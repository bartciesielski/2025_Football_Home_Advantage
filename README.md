````md
# Home Advantage in Professional Football  
*Research Data Management Project – TU Wien (2025)*

This project investigates whether a **home advantage** exists in professional football by analysing match outcomes from:

- **English Premier League**
- **Polish Ekstraklasa**

The study evaluates how strongly home advantage appears in each league and compares the results.

---

## 📁 Project Structure

```text
2025_Football_Home_Advantage/
├─ data/
│   ├─ raw/                # Original dataset files (input)
│   └─ processed/          # Cleaned & aggregated datasets (output)
├─ notebooks/
│   └─ home_advantage_study.ipynb
├─ reports/
│   ├─ figures/            # Saved visual outputs
│   └─ dmp/                # Data Management Plan (PDF)
├─ fair_assessment/        # FAIR self-assessment results (PDF + link)
├─ src/                    # Optional Python scripts
└─ README.md
````

---

## 🔍 Research Question

**Does playing at home increase the likelihood of winning in the Premier League and Ekstraklasa?
If yes, does the magnitude of home advantage differ between leagues?**

---

## 📊 Analysis Overview

All analysis is contained in:

```
notebooks/home_advantage_study.ipynb
```

The notebook performs:

1. Loading and preprocessing raw match data
2. Creating binary outcome variables (home win, away win, draw)
3. Computing distribution of results (overall & per league)
4. Quantifying home advantage
5. Exporting processed datasets to `data/processed/`
6. Saving figures to `reports/figures/`

---

## 📂 Output Files

### Processed Data (stored in `data/processed/`)

* `all_matches.csv`
* `overall_distribution.csv`
* `league_results_counts.csv`
* `league_results_percent.csv`
* `summary_all_matches.csv`
* `summary_by_league.csv`

### Figures (stored in `reports/figures/`)

* `overall_result_distribution.png`
* `home_vs_away_win_rates.png`

---

## 🚀 How to Run the Project

Install dependencies:

```bash
pip install pandas matplotlib jupyter
```

Open the notebook:

```bash
jupyter notebook notebooks/home_advantage_study.ipynb
```

Run all cells to reproduce the analysis.

### Optional: Virtual environment

```bash
python -m venv .venv

# Windows:
.venv\Scripts\activate

# macOS/Linux:
source .venv/bin/activate

pip install pandas matplotlib jupyter
```

---

## 📄 Data Management Plan (DMP)

The complete FWF-compliant **Data Management Plan** for this project is stored in:

```
reports/dmp/
```

It describes:

* Dataset sources and structure
* Documentation and metadata strategy
* Data quality assurance
* Storage, backup, and access control
* Licensing and reuse
* FAIR considerations
* Long-term preservation

---

## 🧭 FAIR Assessment

A full FAIR self-assessment is included in:

```
fair_assessment/
```

This folder contains:

* A screenshot of the FAIR Assessment result
* A `.txt` file with the official FAIR assessment link


---

## 📘 Requirements

* Python 3.10+
* pandas
* matplotlib
* Jupyter Notebook

---

## 📄 License

* **Code:** MIT License (or another license of your choice)
* **Data:** Subject to the original providers' terms (Ekstraklasa & Premier League sources)

---

## 👤 Author

Bartosz Ciesielski
TU Wien — Research Data Management (2025)

```
```
