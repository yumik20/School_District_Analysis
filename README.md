# School_District_Analysis
Pandas, Anaconda, Python 3.8


## Overview of the school district analysis: 

The school board has notified Maria and her boss that the previous students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards asked for help. Maria asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once that's down, Maria asked me to repeat the school district analysis that I did in this module and write up a report to describe how these changes affected the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

*How is the district summary affected?
After the alternation, the total students number dropped from 39,170 to 38,709, average math score dropped 0.1, %passing math dropped 0.2%, %passing reading dropped 0.3%, overall passing dropped 0.1%. 

*How is the school summary affected?


Thomas High School before 
	Charter	1635	$1,043,130.00	$638.00	83.418349	83.848930	93.272171	97.308869	90.948012


Thomas High School after
	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	93.185689	90.630323        65.076453	


*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s *performance relative to the other schools?

Previously Thomas High School was the top 5 performed school, after replace the grades, it is not longer within the top 5. 


# How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade

After replacing the ninth graders’ math and reading scores for Thomas High School, 9th grade scores all became NaN, other graders are not impacted. 


*Scores by school spending

Thomas High School: 
      
Previously $630-644
Current  $625 -640

The category bin sizes also changed because of this. 


*Scores by school size


Previous: Medium (1000-2000)	83.374684	83.864438	93.599695	96.790680	90.621535
Current: Medium (1000-2000)	83.361201	83.873869	93.582398	95.454971	85.447223 

As you can see, the medium sized schools were impacted by the changes. 

*Scores by school type

Previous: Charter	83.5	83.9	94	97	90
Current: Charter 	83.5	83.9	94	96	87

As you can see, the Charter schools are impacted by the changes. 

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The changes impacted negatively on the overall performances of the Charter schools, the Medium sized Schools, and also impacted the categories of school spending. Most of all, it impacted negatively on Thomas High School's overall passing percentage, caused it to drop about 25%. 