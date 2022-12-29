# Data Science job salaries analysis (Python)
### Project overview

- The Dataset contains Data Science job salaries from 2020 to 2022 and it was found via Kaggle
- Jupiter Notebook was used for this project
- The libraries used were pandas, numpy, seaborn, matplotlib, plotly and country_converter
- The project had 3 stages:
  - Data cleaning(it was cheacked for nulls,duplicates and outliers),
  - Data modification(some columns was renamed) and 
  - Data exploration(results and visualizations)

### Objectives

The primary goal is to provide an overview/analysis on what is being paid in Data Science jobs.

Some questions that was asked:
- What is the distribution of salaries?
- What is the relationship between salary and experience?
- What is the distribution of remote ratio?
- Does on site work pays better than remote work?
- Is it better to work as a Data analyst or as a Data Engineer?
- What is the mean salary of data related jobs in every country?

### Results/Conclutions and Visualizations

![Salary Distribution](/images/salary_dist.png?raw=true)

It was found that the highest salary of the dataset is 600000 usd the lowest is 2324 usd and the mean salary is 123374,however the dataset contained some outliers and  after their removal the highest salary changed to 297500 usd the lowest remained the same at 2324 usd and the mean salary changed to 120428 usd.

![Mean salary per experience](/images/mean_sal_exp_level.png?raw=true)

The salary development appears to be associated with the experience level.The higher the experience level the higher the mean salary.

![Remote ratio Distribution](/images/remote_dist.png?raw=true)

Most people are working remote,followed by people working on site and people working hybrid,precisely:
-Remote:       781
-Not remote:   412
-Hybrid:       139

![Mean salary per remote ratio](/images/mean_salary_remote.png?raw=true)

It was found that remote ratio does not affect the salaries.Remote and on site jobs have the same distribution in salaries but slightly better salaries compared to the  hybrid ones.

![Data analyst vs Data Engineers](/images/data_analyst_eng.png?raw=true)

It was observed that Data engineers have better salary development compared to Data analysts.

![World Map](/images/world_map_sal.png?raw=true)

The country with the highest mean salary is Puerto Rico,followed by Russia and United States,more precisely:
-Puerto rico:    167500
-Russia:         157500
-United states:  142938

 
