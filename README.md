# School District Analysis

Performing an analysis using school and student data to inform a school district on their budget and priorities.

##Challenge
Deliverable 1: Replace Ninth-Grade Reading and Math Scores
The school district discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, and they requested for updated data summaries. After further discussion, it was best to only replace the ninth grade math and reading scores at Thomas High School while keeping all other data associated with this student group intact.

Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall.
1. The code snippet provided in Step 1 to import the NumPy module:
<img width="1008" alt="Screen Shot 2022-07-13 at 9 22 58 PM" src="https://user-images.githubusercontent.com/107584891/178891277-bdca4867-b437-455f-82a0-bba29d39bfd6.png">
2. The code snippet provided in Step 2 for the Pandas loc method.
<img width="1007" alt="Screen Shot 2022-07-13 at 9 26 17 PM" src="https://user-images.githubusercontent.com/107584891/178891614-f1290fbc-db18-4c07-bc61-cb90f0a34510.png">
3. ninth-grade reading scores at Thomas High School usiing loc method.
<img width="1004" alt="Screen Shot 2022-07-13 at 9 27 25 PM" src="https://user-images.githubusercontent.com/107584891/178891742-deabeefd-4d2f-4a3f-b500-38dd1d6a9af4.png">
4. student data for NaN's
<img width="1008" alt="Screen Shot 2022-07-13 at 9 29 52 PM" src="https://user-images.githubusercontent.com/107584891/178891967-bfca74af-fbf0-4a41-854a-86aec055c38a.png">


# Repeat the School District Analysis 

##School District Summary

School District Summary
<img width="989" alt="Screen Shot 2022-07-13 at 8 11 12 PM" src="https://user-images.githubusercontent.com/107584891/178884705-25daa824-9fc0-4e0b-a1be-6c977681a0c2.png">



When assessing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped .1, the average reading score stayed the same, the percentage passing math dropped 1%, the percentage passing reading dropped 1%, and the overall passing percent dropped 1%.

##School Summary

School Summary
<img width="1021" alt="Screen Shot 2022-07-13 at 8 28 28 PM" src="https://user-images.githubusercontent.com/107584891/178885136-3d6a1f0f-2edb-4a94-a50e-980bc7429a27.png">
 
##Top Five Performing Schools

Top Five Performing Schools
<img width="1024" alt="Screen Shot 2022-07-13 at 8 31 38 PM" src="https://user-images.githubusercontent.com/107584891/178885420-87456b4b-cd2f-4d00-91fc-cd8bcee7fe29.png">
 


##Bottom Five Performing Schools

Bottom Five Performing Schools
<img width="1017" alt="Screen Shot 2022-07-13 at 8 32 44 PM" src="https://user-images.githubusercontent.com/107584891/178885580-3c8a390c-2288-4790-89a7-9c1e9883bdce.png">


When assessing school summaries and performing schools, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. On the plus side, these changes did not place Thomas High School among the bottom five performing schools. Those ranks remained the same. Per the revised School Summary, Thomas High School now ranks 8th place among 15 high schools in the district.

##Average Math Scores by Grade & School

Average Math Scores by Grade & School

<img width="300" alt="Screen Shot 2022-07-13 at 8 53 59 PM" src="https://user-images.githubusercontent.com/107584891/178888112-0138ecb6-b93f-4a56-8bf1-49526065add7.png">


##Average Reading Scores by Grade & School

Average Reading Scores by Grade & School

<img width="348" alt="Screen Shot 2022-07-13 at 9 00 28 PM" src="https://user-images.githubusercontent.com/107584891/178888741-88301189-dd6d-4f0d-9e6f-667430f03bb9.png">



Another plus side from this data replacement is that it did not change the math and reading scores by grade. Granted, both the average math and reading score summaries were stratisfied by school and grade level. As shown above, the summary tables display "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact.

##School Spending Summary
School Spending Summary
<img width="1013" alt="Screen Shot 2022-07-13 at 8 46 39 PM" src="https://user-images.githubusercontent.com/107584891/178887213-b6fe7cb0-ca45-4677-8c5d-7a17efedc7c2.png">



When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.

##School Size Summary
School Size Summary
<img width="1016" alt="Screen Shot 2022-07-13 at 8 47 20 PM" src="https://user-images.githubusercontent.com/107584891/178887288-5dd992f4-c84c-40ce-b1a3-702cf6d848f1.png">


When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).

##School Type Summary
School Type Summary
<img width="1026" alt="Screen Shot 2022-07-13 at 8 48 13 PM" src="https://user-images.githubusercontent.com/107584891/178887414-8b11427e-52e5-4ad3-a518-509d10e97cc5.png">



In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
Resources
Data Source: PyCitySchools_Challenge_testing
Software: Python, Visual Studio Code, Anaconda, Jupyter Notebook, Pandas

