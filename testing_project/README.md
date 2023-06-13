# California High Schools That Could Most Benefit from TEEN TECH Programing

STEM (Science, Technology, Engineering, Math) jobs are on the rise with no end in sight.  However,  students do not always learn these fundamental skills.  The reasons for this are numerous and often difficult for schools to surmount without outside help.  TEEN TECH has helped students in Minneapolis and Saint Paul achieve the knowledge they need to succeed in STEM jobs.  TEEN TECH has an opportunity to expand their operation into California.    

The objective of this projects is to find which 3 high schools in California could most benefit from TEEN TECH programming.  This assessment will be conducted from last year’s SAT Math scores.  The SAT is widespread in California and an indicator of readiness to enter a STEM related college program.    

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|SName|object|sat_ca|School Name| 
|DName|object|sat_ca|School District Name| 
|CName|object|sat_ca|City in which the school is located| 
|Enroll12|float|sat_ca|12th grade enrollment for school year 2018-2019| 
|NumTSTTakr12|float|sat_ca|Number of 12th graders that took the SAT in school year 2018-2019| 
|NumERWBenchmark12|float|sat_ca|Number of 12th graders that socred 480 or higher on the English sections of the SAT| 
|NumMathBenchmark12|float|sat_ca|Number of 12th graders that socred 530 or higher on the math section of the SAT| 
|Enroll11|float|sat_ca|11th grade enrollment for school year 2018-2019| 
|NumTSTTakr11|float|sat_ca|Number of 11th graders that took the SAT in school year 2018-2019| 
|NumERWBenchmark11|float|sat_ca|Number of 11th graders that socred 480 or higher on the English sections of the SAT| 
|NumMathBenchmark11|float|sat_ca|Number of 11th graders that socred 530 or higher on the math section of the SAT| 
|TotNumBothBenchmark12|float|sat_ca|Number of 12th graders that socred 530 or higher on the math section and 480 or higher on the english sections of the SAT| 
|TotNumBothBenchmark11|float|sat_ca|Number of 11th graders that socred 530 or higher on the math section and 480 or higher on the english sections of the SAT| 
|perct_all_math|float|sat_ca|Percent of students that scored 530 or higher in math| 

## Executive Summary

Which California schools would benefit greatest for a TEEN TECH program?  
This project used SAT Math scores from the 18-19 school year to find the 3  schools with the lowest percentage of students reaching the math benchmark of 580.  
The dataset used consisted of test scores from 11th and 12th grade students that took the SAT during the school year.  It was provided from the state of California.  Tracking data, percent for each grade level, and school year information was removed from the dataset.  In addition some cells had ‘*’ this was interpreted at Null and changed to NAN in the data set.  

This project found the 10 lowest performing schools in California and that 7 of them are in the greater LA area.  It is recommended that TEEN TECH attempt to start programs at Fairvalley High School, Buena Vista Continuation, and El Camino High School  High School.  Once those programs are established it is recommended to start programs in other LA schools such at Buena Vista High School or Augustus F. Hawkins High School campus 
