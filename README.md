# School_District_Analysi

Overview of the school district analysis: 
Maria needs help to analyze the students of 15 schools and needs to get some information regarding the schools, such as school performance on budget and school size and school type. Also, she wants to know about the average reading and math score by students in each level at each school. There are two CSV files, one as student grades and the other is for the 15 High School types. 
Results: Using bulleted lists and images of DataFrames as support, address the following questions.
•	How is the district summary affected?
After being told that there was dishonesty at the ninth grade at Thomas High School, the reading and math score were calculated and after removing the night grade, it was also calculated. The result shows that the percentage increased after removing the ninth grade as below:
Before taking the ninth grade from Thomas High School.
 ![image](https://user-images.githubusercontent.com/49285767/183267978-43d0df0c-afb8-4258-8ada-fe2af34f909c.png)

After taking the ninth grade from Thomas High School.
 ![image](https://user-images.githubusercontent.com/49285767/183267982-7d51453d-1371-41df-997e-f1a00a331990.png)

Looking closely, the data was performed on 15 High School and total of 39,170 students. After taking out the ninth grade from the list Ave math score changed from 79 to 78.9 and Ave reading score remained the same as 81.9. The passing Math changed from 75 to 73.9 and passing reading changed from 86 to 84.7. Also, overall passing has changed from 65 to 64.1.
•	How is the school summary affected?
 The school summary below indicates that after removing the ninth grade from Thomas High School, we see overall changes in Thomas High School columns.

Before taking the ninth grade from Thomas High School.
 ![image](https://user-images.githubusercontent.com/49285767/183267991-e7c4dfb4-23c5-4057-b9ba-b6ce28ad60ad.png)

After taking the ninth grade from Thomas High School.
 ![image](https://user-images.githubusercontent.com/49285767/183267996-32246126-15fe-4ec0-b884-f1c6ec2d9fe9.png)

•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
From the school summary we can see before dropping the ninth grade from the list, Thomas high School was in second place among those 15 schools and the top 5 performing schools. After dropping the ninth school Thomas high school position in the performance no change has been observed and Thomas High School is still the second top performer school, although the percentages slightly has changed. 

Top 5 performers school before dropping ninth grade
 ![image](https://user-images.githubusercontent.com/49285767/183268004-a5394681-258c-4b3b-bab2-60c40c4895c1.png)

Top 5 performers school after dropping ninth grade
 ![image](https://user-images.githubusercontent.com/49285767/183268014-fc7b17ff-8995-4289-8fab-06bf4b789e13.png)


•	How does replacing the ninth-grade scores affect the following:

	Math and reading scores by grade



We can see that the ninth grade for math and reading has changed to nan as they have been removed.

![image](https://user-images.githubusercontent.com/49285767/183268043-b8a6fa56-c421-4e8d-a948-678f86282b97.png) 


	Scores by school spending
After dropping the ninth grade from Thomas High School, there is affect in the bin between $631-$645 that Thomas High School was before in that category.
 ![image](https://user-images.githubusercontent.com/49285767/183268075-f882adb6-92cf-462a-bb1d-4b983b79974f.png)

 
	Scores by school size
School size has not been affected at all.

![image](https://user-images.githubusercontent.com/49285767/183268085-cc1325e5-869d-410c-a3aa-0a18151c7b6e.png)


	Scores by school type
The changes might be very small percentages.
 
 ![image](https://user-images.githubusercontent.com/49285767/183268102-83fad779-26d7-4a6e-b6dd-e26f2fa7ea63.png)


2.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
we realized after ninth grade has been dropped from the data. We saw some changes in our analysis and mentioned those changes to Maria. We see the average math and reading has been changed a lot after dropping the dishonest 9th grade result. Also, there was small changes observed in some of the score school spending , score by school type and scores by school size. 


