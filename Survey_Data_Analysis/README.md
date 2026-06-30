# Survey Data Analysis Power BI Project

## Overview

This project analyses real survey data collected from approximately 630 data professionals through social media platforms. The dataset explores career information within the data industry, including job roles, salaries, programming language preferences, geographical distribution, and job satisfaction.

The raw survey data was transformed using Power Query Editor and analysed in Power BI through the creation of an interactive dashboard.

Credits for the dataset and project inspiration go to Alex The Analyst.


## Process

### Data Cleaning & Transformation

The raw survey dataset was prepared using Power Query:

* Removed unnecessary columns with no analytical value:
  - Browser
  - OS
  - City
  - Country reference fields

* Standardised categorical responses:
  - Simplified job roles, industries, countries, and programming language responses.
  - Responses entered under "Other" were grouped together by splitting text values using delimiters and removing unnecessary columns.

* Transformed salary data:
  - The yearly salary column originally contained salary ranges.
  - The salary range was split into:
    - Minimum salary
    - Maximum salary
    - Average salary (Calculated from Maximum and Minimum)
  - The minimum and maximum salary columns were removed, leaving the average salary for analysis.

* Checked and corrected data types before loading the dataset into Power BI.


## Dashboard Development

An interactive Power BI dashboard was created to analyse:


### Visualisations

* Cards:
 - Total survey participants
 - Average age of respondents

* Average Salary by Job Title 
  - Compared earning potential across different data roles.

* Favourite Programming Languages
  - Analysed programming language preferences among respondents.

* Country Distribution
  - Visualised where survey participants were located.

* Job Satisfaction Analysis
  - Created gauge charts showing:
    - Happiness with current position
    - Satisfaction with current salary

* Difficulty Entering Data Careers (Donut Chart)
  - Analysed respondents' opinions on the difficulty of entering the data field.

The dashboard was formatted and designed to provide an interactive user experience.


## Key Insights

* Survey Participation:  
  The dashboard analysed responses from 630 individuals working within or interested in the data industry.

* Salary Trends by Role:
  Data Scientists had the highest average salary among surveyed roles, followed by Data Architects and Data Engineers.

* Programming Language Preferences:  
  Python was the most commonly preferred programming language, showing its importance within data-related careers.

* Geographical Distribution:  
  The United States had the highest representation among respondents, followed by India and the United Kingdom.

* Job Satisfaction:  
  Respondents reported an average happiness rating of approximately 5.86/10, while salary satisfaction was lower at 4.27/10, suggesting salary satisfaction may be an area for improvement.

* Career Accessibility:  
  Respondents had mixed opinions regarding the difficulty of entering the data field, with ratings ranging from easy to very difficult.


## Potential Improvements

Future improvements to this analysis could include:

* Further standardising categorical responses to ensure consistent grouping across all survey answers.
* Creating additional DAX measures for deeper analysis.
* Adding more detailed comparisons between job roles, salaries, and locations.
* Including additional interactive filters to allow users to explore the data more deeply.

