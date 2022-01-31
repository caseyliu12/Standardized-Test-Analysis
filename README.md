# Project 1: Standardized Test Analysis

### Problem Statement

I am hired by the a local educational consulting company in California. The company provides the service to students and help them get in their ideal colleges. The company asks me to analyaze SAT and ACT performance for various districts in California and provide information to the parents, so the parents would know the districts they can send their children to get higher SAT/ACT scores.

The customers (parents) in this company pay great attention to the education of their childen. They are willing to spend money on education and relocate to different cities in the state to help the childen have better learning environment. This project aims to identify the districts that have good student performance on the SAT/ACT tests (from Grade 12 students). I will be the one who provides the recommendations to the parents.


### Background

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math (source). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section (source). 

Many high school students in CA are scrambling to schedule SAT and ACT tests this fall even though some private and public colleges, including both of California’s massive state university systems, say they are not required during the pandemic. Some students and their parents still worry that not taking the standardized entrance exams — or not getting a chance to increase previous scores — will hurt their college application process. They hope the SAT/ACT would strengthen their college applications.


### Data Dictionary

**ACT dataset**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**sname**|*object*|ACT 2019 CA|School Name| 
|**dname**|*object*|ACT 2019 CA|District Name|
|**cname**|*object*|ACT 2019 CA|County Name| 
|**enroll12**|*integer*|ACT 2019 CA|Enrollment of Grade 12| 
|**numtsttakr**|*integer*|ACT 2019 CA|Number of Test Takers| 
|**avgscrread**|*integer*|ACT 2019 CA|Average ACT  English Score| 
|**avgscreng**|*integer*|ACT 2019 CA|Average ACT Reading Score| 
|**avgscrmath**|*integer*|ACT 2019 CA|Average ACT Math Score| 
|**avgscrsci**|*integer*|ACT 2019 CA|Average ACT Science Score| 
|**numge21**|*object*|ACT 2019 CA|Number of Test Takers Whose ACT Composite Scores Are Greater or Equal to 21.| 
|**pctge21**|*object*|ACT 2019 CA|Percent of Test Takers Whose ACT Composite Scores Are Greater or Equal to 21.| 

Source: https://www.cde.ca.gov/ds/sp/ai/

**SAT dataset**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**sname**|*object*|SAT 2019 CA|School Name| 
|**dname**|*object*|SAT 2019 CA|District Name|
|**cname**|*object*|SAT 2019 CA|County Name| 
|**enroll12**|*integer*|SAT 2019 CA|Enrollment of Grade 12| 
|**numtsttakr12**|*integer*|SAT 2019 CA|Number of Test Takers Grade 12| 
|**numerwbenchmark12**|*integer*|SAT 2019 CA|The number meeting the Evidence-Based Reading & Writing (ERW) benchmark| 
|**pctmathbenchmark12**|*integer*|SAT 2019 CA|The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 12.| 
|**nummathbenchmark12**|*integer*|SAT 2019 CA|The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 12.| 
|**pctmathbenchmark12**|*integer*|SAT 2019 CA|The percent of students who met or exceeded the benchmark for SAT Math test for Grade 12.| 
|**totnumbothbenchmark12**|*object*|SAT 2019 CA|The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.| 
|**pctbothbenchmark12**|*object*|SAT 2019 CA|The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.| 

Source: https://www.cde.ca.gov/ds/sp/ai/


### Summery of Analysis

The average numbers of students who take ACT and SAT are 79 and 139 in California schools, while the average numbers of percent of test takers whose ACT or SAT score pass the benchmark are 51% and 43%. Los Angeles is the best district whose students have good performance of SAT/ACT tests. Besides, San Diego, Orange and Riverside are also good options for parents and students. In the tables, we can see top 10 schools in California and in Los Angeles respectively.


### Conclusions and Recommendations

From the data and analysis we provided above, we can see that Los Angeles is the best county for students to choose if they would like to get higher SAT/ACT scores. Los Angeles not only has the most schools, but also has high percentage of students who met the benchmark of SAT/ACT tests. 

In Los Angeles, here are top 5 schools for the percentage of students whose ACT Composite Scores Are Greater or Equal to 21: Whitney High, Academy of the Canyons, La Canada High, Los Angeles Center for Enriched Studies, Arcadia High; Here are top 5 schools for the percent of students who meet the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12: Whitney High, California Academy of Mathematics and Science, La Canada High, San Marino High, South Pasadena Senior High.

We also notice that the performance of SAT ERW test and SAT Math test are highly related. The schools who have high percent of students who meet or exceed the benchmark for ERW are likely to have high percent of students to meet or exceed the benchmark for math.
