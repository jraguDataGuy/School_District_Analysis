# Py City Schools - Cheaters *Never* Prosper
## Objective
As stated, we have been made aware of academic dishonesty for the 9th grade test scores for Thomas High School. We had performed our analysis prior to being made aware. It is necessary we remove the scores from our data to create the most accurate data. Given only 461 students were removed form a data set 39,170; I wouldn't anticpate significant movement in our analysis. 
## District Summary
![Image of District Summary](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/District_Summary.png)

Once we removed the students, we saw insignificant changes in the testing scores. With rounding, the changes were barely noticeable. 
## Summary of Thomas High School
Prior to removing the 9th graders' scores, we saw THS with low passing scores and overally passing scores.

![Image of School Summary before](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/School_summary-before.png)

After clean up, we saw a drastic increase in the school's passing percentages. One could conclude there was no advantage to cheating for our 9th graders.

![Image of School Summary after](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/school_summary_after.png)

## High and Low Performing Schools
THS moves into the top 5 for Overall passing after adjusting our metrics:
### Top 5 Schools
![Top 5 Schools](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Top_5.png)

### Bottom 5 Schools
![Image of bottom 5](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Bottom%205%20Schools.png)

## Math and Reading Scores by Grade
As you can see by the "NAN", we have successfully removed the 9th grade math and reading scores from THS:

### Math Scores
![Image of Math Scores](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Math_Scores_by_Grade.png)

### Reading Scores
![Reading Score](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Reading_Scores_by_School.png)

## Scores by Size
![Scores by Size](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Scores_By_Size.png)

The Changes by size include:
- Medium Average Math Score decreasing from 83.374684 to 83.361201
- Medium Average Reading Score increasing from 83.864438 to 83.873869
- Medium % Passing Math decreasing from 93.599695 to 93.582398
- Medium % Passing Reading decreasing from 96.790680 to 96.732654
- Medium % Passsing Overall decreasing from 90.621535 to 90.557997

## Scores by Spending

![Scores by Spend](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Scores_By_Spending.png)

The changes by Spending in the $630-644 bracker include:
- Average Math score decreased from 78.518855 to 78.502002
- Average Reading score increased from 81.624473 to 81.636261
- % Passing Math decreased from 73.484209 to 73.462589
- % Passing Reading decreased from 84.391793 to 84.319261
- % Passing Overall decreased from 62.857656 to 62.778233

## Scores by Type

![Scores by Type](https://github.com/jraguDataGuy/School_District_Analysis/blob/main/Resources/Scores_By_Type.png)

The changes here are minimal and are completely eliminated when we round to 0 decimal places. We saw:
- Math scores decrease in Charter from 83.473852 to 83.465425
- Reading scores in Charter increase from 83.896421 to 83.902315
- % Passing Math decrease in Charter from 96.620830 to 93.610020
- % Passing Reading decrease in Charter from 96.586480 to 96.550223
- % Overall Passing decrease in Charter from 90.432244 to 90.392533

The placement of the decimal place is hiding the changes, which highlights how minmal they are.

# Summary
Ultimately, we see the miniscule changes above. The buckets involving THS (Spending $630-644, Medium Size, Charter) all saw:
- Math scores decrease
- Reading scores increase
- % Passing Math decrease
- % Passing Reading decrease
- % Overall Passing decrease

To get a better idea of how our district is performing, we will need to run this in the future with true 9th grade data. However, removing the data this year did not have significant effect on our orirginal report. 
