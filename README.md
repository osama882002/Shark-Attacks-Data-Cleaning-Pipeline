# Attacks Profiling & Cleaning Pipeline

Professional data cleaning pipeline for the Sharks Attacks dataset using Python and Pandas.

## Project Structure

```text
shark_attacks_project/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── 01_shark_attacks_pipeline.ipynb
│
├── src/
│   ├── load.py
│   ├── clean.py
│   ├── validate.py
│   └── analyze.py
│
├── output/
├── logs/
│   └── pipeline.log
│
├── requirements.txt
├── .gitignore
└── README.md

# Pipeline Stages

1- Load
2- Shape
3- Column Names
4- Types
5- Nulls
6- Invalid Values
7- Validate

# Features

* Reusable clean_*() functions
* Pandas .pipe() workflow
* Logging with logging
* Dataset validation using assert
* Missing values analysis
* Duplicate detection
* Metadata removal
* Clean dataset export

# Technologies Used

* Python
* Pandas
* NumPy
* PyArrow
* OpenPyXL


# Installation

```bash
pip install -r requirements.txt
```

# How to Run

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run the project
```bash
jupyter notebook
```

# Output
* Cleaned dataset
* Validation logs
* Profiling results
* Reproducible cleaning pipeline
```bash
data/processed/cleaned_attacks.csv
```