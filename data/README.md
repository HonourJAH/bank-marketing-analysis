# Data

The raw data file is **not committed** to this repository (it is blocked in `.gitignore`). To reproduce the analysis, download it and place it in this folder.

## Source

- **Dataset:** Bank Marketing, UCI Machine Learning Repository
- **Page:** https://archive.ics.uci.edu/dataset/222/bank%2Bmarket
- **DOI:** https://doi.org/10.24432/C5K306
- **Licence:** Creative Commons Attribution 4.0 (CC BY 4.0)
- **Citation:** Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306
- **Paper:** S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, 2014. https://doi.org/10.1016/j.dss.2014.03.001

The data comes from phone marketing campaigns of a Portuguese bank selling term deposits.

## File used

`bank-additional-full.csv`, found inside `bank-additional.zip` at `bank-additional/bank-additional-full.csv`.

- 41,188 rows, 21 columns (20 inputs plus the target `y`)
- Semicolon-separated, text values in quotes
- Ordered by date, from May 2008 to November 2010
- The target column is `y`: did the customer subscribe to a term deposit (yes/no)

## How to reproduce

1. Download `bank-additional.zip` from the UCI page above.
2. Extract `bank-additional-full.csv` and place it in this `data/` folder.
3. Run the notebooks in `notebooks/` in numbered order.

## Notes from the dataset documentation (`bank-additional-names.txt`)

- `duration` (last call length in seconds) is not known before a call is made, and the call's outcome is known once it ends. The documentation says it should be discarded for a realistic predictive model.
- `pdays = 999` means the client was not previously contacted.
- `marital = divorced` means divorced or widowed.
- Missing values are coded as the text "unknown" and can be kept as a class, deleted or imputed.
- The economic indicators are national figures: `emp.var.rate` and `nr.employed` quarterly, `cons.price.idx` and `cons.conf.idx` monthly, `euribor3m` daily.
- Some attributes of the original study were left out for privacy reasons.

## Known characteristics of this file

These are findings from profiling, with the reasoning in `docs/decision-log.md`:

- No blank cells; missing information is the text "unknown" in six columns.
- `pdays = 999` also appears on 4,110 rows where the customer was contacted before, which the documented definition does not explain.
- The file has no customer ID and no year column.
