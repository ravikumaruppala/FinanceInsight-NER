# FinanceInsight
FinanceInsight — an intelligent financial data pipeline that automates the collection, preprocessing, and organization of company reports, SEC filings, and financial news for analysis and model training.

Due to GitHub restrictions on uploading new file objects to public forks after Git LFS usage, the complete project (including dataset and trained models) is hosted externally.

Full Project Download:
👉 https://drive.google.com/drive/folders/1g4w1i5UF1xcNftBm19ayQYnxlyn6W-rt?usp=drive_link

🔁 How to run the project

Download the project from the Drive link above.

Extract the contents.

Copy the folders into this repository as follows:

data/
models/


Run the preprocessing, training, and evaluation scripts as described in this repository.

This ensures full reproducibility while complying with GitHub’s repository size restrictions.




## Features
- Automated data collection (PDF/HTML)
- Organized raw & processed folders
- Simple preprocessing pipeline skeleton
- Ready for NLP/ML experiments

## Quickstart (Windows PowerShell)
```powershell
# create a venv and activate
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# install deps
pip install -r requirements.txt

# run collector
python scripts\data_collector.py --sources data/data_sources.csv --out data/raw

