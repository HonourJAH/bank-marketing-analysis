# What the data says about who buys a term deposit

## About this report

A Portuguese bank contacted customers by phone between May 2008 and November 2010 to sell a term deposit, a savings product in which money is held for a fixed period. This report examines who subscribed and what was associated with a successful campaign.

**Data and definitions**

- The analysis covers 41,176 contact records. Twelve exact duplicates were removed from the original 41,188.
- The data has no customer ID, so one person may appear more than once. Each record is referred to as a "customer" for readability.
- **Yes rate:** the share of customers contacted who subscribed. The overall yes rate is 11.3%, and every group in this report is compared with it.
- **Campaign year:** the data has no year column. The year is inferred from the row order: the file is in date order, and the month falls back from December to March twice, which gives three blocks, 2008, 2009 and 2010 (decision 10 in the decision log). The year turned out to be the largest difference in the data, so results are shown within each year wherever the year could change the conclusion.
- The findings describe patterns in the data. They do not establish causes.
- n/a means a group has fewer than 100 customers, so no rate is shown.
- Percentages are rounded, so a column may not add to exactly 100%.

---

## The campaign year: the largest difference in the data

**Findings**

*Table Y.1. Yes rate by year*

| Year | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| 2008 | 27,682 | 1,339 | 4.8% | 67.2% | 28.9% |
| 2009 | 11,436 | 2,227 | 19.5% | 27.8% | 48.0% |
| 2010 | 2,058 | 1,073 | 52.1% | 5.0% | 23.1% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table Y.2. Customers and yes rate by month and year (n/a where there are fewer than 100 customers)*

| Month | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate |
|---|---|---|---|---|---|---|
| March | 0 | n/a | 282 | 44.7% | 264 | 56.8% |
| April | 0 | n/a | 2,457 | 18.0% | 174 | 55.7% |
| May | 7,762 | 3.1% | 5,793 | 9.0% | 212 | 57.5% |
| June | 4,374 | 4.3% | 715 | 36.9% | 229 | 46.7% |
| July | 6,681 | 6.1% | 177 | 36.7% | 311 | 56.6% |
| August | 5,173 | 5.2% | 770 | 34.3% | 233 | 51.5% |
| September | 0 | n/a | 267 | 39.7% | 303 | 49.5% |
| October | 67 | n/a | 446 | 40.4% | 204 | 45.6% |
| November | 3,615 | 5.3% | 357 | 47.1% | 128 | 45.3% |
| December | 10 | n/a | 172 | 51.2% | 0 | n/a |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** |

*Table Y.3. The four months with the highest overall yes rates, compared with the other six months*

| Months | Customers in 2008 | Customers in 2009 | Customers in 2010 | Total customers | Share in 2009 and 2010 combined | Subscribed | Yes rate |
|---|---|---|---|---|---|---|---|
| March, September, October and December | 77 | 1,167 | 771 | 2,015 | 96.2% | 936 | 46.5% |
| April, May, June, July, August and November | 27,605 | 10,269 | 1,287 | 39,161 | 29.5% | 3,703 | 9.5% |
| **Total** | **27,682** | **11,436** | **2,058** | **41,176** | **32.8%** | **4,639** | **11.3%** |

- The yes rate rose from 4.8% in 2008 to 19.5% in 2009 and 52.1% in 2010, while the number of customers contacted fell from 27,682 to 2,058 (Table Y.1).
- 2008 accounts for 67.2% of customers but 28.9% of subscriptions. 2010 accounts for 5.0% of customers and 23.1% of subscriptions (Table Y.1).
- The same calendar month gave very different results in different years. May was 3.1% in 2008, 9.0% in 2009 and 57.5% in 2010 (Table Y.2).
- Within 2008 and within 2010 the months differ little: between 3.1% and 6.1% in 2008, and between 45.3% and 57.5% in 2010. In 2009, April (18.0%) and May (9.0%) were far below the other months, which ranged from 34.3% to 51.2% (Table Y.2).
- The four months with the highest overall yes rates (March, September, October and December, combined yes rate 46.5%) had 96.2% of their customers in 2009 and 2010, against 29.5% for the other six months (9.5%). The seasonal pattern in the overall figures is therefore mostly a difference between years (Table Y.3).

**What this means**

When the campaign ran mattered more than any characteristic of the customer or the call examined in this report. The overall figures blend three very different years, so each question below is checked within each year, and a result that appears in only one year is described as such.

**Limitations**

- The year is inferred, not recorded. It relies on the file being in strict date order, which the dataset documentation states and the month sequence supports.
- The data cannot show why the years differ. The economy, whom the bank called and how the campaign was run all changed together.
- The 2010 block has only 2,058 customers, so many groups within it are too small to report. 2008 has no customers in March, April or September, and 2010 has none in December (Table Y.2). The data contains no January or February.
- Each record is a contact, not necessarily a different person.

---

## Question 1. How many customers subscribed, and how many calls did it take?

**Findings**

*Table 1.1. Calls and subscriptions by outcome*

| Outcome | Customers | Share of customers | Calls made | Share of calls | Average calls per customer | Median calls per customer |
|---|---|---|---|---|---|---|
| Subscribed (yes) | 4,639 | 11.3% | 9,519 | 9.0% | 2.05 | 2 |
| Did not subscribe (no) | 36,537 | 88.7% | 96,216 | 91.0% | 2.63 | 2 |
| **Total** | **41,176** | **100%** | **105,735** | **100%** | **2.57** | **2** |

*Table 1.2. Calls per subscription*

| Campaign measure | Value |
|---|---|
| Total calls made | 105,735 |
| Customers who subscribed | 4,639 |
| Calls per subscription | 22.8 |

*Table 1.3. Calls and subscriptions by year*

| Year | Customers | Calls made | Share of all calls | Average calls per customer | Subscribed | Share of all subscriptions | Calls per subscription |
|---|---|---|---|---|---|---|---|
| 2008 | 27,682 | 77,501 | 73.3% | 2.80 | 1,339 | 28.9% | 57.9 |
| 2009 | 11,436 | 24,313 | 23.0% | 2.13 | 2,227 | 48.0% | 10.9 |
| 2010 | 2,058 | 3,921 | 3.7% | 1.91 | 1,073 | 23.1% | 3.7 |
| **Total** | **41,176** | **105,735** | **100%** | **2.57** | **4,639** | **100%** | **22.8** |

- 4,639 of 41,176 customers subscribed, a yes rate of 11.3%.
- The typical customer received two calls whether or not they subscribed: the median is 2 in both groups. The average is 2.05 calls for customers who subscribed and 2.63 for those who did not (Table 1.1).
- Customers who did not subscribe were 88.7% of the call list but received 91.0% of all calls.
- The campaign made 22.8 calls for every subscription (Table 1.2). This is an average across three very different years: 57.9 calls per subscription in 2008, 10.9 in 2009 and 3.7 in 2010 (Table 1.3).
- 2008 used 73.3% of all calls and produced 28.9% of subscriptions. 2010 used 3.7% of the calls and produced 23.1% (Table 1.3).

**What this means**

A typical customer received about two calls, but the effort needed per subscription differed enormously between years. The higher average among customers who did not subscribe, combined with identical medians, suggests that a small group received many calls and mostly did not subscribe. Question 6 examines this.

**Limitations**

- The 22.8 calls per subscription is a campaign-wide ratio that includes every call made to customers who never subscribed. It is not the cost of winning one customer, because the data contains no call costs or deposit values.
- The data cannot show whether additional calls reduce the likelihood of a yes. Customers who subscribe probably receive no further calls, so the two groups are not directly comparable.
- Only calls made during this campaign are counted.
- The three years differ greatly (Table 1.3), and the overall figures blend them. The year is inferred, as described above.

---

## Question 2. Which age groups have the highest yes rate?

**Findings**

*Table 2.1. Yes rate by age group, all years*

| Age group | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Under 25 | 1,067 | 256 | 24.0% | 2.6% | 5.5% |
| 25 to 34 | 13,684 | 1,666 | 12.2% | 33.2% | 35.9% |
| 35 to 44 | 13,495 | 1,168 | 8.7% | 32.8% | 25.2% |
| 45 to 54 | 8,702 | 752 | 8.6% | 21.1% | 16.2% |
| 55 to 64 | 3,566 | 484 | 13.6% | 8.7% | 10.4% |
| 65 and over | 662 | 313 | 47.3% | 1.6% | 6.7% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table 2.2. Customers and yes rate by age group within each year (n/a where there are fewer than 100 customers)*

| Age group | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate |
|---|---|---|---|---|---|---|
| Under 25 | 397 | 6.3% | 513 | 29.2% | 157 | 51.6% |
| 25 to 34 | 8,638 | 5.3% | 4,270 | 19.6% | 776 | 47.0% |
| 35 to 44 | 9,550 | 4.7% | 3,562 | 14.0% | 383 | 56.4% |
| 45 to 54 | 6,631 | 4.2% | 1,790 | 18.2% | 281 | 53.4% |
| 55 to 64 | 2,466 | 5.0% | 881 | 27.5% | 219 | 54.3% |
| 65 and over | 0 | n/a | 420 | 40.7% | 242 | 58.7% |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** |

*All years combined*

- Across all years the yes rate is highest at the two ends of the age range. Customers aged 65 and over subscribed at 47.3% and customers under 25 at 24.0%, against 11.3% overall. Customers aged 35 to 44 and 45 to 54 responded below the overall rate, at 8.7% and 8.6% (Table 2.1).
- Customers aged 65 and over are 1.6% of the call list but account for 6.7% of subscriptions (Table 2.1).

*Within each year*

- The pattern depends on the year (Table 2.2). In 2009 it holds: customers under 25 subscribed at 29.2% and those aged 65 and over at 40.7%, against 19.5% for the year, while customers aged 35 to 44 subscribed at 14.0%.
- In 2008 every age group was between 4.2% and 6.3%, close to the year's 4.8%.
- In 2010 every age group was between 47.0% and 58.7%, around the year's 52.1%, with no clear order by age.
- Customers aged 65 and over appear only in 2009 and 2010, with none in 2008, the year with the lowest yes rate. Their overall 47.3% is therefore not comparable with the other groups. Within the years they appear in, they subscribed at 40.7% in 2009, about twice the year's rate, and at 58.7% in 2010, 6.6 points above the year's rate (Table 2.2).

**What this means**

Age is a weak guide on its own. The oldest and the youngest customers responded best overall, but this partly reflects the year in which they were called. The age pattern appears clearly only in 2009. The oldest customers responded above the year's rate in both years in which they appear. Whether shifting calls toward particular ages would pay off cannot be determined from this data alone.

**Limitations**

- The data shows an association with age, not the reason for it.
- The age groups were chosen for this analysis. Finer age steps, examined across all years, showed a sharp rise in the yes rate at age 60, but this was not tested within each year and is not reported.
- The number of customers in each age group differs by year (Table 2.2), and the year is inferred, as described above.
- Several groups in 2010 are small, between 157 and 776 customers.
- Each record is a contact, not necessarily a different person.

---

## Question 3. Which jobs and education levels have the highest yes rate?

**Findings**

*Table 3.1. Yes rate by job, all years*

| Job | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Student | 875 | 275 | 31.4% | 2.1% | 5.9% |
| Retired | 1,718 | 434 | 25.3% | 4.2% | 9.4% |
| Unemployed | 1,014 | 144 | 14.2% | 2.5% | 3.1% |
| Admin. | 10,419 | 1,351 | 13.0% | 25.3% | 29.1% |
| Management | 2,924 | 328 | 11.2% | 7.1% | 7.1% |
| Unknown | 330 | 37 | 11.2% | 0.8% | 0.8% |
| Technician | 6,739 | 730 | 10.8% | 16.4% | 15.7% |
| Self-employed | 1,421 | 149 | 10.5% | 3.5% | 3.2% |
| Housemaid | 1,060 | 106 | 10.0% | 2.6% | 2.3% |
| Entrepreneur | 1,456 | 124 | 8.5% | 3.5% | 2.7% |
| Services | 3,967 | 323 | 8.1% | 9.6% | 7.0% |
| Blue-collar | 9,253 | 638 | 6.9% | 22.5% | 13.8% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table 3.2. Yes rate by education level (from least to most schooling), all years*

| Education | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Illiterate (too few to rely on) | 18 | 4 | 22.2% | less than 0.1% | 0.1% |
| Basic, 4 years | 4,176 | 428 | 10.2% | 10.1% | 9.2% |
| Basic, 6 years | 2,291 | 188 | 8.2% | 5.6% | 4.1% |
| Basic, 9 years | 6,045 | 473 | 7.8% | 14.7% | 10.2% |
| High school | 9,512 | 1,031 | 10.8% | 23.1% | 22.2% |
| Professional course | 5,240 | 595 | 11.4% | 12.7% | 12.8% |
| University degree | 12,164 | 1,669 | 13.7% | 29.5% | 36.0% |
| Unknown | 1,730 | 251 | 14.5% | 4.2% | 5.4% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table 3.3. Customers and yes rate by job within each year (n/a where there are fewer than 100 customers)*

| Job | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate |
|---|---|---|---|---|---|---|
| Student | 193 | 7.3% | 473 | 32.1% | 209 | 52.2% |
| Retired | 795 | 5.9% | 649 | 36.5% | 274 | 54.7% |
| Unemployed | 662 | 3.6% | 266 | 27.4% | 86 | n/a |
| Admin. | 6,827 | 4.9% | 2,951 | 22.8% | 641 | 53.4% |
| Management | 2,015 | 5.4% | 789 | 20.0% | 120 | 51.7% |
| Unknown | 248 | 5.2% | 64 | n/a | 18 | n/a |
| Technician | 4,870 | 4.7% | 1,552 | 21.5% | 317 | 52.7% |
| Self-employed | 992 | 4.8% | 376 | 20.5% | 53 | n/a |
| Housemaid | 824 | 3.3% | 181 | 26.5% | 55 | n/a |
| Entrepreneur | 1,066 | 5.4% | 364 | 15.1% | 26 | n/a |
| Services | 2,719 | 4.9% | 1,125 | 12.2% | 123 | 43.9% |
| Blue-collar | 6,471 | 4.7% | 2,646 | 10.1% | 136 | 49.3% |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** |

*Table 3.4. Customers and yes rate by education level within each year (n/a where there are fewer than 100 customers)*

| Education | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate |
|---|---|---|---|---|---|---|
| Illiterate | 12 | n/a | 6 | n/a | 0 | n/a |
| Basic, 4 years | 2,935 | 3.7% | 1,040 | 19.8% | 201 | 55.7% |
| Basic, 6 years | 1,609 | 5.0% | 649 | 13.9% | 33 | n/a |
| Basic, 9 years | 4,142 | 4.9% | 1,780 | 11.9% | 123 | 46.3% |
| High school | 6,211 | 5.0% | 2,846 | 17.3% | 455 | 50.5% |
| Professional course | 3,647 | 4.6% | 1,297 | 21.0% | 296 | 52.7% |
| University degree | 7,982 | 5.2% | 3,394 | 24.7% | 788 | 52.3% |
| Unknown | 1,144 | 4.4% | 424 | 26.7% | 162 | 54.3% |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** |

*Job, all years combined*

- Students (31.4%) and retired customers (25.3%) have the highest yes rates, against 11.3% overall (Table 3.1).
- Blue-collar customers have the lowest yes rate (6.9%), followed by services (8.1%) and entrepreneurs (8.5%). Blue-collar customers are 22.5% of the call list but 13.8% of subscriptions.
- Admin. customers are the largest source of subscriptions (29.1%), with a yes rate of 13.0%.
- Management, technician, self-employed, housemaid and unknown customers are close to the overall rate, between 10.0% and 11.2%.

*Education, all years combined*

- University graduates have the highest yes rate among the large groups, at 13.7%. They are 29.5% of the call list but 36.0% of subscriptions (Table 3.2).
- The three groups with basic schooling respond below average: 10.2% for 4 years, 8.2% for 6 years and 7.8% for 9 years.
- Customers with unknown education have a yes rate of 14.5% (1,730 customers).
- Only 18 customers are recorded as illiterate, too few to interpret.

*Job, within each year*

- The differences between jobs appear mainly in 2009 (Table 3.3). That year retired customers (36.5%), students (32.1%), unemployed customers (27.4%) and housemaids (26.5%) were well above the year's 19.5%, and blue-collar (10.1%) and services (12.2%) customers were well below it.
- In 2008 every job with enough customers was between 3.3% and 7.3%, close to the year's 4.8%. In 2010 the jobs with enough customers ranged from 43.9% (services) to 54.7% (retired), around the year's 52.1%.
- Blue-collar and services customers were below the year's rate in both 2009 and 2010 (blue-collar 10.1% and 49.3%, services 12.2% and 43.9%), and level with it in 2008 (4.7% and 4.9%). The 2010 groups are small, 136 and 123 customers.
- Students and retired customers were above the year's rate in 2008 (7.3% and 5.9%) and in 2009, and about level with it in 2010 (52.2% and 54.7%).
- Admin. customers were 3.3 points above the year's rate in 2009 (22.8%) and close to it in 2008 and 2010 (4.9% and 53.4%).

*Education, within each year*

- The differences between education levels also appear mainly in 2009 (Table 3.4): from 11.9% (9 years of basic schooling) and 13.9% (6 years) up to 24.7% (university degree) and 26.7% (unknown), against the year's 19.5%.
- In 2008 every group with enough customers was between 3.7% and 5.2%. In 2010 the groups ranged from 46.3% to 55.7%.
- University graduates were above the year's rate in 2008 (5.2%) and 2009 (24.7%), and level with it in 2010 (52.3%). Customers with 9 years of basic schooling were below the year's rate in 2009 and 2010 (11.9% and 46.3%).
- Customers with 4 years of basic schooling had the lowest rate in 2008 (3.7%) and the highest in 2010 (55.7%, 201 customers), so there is no consistent direction for them.
- Customers with unknown education were above the year's rate in 2009 (26.7%) and 2010 (54.3%), and below it in 2008 (4.4%).

**What this means**

Job and education made almost no difference in 2008 and only a modest one in 2010, and they separated customers clearly in 2009. Across the years in which a gap appears, blue-collar and services customers and customers with 9 years of basic schooling responded below the year's rate, and university graduates above it. Students and retired customers responded well in 2008 and 2009. These are candidates for prioritising or deprioritising when deciding whom to call, but the data cannot show whether calling more customers in the higher-responding groups would produce more subscriptions.

**Limitations**

- The data shows associations, not reasons. It cannot explain why any group responds differently.
- Comparing within a year reduces, but does not remove, other differences between groups, such as age, the month of contact and whom the bank chose to call. Job, education, age and year were not tested together. An earlier analysis that allowed for age across all years, including whether retirement matters beyond age, was not repeated within each year and is not reported.
- Many groups were compared, so small differences should not be relied on. Several groups in 2010 are too small to show a rate (n/a in Tables 3.3 and 3.4).
- Jobs and education levels are as recorded by the bank, and the data cannot show how accurate or current they are. Customers with an unknown job or education are kept as their own group.
- The year is inferred, as described above.
- Each record is a contact, not necessarily a different person.

---

## Question 4. Is a customer's financial profile linked to saying yes?

**Findings**

*Table 4.1. Yes rate by housing loan, personal loan and credit default status, all years*

| Column | Group | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|---|
| Housing loan | Has a housing loan | 21,571 | 2,507 | 11.6% | 52.4% | 54.0% |
| Housing loan | No housing loan | 18,615 | 2,025 | 10.9% | 45.2% | 43.7% |
| Housing loan | Unknown | 990 | 107 | 10.8% | 2.4% | 2.3% |
| Housing loan | **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |
| Personal loan | Has a personal loan | 6,248 | 683 | 10.9% | 15.2% | 14.7% |
| Personal loan | No personal loan | 33,938 | 3,849 | 11.3% | 82.4% | 83.0% |
| Personal loan | Unknown | 990 | 107 | 10.8% | 2.4% | 2.3% |
| Personal loan | **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |
| Credit default | Has credit in default (too few to rely on) | 3 | 0 | 0.0% | less than 0.1% | 0.0% |
| Credit default | No credit in default | 32,577 | 4,196 | 12.9% | 79.1% | 90.5% |
| Credit default | Unknown | 8,596 | 443 | 5.2% | 20.9% | 9.5% |
| Credit default | **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table 4.2. Credit default status within each year (n/a where there are fewer than 100 customers)*

| Credit default status | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate | Share of the group's customers in 2008 |
|---|---|---|---|---|---|---|---|
| No credit in default | 20,501 | 5.0% | 10,061 | 21.0% | 2,015 | 52.1% | 62.9% |
| Unknown | 7,178 | 4.3% | 1,375 | 8.1% | 43 | n/a | 83.5% |
| Has credit in default (too few to rely on) | 3 | n/a | 0 | n/a | 0 | n/a | 100% |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** | **67.2%** |

*Table 4.3. Customers with an unknown credit default status: actual yes rate compared with the rate expected for their years*

The expected rate applies, to the unknown group's customers in each year, the yes rate of customers with a recorded "no" in that year (Table 4.2). It is the rate the group would have if it behaved like those customers in the same years. It is approximate because the yearly rates in Table 4.2 are rounded.

| Measure | Value |
|---|---|
| Customers with an unknown status | 8,596 |
| Actual yes rate | 5.2% |
| Yes rate of customers with a recorded status | 12.9% |
| Expected yes rate, allowing for the years in which they were contacted | about 7.8% |

*Housing and personal loans*

- Having a loan makes little difference to the yes rate. Customers with a housing loan subscribed at 11.6% and those without at 10.9%. Customers with a personal loan subscribed at 10.9% and those without at 11.3%, against 11.3% overall (Table 4.1).
- The 990 customers whose loan status is unknown are the same customers in both columns. Their yes rate is 10.8%, close to the overall rate (Table 4.1).

*Credit default*

- Only 3 customers are recorded as having credit in default, too few to interpret (Table 4.1).
- Customers whose credit default status is unknown subscribed at 5.2%, less than half the overall 11.3%. Customers with a recorded "no" subscribed at 12.9%. Unknown customers are 20.9% of the call list but 9.5% of subscriptions (Table 4.1).
- Most of this difference reflects the year in which these customers were contacted. 83.5% of the unknown customers were contacted in 2008, the year with the lowest yes rate, against 62.9% of customers with a recorded "no" (Table 4.2).
- Within 2008 the two groups responded almost alike: 4.3% for unknown customers and 5.0% for customers with a recorded "no". In 2009 the unknown customers subscribed at 8.1% against 21.0%. Only 43 unknown customers were contacted in 2010, too few to show a rate (Table 4.2).
- Allowing for the years in which they were contacted, the unknown customers would be expected to subscribe at about 7.8%. Their actual rate of 5.2% is lower, so a gap remains, but it is much smaller than the comparison of 5.2% with 12.9% suggests (Table 4.3).

**What this means**

Whether a customer has a housing or personal loan tells the bank very little about who will subscribe. A missing credit default record goes with a lower yes rate, but most of the difference comes from these customers having been contacted mainly in 2008. A smaller gap remains, and it is clearest in 2009, when customers with an unknown status responded at less than half the rate of those with a recorded status. They may be a candidate for lower priority, but the data cannot show whether the missing record matters in itself or goes together with something else that does.

**Limitations**

- The data shows associations, not reasons. "Unknown" means only that the bank has no record, and the data does not say why.
- Contact type, month and age were not allowed for here. Housing loan and personal loan were not tested within each year or together, because each is within one point of the overall yes rate across all years.
- Whether a customer has a loan is as recorded at the time of the call. The data does not show when it was taken or how large it is.
- The expected rate in Table 4.3 is approximate and assumes that customers with an unknown status would otherwise have responded like those with a recorded "no".
- The year is inferred, as described above. Fewer than 100 unknown customers were contacted in 2010.
- Each record is a contact, not necessarily a different person.

---

## Question 5. Do contact method, month and weekday change the yes rate?

**Findings**

*Table 5.1. Yes rate by contact type, all years*

| Contact type | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Cellular | 26,135 | 3,852 | 14.7% | 63.5% | 83.0% |
| Telephone | 15,041 | 787 | 5.2% | 36.5% | 17.0% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Table 5.2. Contact type within each year*

| Year | Cellular customers | Cellular yes rate | Telephone customers | Telephone yes rate | Cellular yes rate as a multiple of the telephone yes rate | Share of all telephone customers in this year |
|---|---|---|---|---|---|---|
| 2008 | 13,970 | 5.7% | 13,712 | 3.9% | 1.5 | 91.2% |
| 2009 | 10,495 | 19.9% | 941 | 14.7% | 1.4 | 6.3% |
| 2010 | 1,670 | 57.7% | 388 | 28.4% | 2.0 | 2.6% |
| **Total** | **26,135** | **14.7%** | **15,041** | **5.2%** | **2.8** | **100%** |

*Table 5.3. Yes rate by month of contact, with the yes rate for each year (n/a where there are fewer than 100 customers)*

| Month | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions | Yes rate 2008 | Yes rate 2009 | Yes rate 2010 |
|---|---|---|---|---|---|---|---|---|
| March | 546 | 276 | 50.5% | 1.3% | 5.9% | n/a | 44.7% | 56.8% |
| April | 2,631 | 539 | 20.5% | 6.4% | 11.6% | n/a | 18.0% | 55.7% |
| May | 13,767 | 886 | 6.4% | 33.4% | 19.1% | 3.1% | 9.0% | 57.5% |
| June | 5,318 | 559 | 10.5% | 12.9% | 12.1% | 4.3% | 36.9% | 46.7% |
| July | 7,169 | 648 | 9.0% | 17.4% | 14.0% | 6.1% | 36.7% | 56.6% |
| August | 6,176 | 655 | 10.6% | 15.0% | 14.1% | 5.2% | 34.3% | 51.5% |
| September | 570 | 256 | 44.9% | 1.4% | 5.5% | n/a | 39.7% | 49.5% |
| October | 717 | 315 | 43.9% | 1.7% | 6.8% | n/a | 40.4% | 45.6% |
| November | 4,100 | 416 | 10.1% | 10.0% | 9.0% | 5.3% | 47.1% | 45.3% |
| December | 182 | 89 | 48.9% | 0.4% | 1.9% | n/a | 51.2% | n/a |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** | **4.8%** | **19.5%** | **52.1%** |
| March, September, October and December combined | 2,015 | 936 | 46.5% | 4.9% | 20.2% | n/a | 42.8% | 51.0% |
| The other six months combined | 39,161 | 3,703 | 9.5% | 95.1% | 79.8% | 4.7% | 16.8% | 52.8% |

*Table 5.4. Yes rate by weekday of contact, all years*

| Weekday | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Monday | 8,512 | 847 | 10.0% | 20.7% | 18.3% |
| Tuesday | 8,086 | 953 | 11.8% | 19.6% | 20.5% |
| Wednesday | 8,134 | 949 | 11.7% | 19.8% | 20.5% |
| Thursday | 8,618 | 1,044 | 12.1% | 20.9% | 22.5% |
| Friday | 7,826 | 846 | 10.8% | 19.0% | 18.2% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |

*Contact type*

- Customers contacted on a cellular phone subscribed at 14.7% and those contacted by telephone at 5.2%, against 11.3% overall. Telephone is 36.5% of the call list but 17.0% of subscriptions (Table 5.1).
- Most telephone customers were contacted in 2008, the year with the lowest yes rate: 91.2% of them, against 13,970 of the 26,135 cellular customers (Table 5.2).
- Within each year, cellular customers still subscribed at a higher rate than telephone customers: 5.7% against 3.9% in 2008, 19.9% against 14.7% in 2009 and 57.7% against 28.4% in 2010. The cellular rate was 1.5, 1.4 and 2.0 times the telephone rate in the three years, against 2.8 times across all years (Table 5.2).
- The telephone groups are small in 2009 and 2010, with 941 and 388 customers (Table 5.2).

*Month*

- Across all years the yes rate varies widely by month, from 6.4% in May to 50.5% in March. March, September, October and December have the highest rates, between 43.9% and 50.5%. Together they are 4.9% of the call list but 20.2% of subscriptions, with a combined yes rate of 46.5% (Table 5.3).
- Most of this reflects the year. The same month gave very different results in different years: May was 3.1% in 2008, 9.0% in 2009 and 57.5% in 2010 (Table 5.3).
- Within 2008, the months with enough customers were between 3.1% and 6.1%, and within 2010 between 45.3% and 57.5% (Table 5.3).
- Within 2009 the months differed more. April (18.0%) and May (9.0%) were far below the other months, which ranged from 34.3% to 51.2% (Table 5.3).
- Within 2009 the four months with the highest overall rates combined subscribed at 42.8%, against 16.8% for the other six months combined, a gap caused by April and May. Within 2010 the two groups were level, at 51.0% and 52.8% (Table 5.3).

*Weekday*

- The weekday makes only a small difference. Yes rates run from 10.0% on Monday to 12.1% on Thursday, and the other three days are within about one point of the overall 11.3% (Table 5.4).

**What this means**

Cellular contacts responded better than telephone contacts in every year, but the difference is smaller than the overall figures suggest, because most telephone calls were made in the weakest year. The monthly pattern in the overall figures is mostly a difference between years. Within a year, the one clear monthly difference is that April and May 2009 responded far below the other months. The day of the week matters little. Whether moving calls between channels or months would raise subscriptions cannot be determined from this data alone.

**Limitations**

- The data shows associations, not reasons. It cannot show whether telephone calls were less effective, or whether telephone customers were a different group or were reached in a different phase of the campaign.
- The year is inferred, as described above. The data contains no January or February, and some months have few customers in a given year, so some rates are not shown (n/a in Table 5.3).
- Contact type and month were not compared with each other within each year, and the weekday result was not tested within each year.
- The month results may partly reflect the economic climate at the time, which Question 9 examines.
- Contact type, month and weekday describe the last contact of the current campaign, as documented by the dataset's authors.
- Each record is a contact, not necessarily a different person.

---

## Question 6. Where does extra calling stop paying off?

**Findings**

*Table 6.1. Yes rate by the total number of calls a customer received, all years*

| Calls received | Customers | Subscribed | Calls made | Yes rate | Share of customers | Share of all subscriptions | Share of all calls |
|---|---|---|---|---|---|---|---|
| 1 | 17,634 | 2,299 | 17,634 | 13.0% | 42.8% | 49.6% | 16.7% |
| 2 | 10,568 | 1,211 | 21,136 | 11.5% | 25.7% | 26.1% | 20.0% |
| 3 | 5,340 | 574 | 16,020 | 10.7% | 13.0% | 12.4% | 15.2% |
| 4 | 2,650 | 249 | 10,600 | 9.4% | 6.4% | 5.4% | 10.0% |
| 5 | 1,599 | 120 | 7,995 | 7.5% | 3.9% | 2.6% | 7.6% |
| 6 to 10 | 2,516 | 159 | 18,274 | 6.3% | 6.1% | 3.4% | 17.3% |
| 11 and over | 869 | 27 | 14,076 | 3.1% | 2.1% | 0.6% | 13.3% |
| **Total** | **41,176** | **4,639** | **105,735** | **11.3%** | **100%** | **100%** | **100%** |
| 6 or more calls, combined | 3,385 | 186 | 32,350 | 5.5% | 8.2% | 4.0% | 30.6% |

*Table 6.2. Subscriptions per 100 calls, by call number, all years*

Call number 3 means every third call made to a customer who received at least three calls. A subscription is counted at the call number on which the customer's contact ended, on the assumption that a customer who subscribes is not called again.

| Call number | Calls made | Subscriptions | Subscriptions per 100 calls | Cumulative share of subscriptions | Cumulative share of calls |
|---|---|---|---|---|---|
| 1 | 41,176 | 2,299 | 5.58 | 49.6% | 38.9% |
| 2 | 23,542 | 1,211 | 5.14 | 75.7% | 61.2% |
| 3 | 12,974 | 574 | 4.42 | 88.0% | 73.5% |
| 4 | 7,634 | 249 | 3.26 | 93.4% | 80.7% |
| 5 | 4,984 | 120 | 2.41 | 96.0% | 85.4% |
| 6 to 10 | 10,039 | 159 | 1.58 | 99.4% | 94.9% |
| 11 and over | 5,386 | 27 | 0.50 | 100.0% | 100.0% |
| **Total** | **105,735** | **4,639** | **4.39** | | |

*Table 6.3. Subscriptions per 100 calls, by call number and year (n/a where fewer than 100 calls were made)*

| Call number | Calls made 2008 | Calls made 2009 | Calls made 2010 | Per 100 calls 2008 | Per 100 calls 2009 | Per 100 calls 2010 | Per 100 calls, all years | Share of these calls made in 2008 |
|---|---|---|---|---|---|---|---|---|
| 1 | 27,682 | 11,436 | 2,058 | 1.95 | 10.39 | 27.70 | 5.58 | 67.2% |
| 2 | 16,628 | 5,941 | 973 | 2.06 | 9.93 | 28.57 | 5.14 | 70.6% |
| 3 | 9,622 | 2,903 | 449 | 2.00 | 8.51 | 30.07 | 4.42 | 74.2% |
| 4 | 5,795 | 1,626 | 213 | 1.59 | 6.64 | 23.00 | 3.26 | 75.9% |
| 5 | 3,891 | 987 | 106 | 1.31 | 4.96 | 18.87 | 2.41 | 78.1% |
| 6 to 10 | 8,641 | 1,283 | 115 | 1.11 | 3.27 | 18.26 | 1.58 | 86.1% |
| 11 and over | 5,242 | 137 | 7 | 0.46 | 2.19 | n/a | 0.50 | 97.3% |
| **Total** | **77,501** | **24,313** | **3,921** | **1.73** | **9.16** | **27.37** | **4.39** | **73.3%** |

*Table 6.4. What a limit on calls per customer would have meant, by year*

Calculated from the customers' call counts: the calls beyond the limit, and the subscriptions from customers whose contact ended after it. Results based on fewer than 30 subscriptions are marked (small count).

| Year | Limit on calls per customer | Calls saved | Share of the year's calls | Subscriptions given up | Share of the year's subscriptions | Calls saved per subscription given up | The year's own calls per subscription |
|---|---|---|---|---|---|---|---|
| 2008 | 3 | 23,569 | 30.4% | 263 | 19.6% | 89.6 | 57.9 |
| 2008 | 5 | 13,883 | 17.9% | 120 | 9.0% | 115.7 | 57.9 |
| 2008 | 10 (small count) | 5,242 | 6.8% | 24 | 1.8% | 218.4 | 57.9 |
| 2009 | 3 | 4,033 | 16.6% | 202 | 9.1% | 20.0 | 10.9 |
| 2009 | 5 | 1,420 | 5.8% | 45 | 2.0% | 31.6 | 10.9 |
| 2009 | 10 (small count) | 137 | 0.6% | 3 | 0.1% | 45.7 | 10.9 |
| 2010 | 3 | 441 | 11.2% | 90 | 8.4% | 4.9 | 3.7 |
| 2010 | 5 (small count) | 122 | 3.1% | 21 | 2.0% | 5.8 | 3.7 |
| 2010 | 10 (small count) | 7 | 0.2% | 0 | 0.0% | n/a | 3.7 |
| All years | 3 | 28,043 | 26.5% | 555 | 12.0% | 50.5 | 22.8 |
| All years | 5 | 15,425 | 14.6% | 186 | 4.0% | 82.9 | 22.8 |
| All years | 10 (small count) | 5,386 | 5.1% | 27 | 0.6% | 199.5 | 22.8 |

*Table 6.5. Yes rate by the total number of calls received, within each year (n/a where there are fewer than 100 customers)*

| Calls received | All-years customers | All-years yes rate | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate | Share of the group's customers in 2008 |
|---|---|---|---|---|---|---|---|---|---|
| 1 | 17,634 | 13.0% | 11,054 | 4.9% | 5,495 | 21.6% | 1,085 | 52.5% | 62.7% |
| 2 | 10,568 | 11.5% | 7,006 | 4.9% | 3,038 | 19.4% | 524 | 53.1% | 66.3% |
| 3 | 5,340 | 10.7% | 3,827 | 5.0% | 1,277 | 19.3% | 236 | 57.2% | 71.7% |
| 4 to 5 | 4,249 | 8.7% | 3,048 | 4.7% | 1,049 | 15.0% | 152 | 45.4% | 71.7% |
| 6 to 10 | 2,516 | 6.3% | 1,930 | 5.0% | 527 | 8.0% | 59 | n/a | 76.7% |
| 11 and over | 869 | 3.1% | 817 | 2.9% | 50 | n/a | 2 | n/a | 94.0% |
| **Total** | **41,176** | **11.3%** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** | **67.2%** |

*Yes rate by calls received*

- Across all years, the more calls a customer received, the lower the yes rate: 13.0% for customers who received one call, 11.5% for two, 10.7% for three and 9.4% for four. It falls to 6.3% for 6 to 10 calls and 3.1% for 11 or more (Table 6.1).
- Customers who received six or more calls are 8.2% of the call list but received 30.6% of all calls and produced 4.0% of subscriptions, a combined yes rate of 5.5% (Table 6.1).
- Within each year the pattern is not steady (Table 6.5). In 2008 the yes rate was between 4.7% and 5.0% for customers who received 1 to 10 calls, and fell to 2.9% only for 11 or more calls (817 customers). In 2009 it fell from 21.6% for one call to 8.0% for 6 to 10 calls. In 2010 it was between 52.5% and 57.2% for 1 to 3 calls and 45.4% for 4 to 5 calls.
- Customers who received many calls were mostly contacted in 2008: 94.0% of those with 11 or more calls and 76.7% of those with 6 to 10, against 67.2% of all customers (Table 6.5).

*The chance of a yes on each call*

- Across all years, early calls were far more productive than later ones. Subscriptions per 100 calls were 5.58 at call 1, 5.14 at call 2, 4.42 at call 3, 3.26 at call 4 and 2.41 at call 5, and fell to 1.58 for calls 6 to 10 and 0.50 for calls 11 and over. From the fourth call, each call produced fewer subscriptions than the campaign average of 4.39 per 100 calls (Table 6.2).
- The first three calls produced 88.0% of subscriptions from 73.5% of all calls, and the first five produced 96.0% from 85.4% of calls. Calls beyond the fifth were therefore 14.6% of the effort and 4.0% of the result (Table 6.2).
- The fall is much smaller within each year (Table 6.3). Subscriptions per 100 calls fell from 1.95 at call 1 to 0.46 for calls 11 and over in 2008, from 10.39 to 2.19 in 2009, and from 27.70 at call 1 to 18.26 for calls 6 to 10 in 2010 (too few calls to show a rate beyond that).
- In 2008 and 2010 the first three calls were about equally productive (1.95, 2.06 and 2.00 in 2008, and 27.70, 28.57 and 30.07 in 2010). Only in 2009 did the rate fall steadily from the first call (10.39, 9.93 and 8.51).
- Later calls were increasingly made in 2008: 67.2% of first calls, rising to 97.3% of calls numbered 11 and over (Table 6.3). This is why the overall decline in Table 6.2 is steeper than the decline within any one year.
- The year mattered more than the call number. A call numbered 6 to 10 in 2010 produced 18.26 subscriptions per 100 calls, against 1.95 for a first call in 2008 (Table 6.3).

*What a limit on calls would have meant*

- Across all years, a limit of 3 calls per customer would have saved 28,043 calls (26.5%) at the cost of 555 subscriptions (12.0%). A limit of 5 would have saved 15,425 calls (14.6%) and given up 186 subscriptions (4.0%) (Table 6.4).
- In every year, the calls saved per subscription given up exceed that year's own number of calls per subscription, so the calls beyond each limit were less productive than the average call (Table 6.4).
- The size of the saving depends on the year. A limit of 3 would have saved 30.4% of the calls in 2008 at the cost of 19.6% of that year's subscriptions, 16.6% of the calls in 2009 for 9.1% of the subscriptions, and 11.2% of the calls in 2010 for 8.4% of the subscriptions (Table 6.4).
- Most of the calls a limit would have saved were made in 2008 (Table 6.4).

**What this means**

Calling effort was spread unevenly relative to results, and later calls were less productive than earlier ones in every year. The overall figures exaggerate this, because most of the heavily called customers were contacted in 2008, when yields were low whatever the call number. A limit on calls would have saved calls at below-average yield in every year, with the largest saving in 2008. Where yields were high, as in 2010, even later calls produced a good number of subscriptions, and a limit would have saved little. Where the right limit lies depends on what a call costs and what a deposit is worth, and the data contains neither.

**Limitations**

- The data shows how results varied with the number of calls, not whether the extra calls caused the lower yes rate. Customers who subscribe are presumably not called again, so customers who received many calls are, by construction, those who kept declining. They are not a random sample of everyone who was called at call 1.
- Tables 6.2 and 6.3 assume that a subscription happens on a customer's last call. The dataset documentation ties the outcome to the end of the last contact, which supports this, but the data does not check it directly.
- The limits in Table 6.4 describe what happened in this campaign, not what would have happened under a limit. The data does not show whether customers would have subscribed with fewer calls, or whether more customers were available to be called with the calls saved.
- The data contains no call costs and no deposit values, so it cannot show where calling stops being worthwhile.
- Results based on fewer than 30 subscriptions, and rates based on fewer than 100 customers or calls, are marked or not shown.
- Only calls made in this campaign are counted. The year is inferred, as described above.
- Each record is a contact, not necessarily a different person.

---

## Question 7. Do customers who were contacted in an earlier campaign respond differently?

**Findings**

*Table 7.1. Yes rate by the outcome of the previous campaign, all years*

| Previous campaign outcome | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|
| Never contacted before | 35,551 | 3,140 | 8.8% | 86.3% | 67.7% |
| Earlier contact ended in failure | 4,252 | 605 | 14.2% | 10.3% | 13.0% |
| Earlier contact ended in success | 1,373 | 894 | 65.1% | 3.3% | 19.3% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** |
| Contacted before, combined | 5,625 | 1,499 | 26.6% | 13.7% | 32.3% |

*Table 7.2. Previous campaign outcome within each year (n/a where there are fewer than 100 customers)*

| Previous campaign outcome | 2008 customers | 2008 yes rate | 2009 customers | 2009 yes rate | 2010 customers | 2010 yes rate | Share of the group's customers in 2009 and 2010 combined |
|---|---|---|---|---|---|---|---|
| Never contacted before | 26,948 | 4.9% | 7,760 | 18.7% | 843 | 44.8% | 24.2% |
| Earlier contact ended in failure | 699 | 3.4% | 2,986 | 12.9% | 567 | 34.6% | 83.6% |
| Earlier contact ended in success | 35 | n/a | 690 | 56.8% | 648 | 77.0% | 97.5% |
| **Total** | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** | **32.8%** |

*Table 7.3. Yes rate by number of earlier contacts, all years*

| Earlier contacts | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions | Share with an earlier success |
|---|---|---|---|---|---|---|
| None | 35,551 | 3,140 | 8.8% | 86.3% | 67.7% | n/a |
| 1 | 4,561 | 967 | 21.2% | 11.1% | 20.8% | 19.0% |
| 2 | 754 | 350 | 46.4% | 1.8% | 7.5% | 42.4% |
| 3 or more | 310 | 182 | 58.7% | 0.8% | 3.9% | 60.6% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** | **3.3%** |

*Table 7.4. Customers contacted before: yes rate by number of earlier contacts and previous outcome, all years*

| Previous outcome | Earlier contacts | Customers | Subscribed | Yes rate |
|---|---|---|---|---|
| Failure | 1 | 3,696 | 451 | 12.2% |
| Failure | 2 | 434 | 112 | 25.8% |
| Failure | 3 or more | 122 | 42 | 34.4% |
| Failure | **All** | **4,252** | **605** | **14.2%** |
| Success | 1 | 865 | 516 | 59.7% |
| Success | 2 | 320 | 238 | 74.4% |
| Success | 3 or more | 188 | 140 | 74.5% |
| Success | **All** | **1,373** | **894** | **65.1%** |

*Table 7.5. Yes rate by days since the previous contact (customers with a recorded gap only; n/a where there are fewer than 100 customers)*

| Days since previous contact | Customers | Subscribed | Yes rate | Share of customers with a recorded gap |
|---|---|---|---|---|
| 0 to 2 | 102 | 55 | 53.9% | 6.7% |
| 3 to 4 | 557 | 361 | 64.8% | 36.8% |
| 5 to 6 | 458 | 318 | 69.4% | 30.2% |
| 7 | 60 | 40 | n/a | 4.0% |
| 8 to 14 | 276 | 157 | 56.9% | 18.2% |
| 15 and over | 62 | 36 | n/a | 4.1% |
| **Total** | **1,515** | **967** | **63.8%** | **100%** |

*Table 7.6. Days since the previous contact, by previous outcome (n/a where there are fewer than 100 customers)*

| Days since previous contact | Earlier success customers | Earlier success yes rate | Earlier failure customers | Earlier failure yes rate |
|---|---|---|---|---|
| 0 to 2 | 102 | 53.9% | 0 | n/a |
| 3 to 4 | 551 | 65.2% | 6 | n/a |
| 5 to 6 | 429 | 70.4% | 29 | n/a |
| 7 | 45 | n/a | 15 | n/a |
| 8 to 14 | 210 | 58.1% | 66 | n/a |
| 15 and over | 36 | n/a | 26 | n/a |
| **Total** | **1,373** | **65.1%** | **142** | not calculated |

*Previous campaign outcome, all years combined*

- Customers whose earlier contact ended in success subscribed at 65.1% (894 of 1,373). They are 3.3% of the call list but account for 19.3% of all subscriptions (Table 7.1).
- Customers whose earlier contact ended in failure subscribed at 14.2% (605 of 4,252), against 8.8% for customers never contacted before (Table 7.1).
- Customers contacted before are 13.7% of the call list and account for 32.3% of subscriptions, with a combined yes rate of 26.6% (Table 7.1).

*Previous campaign outcome, within each year*

- A previous success remains a strong signal, but a smaller one than the overall figures suggest. In 2009 these customers subscribed at 56.8%, against 18.7% for customers never contacted before, 3.0 times as high. In 2010 they subscribed at 77.0% against 44.8%, 1.7 times as high. Only 35 customers with an earlier success were contacted in 2008, too few to show a rate (Table 7.2).
- A previous failure is not a reason to prioritise a customer. In every year, customers whose earlier contact ended in failure subscribed at a lower rate than customers never contacted before: 3.4% against 4.9% in 2008, 12.9% against 18.7% in 2009 and 34.6% against 44.8% in 2010 (Table 7.2).
- The higher overall rate for earlier failures (14.2% against 8.8%, Table 7.1) arose from the years in which these customers were contacted. 83.6% of them were contacted in 2009 and 2010, against 24.2% of customers never contacted before (Table 7.2).
- 97.5% of customers with an earlier success were contacted in 2009 and 2010 (Table 7.2).

*Number of earlier contacts (all years combined)*

- The yes rate rises with the number of earlier contacts: 21.2% for one, 46.4% for two and 58.7% for three or more (Table 7.3).
- Part of this rise is the previous outcome. The share of customers with an earlier success rises from 19.0% for one earlier contact to 42.4% for two and 60.6% for three or more (Table 7.3).
- The count carries some information of its own. Among customers whose earlier contact ended in failure, the yes rate rises from 12.2% for one earlier contact to 25.8% for two and 34.4% for three or more. Among customers with an earlier success it rises from 59.7% to 74.4% for two earlier contacts, then stays at 74.5% for three or more (Table 7.4).
- This was not tested within each year, and it may partly reflect the year in which these customers were contacted.

*Days since the previous contact (all years combined)*

- Only 1,515 customers have a recorded gap since the previous contact, and 1,373 of them are customers whose earlier contact ended in success. The result is therefore mainly about earlier successes (Tables 7.5 and 7.6).
- The yes rate is highest when the earlier contact was 3 to 6 days before: 64.8% for 3 to 4 days and 69.4% for 5 to 6 days. It is lower at 0 to 2 days (53.9%) and at 8 to 14 days (56.9%). Customers contacted exactly 7 days after, and those contacted 15 or more days after, are too few to show a rate (Table 7.5).
- The same pattern holds among earlier successes alone: 65.2% at 3 to 4 days, 70.4% at 5 to 6 days, 58.1% at 8 to 14 days and 53.9% at 0 to 2 days (Table 7.6).
- The gaps between 5 to 6 days and both 0 to 2 days and 8 to 14 days are larger than chance alone would usually produce. The gap between 3 to 4 days and 5 to 6 days is not.
- This was not tested within each year. Since almost all customers with an earlier success were contacted in 2009 and 2010 (Table 7.2), the result describes those two years.

**What this means**

A customer's history with the bank is a useful signal, but a narrower one than the overall figures suggest. Customers whose earlier contact ended in success responded far better than customers never contacted before in both years in which the comparison can be made, at 3.0 times the rate in 2009 and 1.7 times in 2010. They are a small group, and they offer a limited way of improving a call list. An earlier failure is not a reason to prioritise a customer: in every year such customers subscribed at a lower rate than customers never contacted before. Among earlier successes, follow-up 3 to 6 days after the previous contact produced the best response in this data. Whether prioritising earlier customers would raise subscriptions cannot be determined from this data alone.

**Limitations**

- The data shows associations, not reasons. The bank chose whom to contact again, so a high yes rate may partly reflect that selection and not the history itself.
- The data has no customer ID, so it cannot show whether customers with an earlier success already hold a deposit from that campaign, or whether the same person appears more than once.
- The previous outcome and the number of earlier contacts describe the period before this campaign only. The data does not say whether the earlier contacts were in one campaign or several.
- The number of earlier contacts and the days since the previous contact were not tested within each year.
- Days since the previous contact is recorded for only 1,515 of the 5,625 customers contacted before, and the data does not explain why it is missing for the others. The day bands were chosen for this analysis, and timing may overlap with the month of contact.
- Only 35 customers with an earlier success were contacted in 2008, so the comparison cannot be made for that year.
- The year is inferred, as described above. No yes rate is shown where fewer than 100 customers fall in a group.
- Each record is a contact, not necessarily a different person.

---

## Question 8. How do call lengths differ between customers who subscribed and those who did not?

**Findings**

The data records the length of each customer's last contact. The dataset documentation states that the length is not known before a call is made and that the outcome is known once the call ends. This question therefore describes what happened. It is not a way of choosing whom to call.

*Table 8.1. Length of the last call, by outcome (seconds; minutes in brackets for the medians)*

| Outcome | Customers | Median last call | Average last call | Middle half of calls ranged from | to | Talk time (hours) | Share of talk time |
|---|---|---|---|---|---|---|---|
| Subscribed (yes) | 4,639 | 449 (7 min 29 s) | 553.3 | 253.5 | 741.5 | 712.9 | 24.1% |
| Did not subscribe (no) | 36,537 | 164 (2 min 44 s) | 220.9 | 95.0 | 279.0 | 2,241.6 | 75.9% |
| **Total** | **41,176** | **180 (3 min)** | not calculated | not calculated | not calculated | **2,954.5** | **100%** |

*Table 8.2. Yes rate by length of the last call*

| Length of last call | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions | Talk time (hours) | Share of talk time |
|---|---|---|---|---|---|---|---|
| Under 1 minute | 4,179 | 1 | less than 0.1% | 10.1% | less than 0.1% | 40.3 | 1.4% |
| 1 to 2 minutes | 8,612 | 163 | 1.9% | 20.9% | 3.5% | 215.4 | 7.3% |
| 2 to 3 minutes | 7,788 | 394 | 5.1% | 18.9% | 8.5% | 320.7 | 10.9% |
| 3 to 5 minutes | 9,349 | 950 | 10.2% | 22.7% | 20.5% | 602.6 | 20.4% |
| 5 to 10 minutes | 7,770 | 1,441 | 18.5% | 18.9% | 31.1% | 889.7 | 30.1% |
| 10 minutes and over | 3,478 | 1,690 | 48.6% | 8.4% | 36.4% | 885.8 | 30.0% |
| **Total** | **41,176** | **4,639** | **11.3%** | **100%** | **100%** | **2,954.5** | **100%** |
| Under 3 minutes, combined | 20,579 | 558 | 2.7% | 50.0% | 12.0% | 576.4 | 19.5% |
| 5 minutes and over, combined | 11,248 | 3,131 | 27.8% | 27.3% | 67.5% | 1,775.5 | 60.1% |

*Table 8.3. Range of call lengths*

| Measure | Value |
|---|---|
| Shortest call | 0 seconds |
| Median call | 180 seconds |
| Longest call | 4,918 seconds (about 82 minutes) |
| Calls of 0 seconds | 4 |
| Of which subscribed | 0 |

*Call length by outcome*

- Customers who subscribed had a median last call of 449 seconds (7 minutes 29 seconds), against 164 seconds (2 minutes 44 seconds) for those who did not, about 2.7 times as long. The average is 553.3 seconds for customers who subscribed and 220.9 seconds for those who did not (Table 8.1).
- The middle half of calls to customers who subscribed lasted between 253.5 and 741.5 seconds, and for those who did not between 95.0 and 279.0 seconds (Table 8.1).
- Customers who subscribed are 11.3% of customers but account for 24.1% of the talk time, 712.9 of 2,954.5 hours (Table 8.1).
- The shortest call lasted 0 seconds and the longest 4,918 seconds. Four calls lasted 0 seconds, and none led to a subscription (Table 8.3).

*Yes rate by call length*

- The yes rate rises steeply with the length of the call: less than 0.1% for calls under a minute, 1.9% for 1 to 2 minutes, 5.1% for 2 to 3 minutes, 10.2% for 3 to 5 minutes, 18.5% for 5 to 10 minutes and 48.6% for calls of 10 minutes and over (Table 8.2).
- Only 1 of the 4,179 customers whose last call lasted under a minute subscribed (Table 8.2).
- Half of all customers (50.0%) had a last call shorter than 3 minutes. They produced 12.0% of subscriptions, a yes rate of 2.7% (Table 8.2).
- Customers whose last call lasted 5 minutes or more are 27.3% of customers and account for 67.5% of subscriptions, with a yes rate of 27.8%. Calls of 10 minutes and over alone are 8.4% of customers and 36.4% of subscriptions (Table 8.2).

**What this means**

This question describes the calls and does not support a recommendation for the bank. Calls that ended within a minute almost never led to a subscription, and calls of 10 minutes or more produced more than a third of all subscriptions, but call length follows how interested the customer was. An interested customer stays on the line, and a customer who declines ends the call. The data cannot show that keeping customers talking longer would raise subscriptions.

**Limitations**

- The length of a call is not known before the call is made, and the outcome is known once it ends, so length is a result of the call and not something the bank can choose in advance. The dataset documentation says it should be discarded when building a model to predict outcomes.
- Only the length of the last contact is recorded. For customers who received several calls, the talk time is understated, so the 2,954.5 hours is not the total effort of the campaign.
- The data shows what happened and does not show what would happen if calls were handled differently.
- The median is shown for all customers together (180 seconds, Table 8.3). The average and the middle half were not calculated for all customers together.
- Call length was not compared between years, so the figures may blend differences between the three years of the campaign.
- Each record is a contact, not necessarily a different person.

---

## Question 9. Does the economic climate change the yes rate?

**Findings**

The dataset includes five national economic indicators for the time of each contact. They describe the period of the call, not the customer.

*Table 9.1. How closely the indicators move together (1 means identical, 0 means unrelated)*

| Indicator | Employment variation rate | Number employed | Euribor 3 month rate | Consumer price index | Consumer confidence index |
|---|---|---|---|---|---|
| Employment variation rate | 1.00 | 0.91 | 0.97 | 0.78 | 0.20 |
| Number employed | 0.91 | 1.00 | 0.95 | 0.52 | 0.10 |
| Euribor 3 month rate | 0.97 | 0.95 | 1.00 | 0.69 | 0.28 |
| Consumer price index | 0.78 | 0.52 | 0.69 | 1.00 | 0.06 |
| Consumer confidence index | 0.20 | 0.10 | 0.28 | 0.06 | 1.00 |

*Table 9.2. Yes rate by period, in date order (n/a where there are fewer than 100 customers)*

A period is an unbroken block of rows with the same value of number employed. The employment variation rate of each period is matched from the customer and subscriber counts.

| Period | Year | Months | Number employed | Employment variation rate | Customers | Subscribed | Yes rate |
|---|---|---|---|---|---|---|---|
| 1 | 2008 | May | 5,191.0 | 1.1 | 7,762 | 240 | 3.1% |
| 2 | 2008 | June to August | 5,228.1 | 1.4 | 16,228 | 866 | 5.3% |
| 3 | 2008 | October to November | 5,195.8 | -0.1 | 3,682 | 232 | 6.3% |
| 4 | 2008 | December | 5,176.3 | -0.2 | 10 | 1 | n/a |
| 5 | 2009 | March to May | 5,099.1 | -1.8 | 8,532 | 1,092 | 12.8% |
| 6 | 2009 | June to August | 5,076.2 | -2.9 | 1,662 | 593 | 35.7% |
| 7 | 2009 | September to November | 5,017.5 | -3.4 | 1,070 | 454 | 42.4% |
| 8 | 2009 | December | 5,023.5 | -3.0 | 172 | 88 | 51.2% |
| 9 | 2010 | March to May | 5,008.7 | -1.8 | 650 | 369 | 56.8% |
| 10 | 2010 | June to August | 4,991.6 | -1.7 | 773 | 403 | 52.1% |
| 11 | 2010 | September to November | 4,963.6 | -1.1 | 635 | 301 | 47.4% |
| | | **Total** | | | **41,176** | **4,639** | **11.3%** |

*Table 9.3. Number employed by year*

| Year | Periods | Lowest number employed | Highest number employed | Customers | Subscribed | Yes rate |
|---|---|---|---|---|---|---|
| 2008 | 4 | 5,176.3 | 5,228.1 | 27,682 | 1,339 | 4.8% |
| 2009 | 4 | 5,017.5 | 5,099.1 | 11,436 | 2,227 | 19.5% |
| 2010 | 3 | 4,963.6 | 5,008.7 | 2,058 | 1,073 | 52.1% |
| **Total** | **11** | | | **41,176** | **4,639** | **11.3%** |

*Table 9.4. Yes rate by level of the euribor 3 month rate, the consumer price index and the consumer confidence index*

Each indicator is divided into five bands containing similar numbers of customers.

| Indicator | Band (lowest to highest) | Customers | Subscribed | Yes rate |
|---|---|---|---|---|
| Euribor 3 month rate | 0.634 to 1.299 | 8,634 | 2,560 | 29.7% |
| Euribor 3 month rate | Above 1.299 to 4.191 | 8,427 | 909 | 10.8% |
| Euribor 3 month rate | Above 4.191 to 4.864 | 8,445 | 306 | 3.6% |
| Euribor 3 month rate | Above 4.864 to 4.962 | 8,496 | 469 | 5.5% |
| Euribor 3 month rate | Above 4.962 to 5.045 | 7,174 | 395 | 5.5% |
| Consumer price index | 92.201 to 92.893 | 8,274 | 1,522 | 18.4% |
| Consumer price index | Above 92.893 to 93.444 | 12,224 | 1,317 | 10.8% |
| Consumer price index | Above 93.444 to 93.918 | 7,134 | 668 | 9.4% |
| Consumer price index | Above 93.918 to 93.994 | 7,762 | 240 | 3.1% |
| Consumer price index | Above 93.994 to 94.767 | 5,782 | 892 | 15.4% |
| Consumer confidence index | -50.8 to -46.2 | 8,864 | 1,243 | 14.0% |
| Consumer confidence index | Above -46.2 to -42.0 | 10,306 | 598 | 5.8% |
| Consumer confidence index | Above -42.0 to -40.0 | 5,679 | 792 | 13.9% |
| Consumer confidence index | Above -40.0 to -36.4 | 8,527 | 617 | 7.2% |
| Consumer confidence index | Above -36.4 to -26.9 | 7,800 | 1,389 | 17.8% |

*How the indicators relate to each other*

- The employment variation rate, number employed and the euribor rate move closely together, with correlations between 0.91 and 0.97. They describe the same changes over time and are not three separate findings. The consumer price index is moderately related to them (0.52 to 0.78) and the consumer confidence index only slightly (0.06 to 0.28) (Table 9.1).

*The yes rate over time*

- The yes rate by period ranged from 3.1% in May 2008 to 56.8% in March to May 2010 (Table 9.2).
- March to May 2009 and March to May 2010 cover the same months and share the same employment variation rate (-1.8), yet the yes rates were 12.8% and 56.8% (Table 9.2).
- Within 2009 the yes rate rose through the year, from 12.8% to 51.2%, as the number employed fell from 5,099.1 to 5,023.5. Within 2010 the number employed fell from 5,008.7 to 4,963.6 while the yes rate fell from 56.8% to 47.4%. Within 2008 it stayed between 3.1% and 6.3% (Table 9.2).

*The indicators and the year*

- The number employed falls from one year to the next, and its ranges do not overlap: 5,176.3 to 5,228.1 in 2008, 5,017.5 to 5,099.1 in 2009 and 4,963.6 to 5,008.7 in 2010 (Table 9.3). It therefore identifies the year. Any link between it and the yes rate cannot be separated from everything else that changed between the years.
- The euribor rate follows the same pattern as the yes rate across years: the lowest band has a yes rate of 29.7% and the top three bands between 3.6% and 5.5% (Table 9.4). The euribor rate is closely related to the number employed (0.95, Table 9.1), so this is not an independent result.
- The consumer price index and the consumer confidence index show no steady direction. Across their five bands the yes rate ranges from 3.1% to 18.4% for the price index and from 5.8% to 17.8% for the confidence index (Table 9.4).

**What this means**

The yes rate was far higher in the later periods, when the number employed and the euribor rate were lower. These indicators cannot be separated from the year, however, and within a year they do not consistently follow the yes rate. The data therefore cannot show that the economic climate caused the differences between years. The same differences could come from whom the bank called, how the campaign was run, or other things that changed over time. For planning, a result from one period should not be used as a benchmark for another.

**Limitations**

- The data shows associations, not reasons. There are only 11 periods, and the three main indicators move together, so the data holds far less independent evidence about the economy than its 41,176 customers suggest.
- The periods are identified as blocks of rows with the same number employed, not as calendar quarters. For example, May and June 2008 fall in different periods. The year is inferred, as described above.
- The indicators are national figures, not customer information. The dataset documentation describes them as quarterly, monthly or daily.
- Period 4 has only 10 customers, so no rate is shown.
- Each record is a contact, not necessarily a different person.

---

## Question 10. Which combinations of customer and campaign features have the highest and lowest yes rate?

**Findings**

The earlier questions looked at one feature at a time. A call list would combine them, so this question ranks combinations, called segments. A segment is a combination of three features that the bank knows before dialling: the outcome of the previous campaign (never contacted, earlier failure or earlier success), the contact type (cellular or telephone) and the age group (under 25, 25 to 34, 35 to 54, or 55 and over). That gives 24 segments. The length of the call (Question 8) and the number of calls received (Question 6) are not used, because they are only known once a contact is under way.

Because the year is the largest difference in the data, each segment is compared with the yes rate of its own year, shown as "times the year's rate". A value of 2.00 means twice the yes rate of all customers in that year, and 1.00 means the same. A segment is ranked only where it has at least 100 customers in a year, and a segment that is above (or below) its year's rate in every year where it can be measured is more trustworthy than one that is not.

*Table 10.1. All 24 segments, all years combined (in the order of their 2009 result)*

| Previous outcome | Contact type | Age group | Customers | Subscribed | Yes rate | Share of customers | Share of all subscriptions | Measurable in |
|---|---|---|---|---|---|---|---|---|
| Earlier success | Cellular | 55 and over | 276 | 204 | 73.9% | 0.7% | 4.4% | 2 or more years |
| Earlier success | Cellular | 25 to 34 | 417 | 263 | 63.1% | 1.0% | 5.7% | 2 or more years |
| Earlier success | Cellular | 35 to 54 | 490 | 301 | 61.4% | 1.2% | 6.5% | 2 or more years |
| Never contacted | Cellular | 55 and over | 2,137 | 375 | 17.5% | 5.2% | 8.1% | 2 or more years |
| Never contacted | Cellular | Under 25 | 583 | 129 | 22.1% | 1.4% | 2.8% | 2 or more years |
| Earlier failure | Cellular | Under 25 | 156 | 46 | 29.5% | 0.4% | 1.0% | 1 year only |
| Earlier failure | Cellular | 55 and over | 457 | 119 | 26.0% | 1.1% | 2.6% | 2 or more years |
| Never contacted | Cellular | 25 to 34 | 7,352 | 959 | 13.0% | 17.9% | 20.7% | 2 or more years |
| Never contacted | Telephone | 55 and over | 1,313 | 81 | 6.2% | 3.2% | 1.7% | 2 or more years |
| Never contacted | Telephone | 25 to 34 | 4,400 | 229 | 5.2% | 10.7% | 4.9% | 2 or more years |
| Never contacted | Cellular | 35 to 54 | 10,841 | 990 | 9.1% | 26.3% | 21.3% | 2 or more years |
| Earlier failure | Cellular | 25 to 34 | 1,357 | 181 | 13.3% | 3.3% | 3.9% | 2 or more years |
| Never contacted | Telephone | 35 to 54 | 8,706 | 364 | 4.2% | 21.1% | 7.8% | 2 or more years |
| Earlier failure | Cellular | 35 to 54 | 1,982 | 225 | 11.4% | 4.8% | 4.9% | 2 or more years |
| Earlier failure | Telephone | 25 to 34 | 122 | 12 | 9.8% | 0.3% | 0.3% | 1 year only |
| Earlier failure | Telephone | 35 to 54 | 138 | 15 | 10.9% | 0.3% | 0.3% | 1 year only |
| Earlier failure | Telephone | 55 and over | 28 | 6 | 21.4% | 0.1% | 0.1% | 1 year only |
| Earlier failure | Telephone | Under 25 | 12 | 1 | 8.3% | less than 0.1% | less than 0.1% | 1 year only |
| Earlier success | Cellular | Under 25 | 87 | 60 | 69.0% | 0.2% | 1.3% | 1 year only |
| Earlier success | Telephone | 25 to 34 | 36 | 22 | 61.1% | 0.1% | 0.5% | 1 year only |
| Earlier success | Telephone | 35 to 54 | 40 | 25 | 62.5% | 0.1% | 0.5% | 1 year only |
| Earlier success | Telephone | 55 and over | 17 | 12 | 70.6% | less than 0.1% | 0.3% | 1 year only |
| Earlier success | Telephone | Under 25 | 10 | 7 | 70.0% | less than 0.1% | 0.2% | 1 year only |
| Never contacted | Telephone | Under 25 | 219 | 13 | 5.9% | 0.5% | 0.3% | 1 year only |
| **Total** | | | **41,176** | **4,639** | **11.3%** | **100%** | **100%** | |

*Table 10.2. The 13 segments that can be measured in two or more years: customers, yes rate and times the year's rate (n/a where there are fewer than 100 customers)*

| Previous outcome | Contact type | Age group | 2008 customers | 2008 yes rate (times the year's rate) | 2009 customers | 2009 yes rate (times the year's rate) | 2010 customers | 2010 yes rate (times the year's rate) | Pattern |
|---|---|---|---|---|---|---|---|---|---|
| Earlier success | Cellular | 55 and over | 3 | n/a | 134 | 66.4% (3.41) | 139 | 82.0% (1.57) | Above in both years measured |
| Earlier success | Cellular | 25 to 34 | 9 | n/a | 208 | 55.8% (2.86) | 200 | 72.5% (1.39) | Above in both years measured |
| Earlier success | Cellular | 35 to 54 | 20 | n/a | 273 | 52.0% (2.67) | 197 | 80.7% (1.55) | Above in both years measured |
| Never contacted | Cellular | 55 and over | 1,236 | 5.7% (1.19) | 752 | 31.0% (1.59) | 149 | 47.7% (0.91) | Mixed |
| Never contacted | Cellular | Under 25 | 225 | 7.6% (1.56) | 328 | 30.2% (1.55) | 30 | n/a | Above in both years measured |
| Earlier failure | Cellular | 55 and over | 52 | n/a | 290 | 22.8% (1.17) | 115 | 43.5% (0.83) | Mixed |
| Never contacted | Cellular | 25 to 34 | 4,440 | 6.3% (1.31) | 2,676 | 20.3% (1.04) | 236 | 56.8% (1.09) | Slightly above in all three years |
| Never contacted | Telephone | 55 and over | 1,175 | 4.1% (0.84) | 102 | 18.6% (0.96) | 36 | n/a | Below in both years measured |
| Never contacted | Telephone | 25 to 34 | 3,988 | 4.4% (0.90) | 295 | 14.9% (0.77) | 117 | 9.4% (0.18) | Below in all three years |
| Never contacted | Cellular | 35 to 54 | 7,385 | 5.5% (1.14) | 3,272 | 14.4% (0.74) | 184 | 61.4% (1.18) | Mixed |
| Earlier failure | Cellular | 25 to 34 | 181 | 2.8% (0.57) | 1,006 | 12.1% (0.62) | 170 | 31.8% (0.61) | Below in all three years |
| Never contacted | Telephone | 35 to 54 | 8,327 | 3.7% (0.76) | 303 | 11.9% (0.61) | 76 | n/a | Below in both years measured |
| Earlier failure | Cellular | 35 to 54 | 419 | 3.3% (0.69) | 1,410 | 11.3% (0.58) | 153 | 33.3% (0.64) | Below in all three years |
| **Yes rate of all customers in the year** | | | **27,682** | **4.8%** | **11,436** | **19.5%** | **2,058** | **52.1%** | |

*Table 10.3. The strongest and weakest groups of segments*

The yes rate here is for all years combined, so it blends years. The comparison with each year's own rate is in Table 10.2.

| Group of segments | Segments | Customers | Subscribed | Yes rate, all years | Share of customers | Share of all subscriptions |
|---|---|---|---|---|---|---|
| Earlier success, cellular, ages 25 to 34, 35 to 54 and 55 and over | 3 | 1,183 | 768 | 64.9% | 2.9% | 16.6% |
| Earlier failure, cellular, ages 25 to 34 and 35 to 54 | 2 | 3,339 | 406 | 12.2% | 8.1% | 8.8% |
| Never contacted, telephone, ages 25 to 34 and 35 to 54 | 2 | 13,106 | 593 | 4.5% | 31.8% | 12.8% |
| The two weakest groups combined | 4 | 16,445 | 999 | 6.1% | 39.9% | 21.5% |

*Table 10.4. How many segments can be measured*

| Segments measurable in | Segments | Customers | Share of customers | Subscribed | Share of all subscriptions | Yes rate, all years |
|---|---|---|---|---|---|---|
| Two or more years | 13 | 40,311 | 97.9% | 4,420 | 95.3% | 11.0% |
| One year only | 11 | 865 | 2.1% | 219 | 4.7% | 25.3% |
| **Total** | **24** | **41,176** | **100%** | **4,639** | **100%** | **11.3%** |

*Table 10.5. Customers with an earlier success, by contact type, all years*

| Contact type | Customers | Share of customers with an earlier success | Subscribed | Yes rate |
|---|---|---|---|---|
| Cellular | 1,270 | 92.5% | 828 | 65.2% |
| Telephone | 103 | 7.5% | 66 | 64.1% |
| **Total** | **1,373** | **100%** | **894** | **65.1%** |

*Table 10.6. Customers contacted by cellular: earlier failure compared with never contacted, by age group and year (only where both groups have at least 100 customers)*

| Age group | Year | Earlier failure customers | Earlier failure yes rate | Never contacted customers | Never contacted yes rate |
|---|---|---|---|---|---|
| Under 25 | 2009 | 105 | 22.9% | 328 | 30.2% |
| 25 to 34 | 2008 | 181 | 2.8% | 4,440 | 6.3% |
| 25 to 34 | 2009 | 1,006 | 12.1% | 2,676 | 20.3% |
| 25 to 34 | 2010 | 170 | 31.8% | 236 | 56.8% |
| 35 to 54 | 2008 | 419 | 3.3% | 7,385 | 5.5% |
| 35 to 54 | 2009 | 1,410 | 11.3% | 3,272 | 14.4% |
| 35 to 54 | 2010 | 153 | 33.3% | 184 | 61.4% |
| 55 and over | 2009 | 290 | 22.8% | 752 | 31.0% |
| 55 and over | 2010 | 115 | 43.5% | 149 | 47.7% |

*The strongest segments*

- Customers with an earlier success who were contacted by cellular, aged 25 to 34, 35 to 54 or 55 and over, are the strongest segments. Their yes rates across all years are 63.1%, 61.4% and 73.9% (Table 10.1).
- They are above their year's rate in both years in which they can be measured. In 2009 they subscribed at 2.86, 2.67 and 3.41 times the year's rate, and in 2010 at 1.39, 1.55 and 1.57 times (Table 10.2). Fewer than 100 of them were contacted in 2008, so that year cannot be assessed.
- Together they are 1,183 customers, 2.9% of the call list, and account for 16.6% of all subscriptions (Table 10.3).
- Customers with an earlier success who were reached by cellular under 25, or by telephone at any age, had similar yes rates (61.1% to 70.6%), but these segments have between 10 and 87 customers each and can be measured in only one year, so they are not ranked (Table 10.1).
- Customers with an earlier success responded about as well by telephone (64.1%) as by cellular (65.2%), but only 103 of the 1,373 were contacted by telephone (Table 10.5).

*The weakest segments*

- Customers whose earlier contact ended in failure, contacted by cellular, aged 25 to 34 and 35 to 54, are below their year's rate in all three years, at between 0.57 and 0.69 times (Table 10.2). They are 3,339 customers, 8.1% of the call list (Table 10.3).
- At every age and in every year where both groups can be measured, a customer with an earlier failure subscribed at a lower rate than a customer of the same age, contacted by cellular, who had never been contacted before. This holds in all nine comparisons (Table 10.6). The difference is largest in 2010, for example 33.3% against 61.4% at ages 35 to 54.
- Customers never contacted before, reached by telephone, aged 25 to 34 and 35 to 54, are also below their year's rate in every year in which they can be measured: 0.90, 0.77 and 0.18 times at ages 25 to 34, and 0.76 and 0.61 times at ages 35 to 54 (Table 10.2). They are 13,106 customers, 31.8% of the call list (Table 10.3).
- The two weakest groups together are 39.9% of the call list and 21.5% of subscriptions (Table 10.3).

*The segments without a stable pattern*

- The largest segment, customers never contacted before, reached by cellular, aged 35 to 54, is 10,841 customers (26.3% of the call list, 21.3% of subscriptions). It is above its year's rate in 2008 and 2010 (1.14 and 1.18 times) and below it in 2009 (0.74 times), so it has no stable direction (Tables 10.1 and 10.2).
- Customers never contacted before, reached by cellular, aged 25 to 34, are only slightly above their year's rate in all three years (1.31, 1.04 and 1.09 times), a weak signal (Table 10.2).
- Customers never contacted before, reached by cellular, under 25, are above their year's rate in both years in which they can be measured (1.56 and 1.55 times). Those aged 55 and over are above it in 2008 and 2009 (1.19 and 1.59 times) and below it in 2010 (0.91 times, 149 customers) (Table 10.2).

*How much of the call list the ranking covers*

- Thirteen of the 24 segments can be measured in two or more years. They hold 97.9% of the customers and 95.3% of the subscriptions. The other eleven segments are small (865 customers in total) and can be measured in only one year, so they are not ranked (Table 10.4).

**What this means**

A call list built only from what the bank knows before dialling would place customers with an earlier success first, by cellular where possible. They are a small group, 3.3% of the call list, so they can start a list but cannot fill one. Customers with an earlier failure, and customers never contacted before who are reached by telephone at ages 25 to 54, would come last. They are 39.9% of the call list and responded below their year's rate in every year in which they could be measured. Most other customers sit in segments with no stable direction, so the ranking does not replace the judgement of the campaign team. Whether calling in this order would raise the number of subscriptions cannot be determined from this data alone.

**Limitations**

- The segments were chosen after looking at the data, so one that looks strong has partly been selected for looking strong. Consistency across years is the safeguard used here, but the ranking has not been tested on a separate campaign.
- The data shows associations, not reasons. The bank chose whom to contact and by what channel, so a segment's yes rate partly reflects that selection.
- The age groups and the labels for the previous outcome were chosen for this analysis. Job and education were not included, because they mattered mainly in 2009 (Question 3) and splitting these segments further would leave very few customers in each group.
- In 2010 the yes rate of all customers is 52.1%, so a segment cannot exceed about 1.9 times that year's rate, whereas in 2009 it can reach about five times. Multiples from different years are therefore not directly comparable, and the direction (above or below) matters more than the size.
- Eleven segments, with 865 customers in total, can be measured in only one year and are not ranked. Where a segment has fewer than 100 customers in a year, no rate is shown.
- The year is inferred, as described above.
- Each record is a contact, not necessarily a different person.
