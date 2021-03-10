# Environmental_Engineer_Salary

## Table of Contents
1. [Installation](#Installation)
2. [Project Motivation](#Project_Motivation)
3. [File Descriptions](#File_Description)
4. [Data Cleaning](#Data_Cleaning)
5. [Results](#Results)
6. [Licensing, Authors, and Acknowledgements](#Licensing,_Authors,_and_Acknowledgements)

## Installation

Packages: Beautiful Soup, pandas, numpy, sklearn, matplotlib, seaborn, wordcloud. 
The code should run with no issues using Python versions 3.*.

## Project Motivation

In this project, I collected the job posting information for Environmental Engineer from Indeed. 
The business questions that I am trying to understand are:

1. Which companies have most job offerings?
2. Which city and state have most job opportunities?
3. Which sector has most job posting?
4. How much should be expected to make as an Environmental Engineer in US?
5. What are the keywords in the job summary?
6. Is there a correlation between location and salary?

## File Descriptions

`Indeed_scraper.ipyn` is the notebook for the webscrapper.
Use web scraper to scrape 1000 job postings from indeed.com. With each job, we got the following:
- Job title
- Company
- Location
- Salary
- Summary

`EnvironmentalEngineerJobAnalysis.ipyn` is the main notebook for this analysis.

## Data Cleaning
I cleaned the data that was scrapped from the Indeed.

1. Cleaned the location information and divided it into city and state.
2. Classified the job into different categories based on the industry type: Water, Remediation, Air, Compliance, Civil.
2. For Salary analysis, we will only keep the job infos with annual salary.

## Results
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the analysis.


For more information, check out my Medium post [here](https://drboli.medium.com/trying-to-find-environmental-engineer-jobs-here-are-the-insights-from-1000-job-postings-65d796b1ac01).

## Licensing, Authors, and Acknowledgements
For this analysis, I analyzed the data from Indeed.com on March 9th, 2021.
