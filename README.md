# Support Cases Analysis – GlobalVision Challenge

This project analyzes support case and account data to generate business
insights using Python, SQL, and data visualization techniques.

The analysis is organized in a Jupyter Notebook and covers:
- Exploratory Data Analysis (EDA)
- SQL-based metrics and joins
- Data visualization
- Business insights and recommendations

---

## Project Structure

- `globalvision_challenge.ipynb` — Main notebook containing the full analysis
- `accounts_anonymized.json` — Accounts dataset
- `support_anonymized.json` — Support cases dataset

---

## Requirements

This project was developed using Python and relies on the following libraries:

- **pandas** – data manipulation and analysis  
- **sqlite3** – SQL queries and joins using an in-memory SQLite database  
- **matplotlib** – data visualization  
- **seaborn** – statistical data visualization  
- **jupyter** – notebook environment

---

## Installation

It is recommended to use a virtual environment.

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

`sqlite3` is included in the Python standard library and does not require
separate installation.

## How to Run the Project

1. Ensure the JSON files are in the same directory as the notebook.
2. Start Jupyter Notebook:
```bash
jupyter notebook
```
3. Open `globalvision_challenge.ipynb`.
4. Run the notebook cells from top to bottom.

All SQL queries are executed using an in-memory SQLite database created within
the notebook, so no external database setup is required.

## Notes

* SQL was intentionally used for joins and metric derivation to demonstrate
relational querying capabilities.
* Visualizations were created using Matplotlib and Seaborn.
* Business insights and recommendations are summarized in the final section of
the notebook.

## Author

Miguel Gomes Fecchio