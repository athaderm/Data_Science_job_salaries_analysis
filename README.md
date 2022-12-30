<h1 align="center">Data Science job salaries analysis (Python)</h1>

<br>

<h2 align="center">Project overview</h2>

- The Dataset contains Data Science job salaries from 2020 to 2022 and it was found in Kaggle
- Jupyter Notebook was used for this project
- The libraries used were pandas, numpy, seaborn, matplotlib, plotly and country_converter
- The project had 3 stages:
  - Data cleaning (it was cheacked for null values, duplicates and outliers).
  - Data modification (some columns were renamed)
  - Data exploration (results and visualizations)

<br>

<h2 align="center">Objectives</h2>

The primary goal is to provide an estimation on Data Science jobs salaries.

Some questions that were asked:
- What is the distribution of salaries?
- What is the relationship between salary and experience?
- What is the distribution of remote ratio?
- Does on site work pays better than remote work?
- Is it better to work as a Data analyst or as a Data Engineer?
- What is the mean salary of data related jobs in every country?

<br>

<h2 align="center">Visualizations and Results</h2>

<br>

<p align="center"><img src="/images/salary_dist.png" width="70%" height="70%" /></p>

The analysis have shown that the highest salary is 600.000$ USD and the lowest is 2.324$ USD. However the dataset contained some outliers. After their removal the highest salary changed to 297.500$ USD and the lowest remained the same, at 2.324$ USD.

<br><br>

<p align="center"><img src="/images/mean_sal_exp_level.png" width="70%" height="70%" /></p>

The salary development appears to be associated with the experience level. The higher the experience level the higher the mean salary.

<br><br>

<p align="center"><img src="/images/remote_dist.png" width="70%" height="70%" /></p>

Most people are working remotely, followed by people working on site and lastly people working hybrid:


<br>

<div align="center">
  
  | Status  | Count |
  |---------|:-----:|
  | Remote  |  781  |
  | On Site |  412  |
  | Hybrid  |  139  |
  
</div>

<br><br>

<p align="center"><img src="/images/mean_salary_remote.png" width="60%" height="60%" /></p>

It was found that remote ratio does not affect the salaries much, except hybrid ones. Remote and on site jobs have almost the same distribution in salaries. They have a greater difference compared to the hybrid ones.

<br><br>

<p align="center"><img src="/images/data_analyst_eng.png" width="70%" height="70%" /></p>

It was observed that Data Engineers have better salary development compared to Data Analysts.

<br><br>

<p align="center"><img src="/images/world_map_sal.png" width="70%" height="70%" /></p>

The country with the highest mean salary is Puerto Rico, followed by Russia and United States:

<div align="center">
  
  | Country       | Mean Salary ($USD) |
  |:-------------:|:------------------:|
  | Puerto Rico   |       167.500      |
  | Russia        |       157.500      |
  | United States |       142.938      |
  
</div>

 
