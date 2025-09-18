# Polio in the United States: Socioeconomic Patterns and the Effects of the Salk and Sabin Vaccines (1928–1970)

This repository contains analysis code and supporting materials for the paper:

**Polio in the United States: Socioeconomic Patterns and the Effects of the Salk and Sabin Vaccines (1928–1970)**

---

## Project Overview
This project explores patterns of polio incidence in the United States between 1928–1970, with a focus on:
- Socioeconomic differences in disease burden
- The introduction of the Salk (1954) and Sabin (1961) vaccines
- Long-term effects of vaccination programs on incidence

---

## Repository Structure
- `paper/` – Final paper (PDF)
- `analysis/` - Markdown containing the analysis and plotting code in R 
- `data/` – Raw data (Tycho and FRED) and derived CSVs 
- `results/` – Key figures generated for the paper  

---

## Data Availability
The original Tycho data is not included in this repository.  
To run the analyses, please refer to:  
- [Tycho Project Data](https://www.tycho.pitt.edu/) (historical infectious disease incidence)  

The original economic data, as accessed and downloaded for this project (including our specific filters) is included in `data/raw/fred_income`. 
Further US economic data can be accessed at:
- [Per Capita Personal Income by State, Annual](https://fred.stlouisfed.org/release/tables?rid=110&eid=257197#snid=257202)

---

## How to Run
1. Clone this repo  
   ```bash
   git clone https://github.com/USERNAME/polio_us_1928_1970.git
   cd polio_us_1928_1970
