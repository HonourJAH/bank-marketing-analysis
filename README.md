# Bank Marketing Campaign Analysis

An analysis, in Python and pandas, of phone marketing campaigns run by a Portuguese bank to sell term deposits. It asks who said yes, and what made the campaign work.

## Business problem

Between May 2008 and November 2010 the bank phoned customers to sell a term deposit, a savings product in which money is held for a fixed period. Most customers said no. A call centre manager would want to know whom to call first, how many calls are worth making, and which results can be trusted. This project answers ten business questions from the data and states plainly what the data can and cannot show.

## Data

- **Source:** Bank Marketing dataset, UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/222/bank%2Bmarket), CC BY 4.0
- **File used:** `bank-additional-full.csv`, 41,188 contact records and 21 columns
- **Target:** whether the customer subscribed to a term deposit (yes or no)
- **Not committed:** the data files are blocked in `.gitignore`. See `data/README.md` for the citation and how to download the file.

## Approach

1. **Load the raw data unchanged**, as text, so nothing is converted silently.
2. **Profile the raw data** before touching it: blank cells, "unknown" values, placeholders, numeric ranges, duplicates and categories.
3. **Log every decision** in `docs/decision-log.md`, with what was found, what was decided, why, and the limit of the decision.
4. **Clean a copy** of the data and keep the raw data intact. Every step is reconciled against the profiling numbers.
5. **Validate the clean data** from a separate notebook, rebuilding the differences from the raw file.
6. **Answer ten business questions**, one notebook each, and write each finding in plain language in `docs/findings.md`.

## Main data decisions

| Decision | What was done |
|---|---|
| Duplicates | 12 exact duplicate rows removed (41,188 rows became 41,176). The effect on the yes rate is 0.001 percentage points either way. |
| "unknown" values | Kept as their own category in six columns. Dropping them would have removed 26% of the rows, and customers with an unknown credit default status respond differently from the rest. |
| `pdays = 999` | Treated as a placeholder, not as 999 days. Set to missing, with a new column `previously_contacted`. |
| Call duration | Kept, but treated as an outcome of the call. The dataset documentation says it is not known before a call is made. |
| Column names | Renamed to readable names, with the mapping recorded. |
| Campaign year | The data has no year column. The year is inferred from the row order (the file is in date order and the month falls back from December to March twice), and cross-checked against a second, independent method. |

## Key findings

The largest difference in the data is the year. The yes rate was 4.8% in 2008, 19.5% in 2009 and 52.1% in 2010, so the overall 11.3% blends three very different years. Several patterns that look clear across all years change or disappear when each year is examined on its own. The ten findings below are checked within each year wherever the year could change the conclusion.

| # | Business question | Main answer |
|---|---|---|
| 1 | How many customers subscribed, and how many calls did it take? | 4,639 of 41,176 customers (11.3%) subscribed. Calls per subscription fell from 57.9 in 2008 to 10.9 in 2009 and 3.7 in 2010. |
| 2 | Which age groups have the highest yes rate? | The oldest and youngest customers responded best overall, but the pattern appears clearly only in 2009. |
| 3 | Which jobs and education levels have the highest yes rate? | Differences appear mainly in 2009. Students and retired customers responded best, and blue-collar and services customers worst. |
| 4 | Is a customer's financial profile linked to saying yes? | Housing and personal loans make little difference. A missing credit default record goes with a lower yes rate, mostly because those customers were contacted in 2008. |
| 5 | Do contact method, month and weekday change the yes rate? | Cellular beat telephone in every year, by 1.4 to 2.0 times, not the 2.8 times shown overall. Monthly differences are mostly differences between years. The weekday matters little. |
| 6 | Where does extra calling stop paying off? | The first three calls produced 88.0% of subscriptions from 73.5% of calls. A limit of 3 calls per customer would have saved 26.5% of calls at the cost of 12.0% of subscriptions. |
| 7 | Do customers from an earlier campaign respond differently? | An earlier success subscribed at 3.0 times the rate of never-contacted customers in 2009 and 1.7 times in 2010. An earlier failure subscribed less than a first contact in every year. |
| 8 | How do call lengths differ between customers who subscribed and those who did not? | The median last call lasted 449 seconds for subscribers and 164 seconds for the others. This describes what happened and is not a way to choose customers. |
| 9 | Does the economic climate change the yes rate? | The economic indicators identify the year, so their effect cannot be separated from everything else that changed. No causal claim is made. |
| 10 | Which combinations of customer and campaign features do best and worst? | Customers with an earlier success, contacted by cellular, are the strongest segments (2.9% of customers, 16.6% of subscriptions). Earlier failures by cellular and never-contacted customers by telephone, aged 25 to 54, are the weakest (39.9% of customers, 21.5% of subscriptions). |

The full results, with every table, are in [`docs/findings.md`](docs/findings.md).

## What this means for the bank

- A call list built from what is known before dialling would start with customers who subscribed in an earlier campaign, by cellular where possible, and place earlier failures and never-contacted telephone customers aged 25 to 54 last.
- A limit of three to five calls per customer would have saved calls at below-average yield in every year. Where the right limit lies depends on what a call costs and what a deposit is worth, and the data contains neither.
- A result from one year should not be used as a benchmark for another.
- The data cannot show whether acting on any of this would raise subscriptions.

## What the data cannot show

- **Causes.** All findings are associations. The bank chose whom to call, when and by which channel.
- **The reason for the differences between years.** The economy, whom the bank called and how the campaign was run all changed together.
- **The year itself.** It is inferred from the row order and is not recorded.
- **Individual customers.** There is no customer ID, so one person may appear more than once.
- **Costs and values.** There are no call costs or deposit amounts, so no break-even point can be calculated.

## Repository structure

    bank-marketing-analysis/
    ├── data/
    │   └── README.md                         source, citation, how to download
    ├── docs/
    │   ├── decision-log.md                   every data decision, with its reasoning and limits
    │   └── findings.md                       the ten business questions, in plain language
    ├── notebooks/
    │   ├── 01_load_raw.ipynb                 load the raw data unchanged
    │   ├── 02_profile_raw.ipynb              profile the raw data
    │   ├── 03_build_clean.ipynb              apply the decisions, save the clean data
    │   ├── 04_profile_clean.ipynb            validate the clean data against the raw data
    │   └── analysis/
    │       ├── q01_overall_result_and_calling_effort.ipynb
    │       ├── q02_age_and_life_stage.ipynb
    │       ├── q03_job_and_education.ipynb
    │       ├── q04_financial_profile.ipynb
    │       ├── q05_contact_channel_and_calendar.ipynb
    │       ├── q06_repeated_contacts.ipynb
    │       ├── q07_previous_campaign.ipynb
    │       ├── q08_call_duration.ipynb
    │       ├── q09_economic_context.ipynb
    │       └── q10_best_and_worst_segments.ipynb
    ├── .gitignore
    └── README.md

## How to reproduce

1. Download `bank-additional.zip` from the UCI page above, and place `bank-additional-full.csv` in the `data/` folder.
2. Install the packages: `pip install pandas pyarrow jupyter`
3. Run the notebooks in `notebooks/` in numbered order. `03_build_clean.ipynb` saves `data/bank_marketing_clean.parquet`, which the analysis notebooks read.
4. Run the notebooks in `notebooks/analysis/` in any order.

## Tools

Python, pandas, Jupyter (VS Code), Parquet, Git and GitHub.

## Author

Michael Onojah. GitHub: [HonourJAH](https://github.com/HonourJAH). LinkedIn: [linkedin.com/in/friday-onojah-9a5698219](https://www.linkedin.com/in/friday-onojah-9a5698219).

## Citation

Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306
