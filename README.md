                                               #Overview of Project

Maria, the chief data scientist for the city school district, is responsible for all standardized test data for analysis to provide inside trends for the student's performance. Our objective is to aggregate and analyze student funding and test scores data; to showcase school performance trends.

                                                   #Analysis
						   
The school board has concluded that there might be academic dishonesty in 9th-grade math and reading at Thomas High School. We replaced math and reading values in 9th grade with NaN values and kept the rest of the data intact.

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/NaN_value_ths.png)
Fig: 9th grade Thomas High School Data Replaced with NaN

                                                     #Results
						     
School District Summary: As we can see, we have 15 schools with 39170 students in both cases.  Partial removal of the student math and reading data had no effect on did not affect the school district summary. 

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/district_summary_og.png)
Fig: Original School District Summary

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/District_summary_ths.png)
Fig: New School District Summary

School Summary: We see the score changes in math, reading, and overall passing percentage in Thomas High School after introducing the NaN value. 
Initially passing math 67%, reading 69%, and overall passing is 65%.

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/school_summary_og.png)
Fig: Original School Summary for Thomas High School

Eliminating 9th grade boosted the individual results of passing math at 93%, reading at 97%, and overall passing is 90%.

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/school_summary_ths.png)
Fig: New School Summary for Thomas High School

Thomas High school was second in place in the original analysis. After replacing values, Thomas high school still is in second place in the top five. the bottom five schools' performance remains the same.

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/top5_og.png)
Fig: Original Top 5 School

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/top5_ths.png)
Fig: New Top 5 School

Changing 9th-grade math values to NaN for Thomas high school did not affect 10th, 11th or 12th grade or other schools.
Changing 9th-grade reading values to NaN for Thomas high school did not affect 10th, 11th or 12th grade or other schools.

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/9th_grade_nan.png)
Fig: Changing 9th Grade Value with NaN for Thomas High School

We do see a slight variation (0.01%) in the school type scores such as math, reading, and overall passing numbers; however, it is insignificant. Also when we formatted the both dataframes with .map format they look identical. 

![](https://github.com/smzd/School_District_Analysis/blob/main/Resources/school_type_og.png)
Fig: Scores by School Type 

                                                     #Summary
						     
•	School Summary: Originally passed math 67%, reading 69%, and overall passing is 65%. After passing math, 93% read 97 %, and general passing is 90%.

•	School District Summary: No change in the school district summary.

•	School Performance: No change in the top 5 or bottom five lists of schools.

•	Scores by the school budget, school size, and school type: had no effect from the data alteration and did not affect any school.



#Resources: 

Data Source: Schools_complete.csv
	     Students_complete.csv
	     
Software: Python 3.9.7, Visual Studio Code, Version: 1.68.1 (Universal)
                        
