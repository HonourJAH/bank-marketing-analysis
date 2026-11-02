# Decision log

Each entry records what profiling found, what was decided, and why. Entries are added as profiling and cleaning proceed.

## 1. "unknown" values are kept as their own category

**Found**
- No blank cells in any column. Six columns use the text "unknown": default (8,597 rows, 20.87%), education (1,731, 4.20%), housing (990, 2.40%), loan (990, 2.40%), job (330, 0.80%), marital (80, 0.19%).
- 30,488 rows (74%) have no unknown value; 328 rows have three or more.
- The 990 unknown housing rows are exactly the same rows as the 990 unknown loan rows.
- Yes rate (overall 11.27%): unknown default 5.15% vs known 12.88%; unknown education 14.50% vs known 11.12%; housing, loan and job within about half a point of known; marital 15.00% but on only 80 rows, too few to conclude.

**Decision**
Keep "unknown" as its own category in all six columns. Do not drop rows and do not impute values. Housing and loan are treated as one decision because their unknown rows are identical.

**Why**
Dropping unknown-default rows would remove 8,597 customers who respond very differently from the rest and would bias every later result. Imputing would invent values the bank never recorded.

**Limit**
The data shows unknown-default customers respond less often. It cannot show why.

## 2. pdays = 999 is a placeholder, not a number of days

**Found**
- 39,673 rows (96.32%) have pdays = 999; the other 1,515 have real day counts (min 0, median 6, max 27, none failed conversion).
- All 35,563 rows with poutcome = nonexistent have pdays = 999, and every row with previous = 0 has pdays = 999.
- 4,110 further rows have pdays = 999 but previous above 0 and poutcome = failure: they were contacted before, but the days since contact is not recorded.
- All 1,373 poutcome = success rows have a real pdays value.

**Decision**
Keep the raw pdays unchanged. In the clean data, set pdays to missing where it is 999 and add a column previously_contacted (previous above 0). Keep poutcome = nonexistent as its own category.

**Why**
Treating 999 as a number of days would distort averages and any analysis of time since last contact. previous is the more reliable indicator of earlier contact, because 999 covers two different situations.

**Limit**
The data does not explain why pdays is missing for the 4,110 earlier-contacted customers. The assumption that poutcome = nonexistent and previous = 0 are the same rows is very likely (both are 35,563 rows) but not directly checked.

## 3. Exact duplicate rows are removed in the clean data

**Found**
- 12 pairs (24 rows) identical in all 21 columns. Five pairs are on adjacent rows; the rest are 3 to 144 rows apart.
- Yes rate: 11.265% with the duplicates, 11.266% without the 12 extra copies.

**Decision**
Remove the 12 extra copies (keep the first of each pair) in the clean data. The raw data is unchanged. 41,188 rows become 41,176.

**Why**
The pairs match on every column, including call duration to the second. Double-counting is the safer error to avoid, and the effect on the yes rate is 0.001 points either way.

**Limit**
There is no customer ID, so the data cannot prove these are recording errors; two different customers could match on every column.

## 4. Unusual values are kept

**Found**
- age under 18: 5 rows (2 yes). duration = 0: 4 rows (all no).
- campaign above 10: 869 rows, 3.11% yes; campaign above 30: 33 rows, none yes.
- Other ranges are plausible: age 17 to 98, duration up to 4,918 seconds, campaign up to 56, previous 0 to 7.

**Decision**
Keep all rows. No capping, no removal.

**Why**
The values are possible, and the large group (campaign above 10) shows a real pattern that removing it would hide.

**Limit**
The data cannot show whether any of these are entry errors. The age and duration groups are too small to analyse on their own. In the analysis, use medians or banded groups for campaign, not plain averages.

## 5. Economic indicators describe the period of the call

**Found**
- Distinct values across 41,188 rows: emp.var.rate 10, cons.price.idx 26, cons.conf.idx 26, euribor3m 316, nr.employed 11.

**Decision**
Keep as numeric columns. Treat them as context about the time of the call, not as customer attributes, and keep the questions about them separate from the questions about customers in the findings.

**Why**
So few distinct values means many customers share the same value.

**Limit**
This is inferred from the counts. It should be confirmed against the dataset documentation, to be linked in data/README.md.

## 6. Categorical columns are kept as they are; small groups are flagged, not merged

**Found**
- Stripping spaces changed 0 cells; no column has the same value in two casings.
- job (12 values), marital (4), education (8), default (3), housing (3), loan (3), contact (2), month (10), day_of_week (5), poutcome (3) and y (2) contain no typos or unexpected categories. Every column's counts add up to 41,188.
- Small groups: default = yes has 3 rows; education = illiterate has 18; month = dec has 182 and mar 546 (may has 13,769).
- month has no January or February; day_of_week is Monday to Friday only; contact is 26,144 cellular and 15,044 telephone.

**Decision**
Keep all categories unchanged. Do not merge or drop small groups. In the analysis, show the row count beside every rate and draw no conclusion from a group under 100 rows.

**Why**
Nothing in these columns needs correcting. Merging small groups would hide them, and rates on a handful of rows would look more certain than they are.

**Limit**
The data cannot say why January and February are absent, or whether one month name combines several years (the documentation reportedly covers 2008 to 2010, to be confirmed). default = yes cannot support any statement about defaulters.

## 7. Dataset documentation checked; duration is treated as an outcome of the call

**Found** (in `bank-additional-names.txt`)
- duration: the documentation says it strongly affects the target (duration = 0 means "no"), is not known before a call, and should be discarded for a realistic predictive model. In our data, all 4 rows with duration = 0 are "no".
- pdays: 999 is documented as "not previously contacted". This fits 35,563 rows but not the 4,110 rows with pdays = 999, previous above 0 and poutcome = failure.
- Economic indicators are documented as quarterly (emp.var.rate, nr.employed), monthly (cons.price.idx, cons.conf.idx) and daily (euribor3m); nr.employed has 11 distinct values, matching the 11 quarters from May 2008 to November 2010.
- "unknown" is the documented missing-value code, to be kept as a class, deleted or imputed. marital = divorced means divorced or widowed.
- The file is ordered by date, May 2008 to November 2010, with no year column.

**Decision**
Keep duration in the clean data, but treat it as an outcome of the call, not something the bank can set beforehand. Do not use it to explain who will say yes in advance; analyse it separately and label it that way. Decisions 1, 2 and 5 stand.

**Why**
The call's length is only known once the call ends, at which point y is known too.

**Limit**
The documentation does not explain the 4,110 rows where pdays = 999 conflicts with an earlier contact. The data cannot explain them either.

## 8. Columns are renamed to readable names in the clean data

**Found**
- Several original names contain dots (emp.var.rate, cons.price.idx, cons.conf.idx, nr.employed), which are awkward to use in pandas, and some are unclear on their own (default, campaign, y).

**Decision**
Rename all columns in the clean data. The raw data keeps the original UCI names. One column is added: previously_contacted (see decision 2).

| UCI name | Clean name |
|---|---|
| age | age |
| job | job |
| marital | marital_status |
| education | education |
| default | credit_default |
| housing | housing_loan |
| loan | personal_loan |
| contact | contact_type |
| month | contact_month |
| day_of_week | contact_weekday |
| duration | call_duration_seconds |
| campaign | contacts_this_campaign |
| pdays | days_since_previous_contact |
| previous | contacts_before_campaign |
| poutcome | previous_campaign_outcome |
| emp.var.rate | employment_variation_rate |
| cons.price.idx | consumer_price_index |
| cons.conf.idx | consumer_confidence_index |
| euribor3m | euribor_3_month_rate |
| nr.employed | number_employed |
| y | subscribed_term_deposit |

**Why**
Clear names let the findings and code be read without a code book, and the mapping keeps every column traceable to the dataset documentation.

**Check**
Renaming back to the original names gives a table identical to the one before renaming, so only labels changed.
