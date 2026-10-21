# Review Complexity and Critic Polarization on Rotten Tomatoes

**DS 4002 — Project 2**
**Team:** Shawn Chen, Arya Rajesh, Zichen Luo, Camila Janada

## Contents of This Repository


The repository is organized into four folders:

- **SCRIPTS/** holds the Google Colab notebook that runs the full analysis: feature creation, exploratory data analysis, model development and model testing.
- **DATA/** holds the cleaned dataset and directions to acquire the original dataset
- **OUTPUT/** holds every figure and results table produced by the notebook.
- **REFERENCES/** holds the sources cited in the project.

**Main finding:** 

## Section 1: Software and Platform

**Software:** Python 3, run in [Google Colab](https://colab.research.google.com/) (free, browser-based).

**Packages:**

| Package | Used for | Install needed in Colab? |
|---|---|---|


**Platform:** 

## Section 2: Map of Documentation

```
DS-4002-Projects/
├── README.md                              # This file: orientation to the repository
├── LICENSE.md                             # MIT License
│
├── SCRIPTS/
│   └── ds_4002_project_2.ipynb            # Full analysis notebook, run top to bottom:
│                                          #   1. Upload cleaned data (Influenza_Data_25-26.csv, Influenza_Data_21-25.csv)
│                                          #   2. Create variables
│                                          #   3. Exploratory data analysis and plots
│                                          #   4. Model development (regression, diagnostics)
│                                          #   5. Model testing (held-out data vs. baseline)
│
├── DATA/
│   ├── README.md                          # Explanation to acquire the original dataset
│   ├── Influenza_Data_25-26.csv           # Cleaned data for years 2025-2026
│   └── Influenza_Data_21-25csv            # Cleaned data for years 2021-2025
├── OUTPUT/
│   ├── 
│   └──                                    # 
│
└── REFERENCES/
    └── README.md                          # Sources cited in the project
```

## Section 3: Instructions for Reproducing Results


### Step 1: Get the data

### Step 2: Open the notebook in Google Colab
1. Go to [colab.research.google.com](https://colab.research.google.com/) and sign in with a Google account.
2. 

### Step 3: Run the notebook
1. Click **Runtime → Run all**.
2. The first code cell will pause and show a **Choose Files** button. Click it and select the `xxxx` you downloaded in Step 1. The notebook continues once the upload finishes; a large file can take a minute or two to upload.
3. Let the remaining cells run in order. Do not skip cells or run them out of order, because the model testing cell reuses the model fit in the model development cell.

### Step 4: Check your results

| Result | Expected value |
|---|---|


### Notes on the methods


