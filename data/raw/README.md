# Data Directory

This project uses **Project Tycho Level 1 data** on U.S. disease incidence.

- Source: [Project Tycho](https://www.tycho.pitt.edu/)
- File needed: `Project_Tycho_Level1.csv`  
- Expected location: `data/raw/Project_Tycho_Level1.csv`

⚠️ Due to file size restrictions, the raw data is **not included** in this repository.  
Please download it directly from Project Tycho and place it in the `data/raw/` directory.

This project also uses FRED (Federal Reserve Bank of St. Louis) data on income statistics in the United States. 

- Source: [Per Capita Personal Income by State, Annual](https://fred.stlouisfed.org/release/tables?rid=110&eid=257197#snid=257202)
- File: `fred_income.csv`

The processed/filtered datasets in `data/derived_CSVs/` are generated from the raw data and included here for reproducibility.
