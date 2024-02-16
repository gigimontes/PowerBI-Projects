# Project #1: Analyst Data Survey 📊

## Project Overview
I analyzed data from a Questionnaire Survey results taken of those who are in the data analytics/data science field. 

## Data Source
I retrieved the data from AlexTheAnalyst Github's "Power-BI" respitory. To go to the respitory click here: [Power BI Respitory](https://github.com/AlexTheAnalyst/Power-BI)


## Tools Used In Project:
**Excel** 
  - Download the Excel spreadsheet here: [Power BI Repitory](https://github.com/AlexTheAnalyst/Power-BI)

**Power BI**
  - Download the Report here: [Analyst Data Survey](https://github.com/gigimontes/PowerBI-Projects/blob/main/Data%20Survey%20Project.pbix)  

## Data Cleaning/Preparation

**Split Column by Delimiter** 
 - For questions 2 and 7, Survey takers had an option to choose 'other' and type in a specific answer. This caused a lot of misspelled words, repetitive answers, outliers, etc. For this project, I split the column after the 'other' to then delete the new column where the typed-in answer was in. This made the data simpler to read and process.

**Average Salary**
  - For question 2 the answer choices are in ranges (ex. 0-40k, 41k-65k, 66k-85k, 86k-105k, 106k-125+k). Therefore, I had to Split the column, resulting in the start of a range in the first column and the second one in the second, replace the values to eliminate any text or symbols in the columns, and change the data type from Text to Numerical. Once completing these steps I was finally able to calculate the average salary.

## Exploratory Data Analysis
The questions that were asked in the Survey and were used to do my Analysis are:

  1. What is your age?
  2. What's your favorite Favorite Programming Language?
  3. How happy are you in your current position with the following? (Salary)
  4. How happy are you in your current position with the following? (Work/Life Balance)
  5. How happy are you with your Current Position with the following? (Learning New things)
  6. How difficult was it for you to break into Data?
  7. What Country do you live in? 

## Results

![image](https://github.com/gigimontes/PowerBI-Projects/assets/143570053/17d09171-9a9a-4448-94d7-d056e70c49cd)

  - There's 630 Survey submissions with the average age being 29 years old.
  - The work life balance satisfaction and the satisfaction with learning 
    new material are both 5 out 10, however, the salary satisfaction is     
    4.27. Survey takers are more happy with the work life balance and the 
    learning new material that comes with the role than their salary pay.
  - The programming language that was the majority favorite was Python     
    while the least was Java.
  - 43% of survey takers thought getting a job in the field was neither 
    easy nor difficult while 25% thought it was difficult and 21% thought 
    it was easy.
  - The average Data Scientist had the highest salary being 93,780 per year 
    while those individuals who were a student, still on the search for a 
    job in the field, and those who were none did with a salary of 26,580 
    per year.
  - Most Participants reside in the United States with 261 submissions and 'Other' countries with 224 submissions. There are 73 participants that reside in India, 
    40 in the United Kingdom, and 32 in Canada.



