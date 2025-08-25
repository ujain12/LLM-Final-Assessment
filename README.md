# Employee Email Sentiment — Codebase

**Main file:** `Employee_Email_Sentiment_Analysis.ipynb` (run this).

## How to run
1. Install requirements: `pip install -r requirements.txt`
2. Put your raw CSV at the path used in the notebook (`DATA_PATH`).
3. Open the notebook and run cells in order.

## Notes
- Expected columns: `from`, `date`, `body`. If different, rename in pandas before proceeding.
- Charts use matplotlib only. No external services are required.
- Outputs are written to `outputs/`.
