# Augmenting LinkedIn Dataset with Glassdoor Information through Web Scraping

## Objective

The objective of this project is to integrate two datasets of job postings from job search portals, one corresponding to the previous month from LinkedIn and another updated this week from Glassdoor. By combining these datasets, we aim to gain insights into the current state of the labor market, identify the most sought-after jobs by companies, the top cities with the highest number of job openings, and the essential skills required.

## Hypothesis

By integrating LinkedIn job postings data from the previous month with the latest updates from Glassdoor, we aim to identify the most sought-after jobs by companies, the top cities with the highest number of job openings, and the essential skills required. This analysis will help students focus their job search after completing the bootcamp.

## Project Methodology

### Defining the Topic
The main goal was to obtain a general overview of the most in-demand data roles on job search portals and to identify the most sought-after skills. The focus was on how the insights gained could be highly useful in guiding our job search post-bootcamp.

### Data Acquisition
Initially, I attempted to obtain data from the Indeed Jobs API but encountered limitations on requests. Consequently, I shifted to web scraping data from the Glassdoor website. Despite similar limitations on requests, I managed to gather significant information about data-related job postings.

### Data Cleaning and Integration
After collecting data from Glassdoor, I conducted a thorough cleaning process, particularly focusing on standardizing company names and job titles. Then, I merged this data with the LinkedIn dataset, filtering and standardizing columns, and removing null values.

### Exploratory Analysis
The exploratory analysis revealed several insights:

#### Most Common Words in Job Titles
A word cloud representation showcased prevalent terms like "data analyst," "data engineer," and "data scientist," aiding in identifying job trends and market demands.

#### Top 10 Most Published Job Titles
A bar chart illustrated the top 10 most commonly published job titles, providing insights into the most in-demand roles in the analytics field.

#### Seniority
A summary displayed the distribution of job responsibilities among different experience levels, assisting in career goal adjustment and skill development.

#### Top Skills
An analysis highlighted the top skills needed in the analytics field, aiding in focusing learning efforts on acquiring relevant skills for popular job roles.

#### Top City
A chart showed the concentration of job opportunities in different cities, facilitating informed decisions about job search or potential relocation plans.

#### Job Modality
A visualization confirmed the prevalence of hybrid and remote work modalities, indicating a growing trend towards flexible work arrangements.

#### Top Skills (Again)
Another chart emphasized the frequency of essential skills in job postings, enabling strategic focus on developing and showcasing sought-after abilities.

## Conclusion

By integrating LinkedIn and Glassdoor datasets and conducting exploratory analysis, this project provides valuable insights into the current job market landscape, helping job seekers make informed decisions and focus their efforts effectively.
