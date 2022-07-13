# School_District_Analysis

## Overview
The purpose of this analysis was to analyze raw data provided by the school board.  Specifically looking at the reading and math scores, drilling down into passing percentages, how those scores varried across each district as well as each type of school.  Originally the data presented contained all schools, but after the board stated the source file of data showed evidence of academic dishonesty, the scope of analysis was extended to exclude the school in question (Thomas High School).  After removing the data in question from Thomas High School's 9th grade class, client requested comparison analysis of what removing that data did to the final outcome.

## Resources
- Software: Python 3.7.6, Jupyter Notebook with Python, Pandas Library and Numpy Library.
- Data Source: schools_complete.csv
- Data Source: students_complete.csv

## Results
Due to the suspected academic dishonesty by the 9th grade students of Thomas High School, the analysis for this client was completed twice.  The first time being the full set of data, including Thomas High School.  The second time the analysis was done, the data from the 9th grade of Thomas High School was removed from any calculations.  

### Thomas High School District Summary
<img width="500" alt="3  thomas district summary df" src="https://user-images.githubusercontent.com/104927745/178400731-60af2b94-e59a-4d75-9619-ed6cde7f4052.PNG">

### Thomas High School data removed 
- Replaced with "NaNs" showing null data.
<img width="500" alt="1  NaNs" src="https://user-images.githubusercontent.com/104927745/178400727-b597d506-2ad0-4568-b9e4-f1ba26c2ba93.PNG">

### Updated District Summary
- The removal of Thomas High School did not have a significant impact on the district analysis as a whole (specifically there are only 461 students in 9th grade at Thomas High School).
<img width="500" alt="2  updated district summary" src="https://user-images.githubusercontent.com/104927745/178400728-381fcbf8-157e-4741-aaeb-2559150ccfc3.PNG">

### Top Five Schools
- Thomas High School is still listed in the Top Five Schools after removal of data.
<img width="500" alt="4  Top five schools" src="https://user-images.githubusercontent.com/104927745/178400732-0b8d4708-4aff-4e64-9d8b-d281fa2e5f29.PNG">

### Bottom Five Schools
- Nothing was affected in the bottom five schools after removal of data.
<img width="500" alt="5  bottom five schools" src="https://user-images.githubusercontent.com/104927745/178400734-15ea6aa2-db3b-4a07-90fe-c44324686464.PNG">

### Average Math Scores
- Only impact is removal of scores for 9th grade in math at Thomas High School.
<img width="500" alt="6  average math scores" src="https://user-images.githubusercontent.com/104927745/178400736-4d1c3db1-e791-4398-b8a7-9b68e5b0308e.PNG">

### Average Reading Scores
- Only impact is removal of scores for 9th grade in reading at Thomas High School.
<img width="500" alt="7  average reading scores" src="https://user-images.githubusercontent.com/104927745/178400737-7486cf8d-6efc-4dc7-8127-9996e7d27f7d.PNG">

### Scores by School Spending
- No discernable impact from removing data.
<img width="500" alt="8  scores by school spending, school size, school type" src="https://user-images.githubusercontent.com/104927745/178400739-972f6b65-e53f-4337-a720-f64843e5d7e2.PNG">

### Scores by School Type
- No discernable impact from removing data, Thomas High School is a Charger School, so we did see a slight decrease ( 0.1%), District data was not affected by removal.
<img width="500" alt="scores by type" src="https://user-images.githubusercontent.com/104927745/178400740-dd09b812-a000-4d60-9c16-9a2ddbd07b2e.PNG">

### Spending Ranges
<img width="500" alt="spending ranges" src="https://user-images.githubusercontent.com/104927745/178400741-18836e3d-8c8d-4e58-82b8-2fbb7d1a8fe7.PNG">

## Summary
In removing the Thomas High School data from this revised analysis, no discernable change was made to the original output of the analysis.
- There were 461 total students in the 9th grade class at Thomas High School which were removed, and the total size of data was 
- In looking at the District Analysis, changes to all scores were less then 0.5%, thus little to no impact to school or student count.
- Thomas High School remained at 2nd place ranking in the top 5 schools, but overall score did drop by less then 1%.
- Scores by school size and school type did not have any drastic effect from data being removed, less then 0.1% of change.
