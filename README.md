# The 2019 Stack Overflow Developer Survey analysis


### The 2019 Stack Overflow Developer Survey analysis is the Data Analyst Capstone Project of the IBM Data Analyst Professional Certificate


# Project Description

I have recently been hired as a Data Analyst by a global IT and business consulting services firm that is known for their expertise in IT solutions and their team of highly experienced IT consultants.  In order to keep pace with changing technologies and remain competitive, my organization regularly analyzes data to help identify future skill requirements. 

As a Data Analyst, I am assisting with this initiative and have been tasked with collecting data from various sources and identifying trends for this year's report on emerging skills. 

My first task was to collect the top programming skills that are most in demand from various sources including:

- Job postings

- Training portals

- Surveys

Once i have collected enough data, i begin analyzing the data and identify insights and trends that may include the following:

- What are the top programming languages in demand?

- What are the top database skills in demand?

- What are the popular IDEs?

Then i begin by scraping internet web sites and accessing APIs to collect data in various formats like .csv files, excel sheets, and databases.   
 
 

Once this was completed, i made that data ready for analysis using data wrangling techniques. 
 


once the data was ready i applied statistical techniques to analyze the data.  Then i collected all this information together by using  IBM Cognos Analytics to create my dashboard. And finally, showed off my storytelling skills by sharing my findings in a presentation.

# Outline 

|       SL. NO        |                                                                                                 Outline                                                                                                  |
| :-----------------: |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|          1          |                                                                                            Executive Summary                                                                                             |
|          2          |                                                                                               Introduction                                                                                               |
|          3          |                                                                                               Methodology                                                                                                |
|          4          |                                                                                                 Results                                                                                                  |
|          5          |                                                                                                Discussion                                                                                                |
|          6          |                                                                                                Conclusion                                                                                                |
|          7          |                                                                                                 Appendix                                                                                                 |

# Executive Summary

This Project will give you an overview of :

1. Trends in programming languages and databases

2. Demographics survey

3. Technological gap in countries

4. Gender gap in jobs

# Introduction

- This presentation has been created for stakeholders and business decision makers within the global IT and business consulting services firm.


- The presentation will help identify future skill requirements in the global IT sector necessary for the firm to keep pace with changing technologies and remain competitive.


- Recommendations will be stated based on the analysis.

# Objectives

## Background

Analyzing the trends in software development.

## Purpose

Identify skill requirements for future.

## Question for Analysis

- What are the top programming languages in demand?

- What are the top database skills in demand?

- What are the popular IDEs?

## Audience

Human Resource and IT Head.

# Hardware and Software Requirments

## Hardware

In this Project We are going to use IBM Cloud Pack for Data and its various Web services, so a RAM of 8 GB and decent Internet Connection is required only. All the hardware requirments will be covered by IBM Cloud Pack for Data.

## Software

We are going to use IBM Watson Studio for this project.

In case of local machine We are going to use the following softwares in this project :

Programming Language : [Python](https://www.python.org/)

IDE : [Jupyter Notebook](https://jupyter.org/)

Packages : [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html), [Numpy](https://numpy.org/), [Scipy](https://scipy.org/), [Scikit-learn](https://scikit-learn.org/stable/), [Matplotlib](https://matplotlib.org/), [BeautifulSoop](https://pypi.org/project/beautifulsoup4/).

# Methodology

## 1. Collecting Jobs data Using API and Web Scraping

### The Data was collected from:

Stack Overflow Developer 2019 Survey

GitHub Job Postings

Programming Languages Annual Salary

To see the code and step by step process of Collecting by API [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week1-2__Collecting_Jobs_data_Using_API-Questions.ipynb)

To see the code and step by step process of Collecting by Web Scraping [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week1-4__Collecting%20Data%20Using%20Web%20Scraping.ipynb)


The Data Sets:

[m5_survey_data_demographics.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_demographics.csv?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDA0321ENSkillsNetwork21426264-2022-01-01) which contains information about the IT professionals.

[m5_survey_data_technologies_normalised.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_technologies_normalised.csv?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDA0321ENSkillsNetwork21426264-2022-01-01) which contains information about trending technologies and programming languages.  


## 2. Data Exploration

To see the code and step by step process of Data Exploration [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week1-5__Explore%20the%20Data%20Set.ipynb)

## 3. Data Wrangling
 
To see the code and step by step process of Data Wrangling [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week2-1__Data%20wrangling.ipynb)

## 4. Exploratory Data Analysis

To see the code and step by step process of Exploratory Data Analysis [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week3-1__Exploratory%20data%20analysis.ipynb)

## 5. Data Visualization

To see the code and step by step process of Exploratory Data Visualization [click here](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/week4-1__DataVisualization-lab.ipynb)

# Results


## Programming Language Trends 

![Programming Language Trends.jpg](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Programming%20Language%20Trends.jpg)


## Programming Language Trends - Findings & Implications

### Findings 

1. JavaScript and HTML/CSS continue to be the top two most popular programming languages for this year and next.

2. Python and TypeScript have gained more interest for next year.

3. Whereas interest in SQL and Bash/Shell/PowerShell has decreased.

### Implications

1. Continue to employ a similar number of people skilled in JavaScript and HTML/CSS.

2. Employ more people skilled in Python and TypeScript.

3. Employ less people skilled in SQL and Bash/Shell/PowerShell.


## Database Trends 

![Database Trends.jpg](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Database%20Trends.jpg)

## Database Trends - Findings & Implications

### Findings

1. Interest in MySQL, Microsoft SQL Server and SQLite has decreased for next year.

2. Interest in PostgreSQL and MongoDB have increased compared to the current year.

3. There is gained interest in Redis and Elasticsearch for next year.

### Implications

1. Employ less people skilled in MySQL, Microsoft SQL Server and SQLite.

2. Employ more people skilled in PostgreSQL and MongoDB.

3. Employ more people skilled in Redis and Elasticsearch.

## IBM Cognos Dashboard Link

[Dashboard](https://jp-tok.dataplatform.cloud.ibm.com/dashboards/7c95e4bd-4a86-4aa6-8e46-546a3749d006/view/553fc12300b300e714b5eee407992f067b37740fb7bb815086d77b490a622097f33b1699c82a4d59da400460fbe811599a)

### Current Technology usage Dasboard

![Current Technology usage Dasboard](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Current%20Technology%20usage%20Dasboard.jpg)

### Future Technology trend Dasboard

![Future Technology trend Dasboard](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Future%20Technology%20trend%20Dasboard.jpg)

### Demographics Dashboard

![Demographics Dashboard](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Demographics%20Dashboard.jpg)

# Discussion

Technology Trends now and future

Training and Re-skilling workers

Females participation in Technology field

Bridge divide of technology gaps in developing countries

Eliminate age and education discrimination in employment

# Ovearall Findings and Implications

## Findings

1. Programming Languages- TypeScript is gaining significant interest and Python continues to grow as well.

2. Databases- Redis, Elasticsearch, PostgreSQL and MongoDB are gaining more interest.

3. Platforms- Interest Slack and Windows is dropping significantly.

4. WebFrames- Vue.js is gaining substantial interest and React.js continues to grow as well.

## Implications

1. Continue to staff enough JavaScript and HTML/CSS but employ more people skilled in TypeScript and Python.

2. Employ more people skilled in Redis, Elasticsearch, PostgreSQL and MongoDB.

3. Continue to staff enough ASP.NET but employ more people skilled in Vue.js and React.js.

4. Continue to staff enough Linux, employ more peopleskilled in Docker, AWS and Android, butmake reductionsto Slack and Windows.


# Conclusion

1. Carve out budget in order to hire additional staff with skills needed to fill any gaps.

2. Set aside budget or put a program in place to upskill those already employed.

3. Make adjustmentsin staff for those skills no longer in demand.

# Appendix

### GITHUB JOB POSTINGS

![GITHUB JOB POSTINGS.jpg](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/GITHUB%20JOB%20POSTINGS.jpg)

### POPULAR LANGUAGES

![POPULAR LANGUAGES.jpg](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/POPULAR%20LANGUAGES.jpg)

### Box plot of Age and Pie chart of the top 5 databases that respondents wish to learn next year

![Box and Pie chart](https://github.com/sumitsalve98/IBM-Data-Analyst-Capstone-Project/blob/master/IBM%20Data%20Analyst%20Capstone%20Project/screenshots/Plot%20a%20box%20plot%20of%20Age%20and%20Pie%20chart%20of%20the%20top%205%20databases%20that%20respondents%20wish%20to%20learn%20next%20year.jpg)


# Authors

- [@sumitsalve](https://github.com/sumitsalve98)


# 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://sumitsalve98.github.io/MyPortfolio/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumit-salve-72b818217/)









