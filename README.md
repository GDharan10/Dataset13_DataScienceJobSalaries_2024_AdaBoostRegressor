# Data Science Job Salaries 2024

## Overview
This repository contains the code and documentation for analyzing the "Data Science Job Salaries 2024" dataset using Python and statistical methods. The dataset consists of various variables related to data science job positions and salaries, including work year, experience level, employment type, job title, salary, salary currency, salary in USD, employee residence, remote work ratio, company location, and company size. Our goal is to explore, analyze, and draw insights from this data.

## Description
The "Data Science Job Salaries 2024" dataset contains information about salaries and job details in the data science field. Each entry represents a unique job position and includes the following columns:

- **work_year** : The year the salary was paid.
- **experience_level** : The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX  Executive-level / Director
- **employment_type** : The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance
- **job_title** : The role worked in during the year.
- **salary** : The total gross salary amount paid.
- **salary_currency** : The currency of the salary paid as an ISO 4217 currency code.
- **salary_in_usd** : The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).
- **employee_residence** : Employee's primary country of residence in during the work year as an ISO 3166 country code.
- **remote_ratio** : The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)
- **company_location** : The country of the employer's main office or contracting branch as an ISO 3166 country code.
- **company_size** : The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)

## Repository Structure
- `salaries.csv`: Contains the raw data files used in the analysis.
- `Data_science_job_salaries_2024.ipynb`: Jupyter notebooks containing the code for data exploration, preprocessing, analysis, and visualization.
- `results/`: Output files, visualizations, and summaries generated during the analysis.
- `README.md`: This file, providing an overview of the project.

## Dependencies
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Statsmodels
- sklearn
- Jupyter Notebook

## Getting Started
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Explore the Jupyter notebook `Data_science_job_salaries_2024.ipynb` to understand the analysis process.
5. Run the notebook or scripts to reproduce the analysis and results.
6. Refer to the documentation and comments within the code for more detailed explanations.

## Contribution Guidelines
Contributions to this project are welcome! If you find any issues, have suggestions for improvements, or want to add new features, please open an issue or submit a pull request following the guidelines outlined in `CONTRIBUTING.md`.



