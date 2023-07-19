# Data Cleaning Project: Glassdoor Data Science Job Posts

![Glassdoor Logo](glassdoor_logo.png)

This repository contains a data cleaning project using pandas and numpy in a Jupyter Notebook. The project focuses on cleaning and preprocessing data scraped from Glassdoor's job posts related to Data Science positions.

## Description

The goal of this project is to demonstrate how to clean and preprocess scraped data from job posts on Glassdoor. The dataset (`Uncleaned_DS_jobs.csv`) contains information such as job titles, company names, locations, salaries, and job descriptions for various Data Science positions.

The Jupyter Notebook (`glassdoor_job_posts.ipynb`) provides a step-by-step guide to data cleaning using pandas and numpy. It covers the following data cleaning tasks:

1. Data type conversions: Convert data types of certain columns to appropriate formats, ensuring consistency and efficiency in calculations and analyses.

2. Text cleaning: Perform text cleaning techniques like removing special characters, converting text to lowercase, and handling text normalization to standardize the data.

3. Salary data cleaning: Standardize salary information and convert it to a numeric format for further analysis.

4. Data validation: Validate data integrity and correctness to ensure the accuracy of the dataset.

5. Data export: Save the cleaned dataset as `clean_DS_jobs.csv` for future analysis and visualization.

## File Structure

```
├── glassdoor_job_posts.ipynb    # Jupyter Notebook containing the data cleaning project
└── datasets
    ├── Uncleaned_DS_jobs.csv    # Original dataset scraped from Glassdoor
    └── clean_DS_jobs.csv        # Cleaned dataset after data cleaning
```

## Requirements

To run the Jupyter Notebook and perform the data cleaning tasks, you'll need the following Python libraries:

- pandas
- numpy
- Jupyter Notebook

You can install the required libraries using the following command:

```bash
pip install pandas numpy jupyter
```

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your_username/glassdoor-data-cleaning.git
cd glassdoor-data-cleaning
```

2. Open the Jupyter Notebook (`glassdoor_job_posts.ipynb`) using Jupyter Notebook or Jupyter Lab.

3. Follow the instructions in the Notebook to execute each data cleaning task.

4. After cleaning the data, the cleaned dataset will be saved as `clean_DS_jobs.csv` in the `datasets` directory.

---
