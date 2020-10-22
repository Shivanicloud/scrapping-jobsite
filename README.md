# scrapping-jobsite

# Purpose of this code

I wrote this code for a project for the School of Management at the University of San Francisco. The purpose of the code was to be able to get a Dataset that captures different jobs posts from Indeed that can be analyzed to understand the job market demand, in terms of job titles, skills, industries and locations.

The code structure:-

Importing needed packages
Loading CSV files that are the inputs for the code, 
the files contain the job searches and keywords you are looking for in each job.

1. Phase 1 - Scraping Job links: This code will create a dataset of all the job searches with links for each job.

2. Phase 2 - Scraping the body of job posts: This code will pull the body text of each job in the created dataset.

3. Phase 3 - Text mining the body of job posts: This code will look for the desired keywords and min years of experience needed for each job.

4. Phase 4 - Classifying jobs: This code classifies the jobs into different categories: Job title, Business Function / Department, and city.

