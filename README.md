# School_District_Analysis

## Project Overview
-We have been notified by our client Maria that the school board she works for believes that there has been some academic dishonesty in the data collected for Thomas High School. The reading grades as well as the math grades seem to have been altered, so I've been asked to fix this.
-I've created a new dataframe using python and pandas within a Jupiter Notebook. I first replaced these math and reading scores with NaN values, or null values. I then compared my new dataframe with the original, flawed dataframe to see exactly how this academic dishonesty has affected the mean of the data.

## Project Results
-Upon creating this new dataframe, I've discovered that the means, or averages, of the math and reading scores of 9th graders at Thomas High school have changed. 
-The reading score average went from 81.88 to 81.86 when I fixed the data.
-The math score average went from 78.99 to 78.93.

## District Summary

-The dataframe I created for the school district summary analyzes 15 schools with a total of 39,170 students.
-The average math score appears to be 78.9, with 74.8% of students passing.
-The average reading score is 81.9, with 85.7% of students passing.
-The overall passing percentage is 74.9%.

-When comparing this data with the original data, we see that the overall percentage was reduced by 1% and the average math scores went down by .1. Below is an image of this dataset.
<img width="1025" alt="Screen Shot 2022-04-02 at 10 59 28 AM" src="https://user-images.githubusercontent.com/100390727/161391188-cc870798-ef61-4a15-8d2d-e36bfab0d76e.png">

## School Summary

-Thomas high school's rank in the school district was affected pretty intensely after I cleaned the data. Originally Thomas High School had an overall passing percentage of 91%, however with the new dataframe I'm able to see that in reality the overall passing percentage is 65%. this is a drop of 26%. This is proof that there was indeed academic dishonesty in the original data.

- Below is an image of the top 5 schools with the highest Overall Passing Percentage, as well as the bottom 5 schools.

### Top 5
<img width="1072" alt="Screen Shot 2022-04-02 at 11 11 06 AM" src="https://user-images.githubusercontent.com/100390727/161391597-3c5e1614-d281-4a05-bd3d-258460fbc521.png">

### Bottom 5
<img width="1072" alt="Screen Shot 2022-04-02 at 11 11 56 AM" src="https://user-images.githubusercontent.com/100390727/161391617-7ed2090b-b7fd-4d7a-baee-ac942a373a10.png">

## School Spending Summary

-There was a decrease in the percentage of students passing reading and math, as well as a decrease in the overall passing percentage for the $630-644 range once I revised the summary. The math and reading scores were unaffected. Below is an image of this data.
<img width="927" alt="Screen Shot 2022-04-02 at 11 15 28 AM" src="https://user-images.githubusercontent.com/100390727/161391727-f066ad62-9d81-42bf-bdcd-946ebeda4c2f.png">

## School Size Summary 
- There was a 6% drop in the percentages of students passing reading and math, as well as a decrease in the overall passing percentage for medium sized schools. Below is an image.
<img width="855" alt="Screen Shot 2022-04-02 at 11 22 09 AM" src="https://user-images.githubusercontent.com/100390727/161391980-581680cf-ffb6-494c-a4b9-cfe59ce8d3c2.png">

## Summary of School Type

- We were analyzing the two different school types: Charter and District. We can see that for Charter Schools, which Thomas High School is a part of, has 94% passing math, 97% passing reading and an overall passing percentage of 90%. Below is an image of this data.
<img width="855" alt="Screen Shot 2022-04-02 at 11 31 02 AM" src="https://user-images.githubusercontent.com/100390727/161392310-de462e91-94fa-42a9-a24b-4512b13f7087.png">


### All in all, there is always a possibility of dishonesty when it comes to data. Data is created by humans and therefore it can be flawed. Thankfully using python and panda dataframes I was able to analyze this data and clean it for the School Board.



