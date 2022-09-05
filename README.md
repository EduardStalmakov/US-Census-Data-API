# Census API Data- Annual Business Survey 2019
## Table of Contents
* [Introduction](#Introduction)
* [Questions](#Questions)
* [Get the Data](# How to get the data)
* [Visuals](#Visuals)



# Introduction
This project uses data gathered from the [U.S. Census Bureau’s Annual Business Survey](https://www.census.gov/data/developers/data-sets/abs.2019.html), which provides information on both economic and demographic characteristics for businesses and business owners. Survey responses are gathered into four census datasets: Company Summary, Characteristics of Businesses, Characteristics of Business Owners, and Technology Characteristics of Business. We used data only from the Characteristics of Businesses and Characteristics of Business Owners datasets. 

[View our Presentation](https://docs.google.com/presentation/d/1WutSR1Dwtx_6uWYGedaDQSpv1CQMOPqWjjURKrt36Jg/edit?usp=sharing)

[View our Project Report](https://docs.google.com/document/d/1ZHFal6RjUJfD8Rb6ciDHICtxff8mbLKkd7xuRR6WHIc/edit?usp=sharing)

# How to get the data

API Call to get the Characteristics of Business Owners data:

  "https://api.census.gov/data/2018/abscbo?get=NAICS2017,NAICS2017_LABEL,QDESC,QDESC_LABEL,OWNER_RACE,OWNER_RACE_LABEL,OWNER_SEX,OWNER_SEX_LABEL,OWNCHAR,OWNCHAR_LABEL,OWNPDEMP,OWNPDEMP_PCT&for=us:*"


API Call to get the Characteristics of Businesses data:

"https://api.census.gov/data/2018/abscb?get=NAICS2017,NAICS2017_LABEL,RACE_GROUP,RACE_GROUP_LABEL,SEX,SEX_LABEL,QDESC,QDESC_LABEL,BUSCHAR,BUSCHAR_LABEL,FIRMPDEMP,FIRMPDEMP_PCT,EMP,EMP_PCT,PAYANN,PAYANN_PCT,RCPPDEMP,RCPPDEMP_PCT&for=us:*"

# Software Utilized

Python 3.9.12 was used to analyze the data and create the visualization within a Jupyter Notebook

Imports included:
* pandas
* requests
* json
* matplotlib.plyplot
* seaborn


# Questions
1. How does firm payroll differ by educational attainment and race of the business owner?
2. Does educational attainment change the business structure?
3. What are the patterns of successful businesses and their owners? 
4. What is the educational background of American business owners, how does it vary between industries, and does this variation correlate with any variation in firm characteristics across industries?

# Visuals

## Question 1: How does firm payroll differ by educational attainment and race of the business owner?

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/Median_Salary_by_all_degrees.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/Race_education.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/payroll_education_race.png)

## Question 2: Does educational attainment change the business structure?

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/WorkerType.png)

## Question 3: What are the patterns of successful businesses and their owners? 

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/tarick-1.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/tarick-2.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/tarick-3.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/tarick4.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/tarick-5.png)

## Question 4: What is the educational background of American business owners, how does it vary between industries, and does this variation correlate with any variation in firm characteristics across industries?

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/dennis-1.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/dennis-2.png)

![Owner](https://github.com/EduardStalmakov/US-Census-Data-API/blob/main/dennis-3.png)

