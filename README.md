# Home Advantage in Professional Football  
*Research Data Management Project – TU Wien (2025)*

This project analyses **home versus away performance** in two professional football leagues:
- **English Premier League**
- **Polish Ekstraklasa**

The goal is to evaluate whether a **home advantage** exists and how strongly it differs between leagues.



## 📁 Project Structure


2025_Football_Home_Advantage/
├─ data/
│   ├─ raw/                # Original Excel datasets (input)
│   └─ processed/          # Cleaned & aggregated datasets (output)
├─ notebooks/
│   └─ home_advantage_study.ipynb
├─ reports/
│   ├─ figures/            # Saved plots
│   └─ dmp/                # Data Management Plan
├─ src/                    # Optional Python scripts
└─ README.md


## 🔍 Research Question

**Does playing at home increase the probability of winning in the Premier League and Ekstraklasa?  
If yes, how do these two leagues compare?**


## 📊 Analysis Overview

All analysis is performed in:

```

notebooks/home_advantage_study.ipynb

````

The notebook performs:

1. Loading and preprocessing of raw match data  
2. Creation of binary outcome variables (home win, away win, draw)  
3. Distribution analysis (overall & by league)  
4. Home advantage evaluation  
5. Export of processed tables to `data/processed/`  
6. Export of final figures to `reports/figures/`  

---

## 📈 Output Files

### 📂 Processed Data  

Stored in: `data/processed/`

- `all_matches.csv`  
- `overall_distribution.csv`  
- `league_results_counts.csv`  
- `league_results_percent.csv`  
- `summary_all_matches.csv`  
- `summary_by_league.csv`  

### 🖼 Figures  

Stored in: `reports/figures/`

- `overall_result_distribution.png`  
- `home_vs_away_win_rates.png`  

---

## 🚀 How to Run the Project

Make sure you have Python installed, then:

```bash
pip install pandas matplotlib
jupyter notebook
````

Open the notebook:

```
notebooks/home_advantage_study.ipynb
```

Run all cells.

---

## 🔧 Requirements

* Python 3.10+
* pandas
* matplotlib
* Jupyter Notebook

(Optional: create a virtual environment)

```bash
python -m venv .venv

# macOS / Linux:
source .venv/bin/activate

# Windows:
.venv\Scripts\activate
```

Then:

```bash
pip install pandas matplotlib jupyter
```

---

## 📄 License

* **Code:** MIT License (or another license you choose)
* **Data:** Use according to the terms of the original data source(s).

---

## 👤 Author

Bartosz Ciesielski
TU Wien – Research Data Management (2025)