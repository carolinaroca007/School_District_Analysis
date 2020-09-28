# School_District_Analysis

## Analysis Overview

The purpose of this analysis was to aid Maria, the Chief Data Scientist for a city school district, analyze data on student funding and students' standardize test scores. The task is to aggregate the data and showcase trends in school performance. This analysis will assist the school board and superintendent in making decisions regarding the schools' budgets and priorities. 

After the initial analysis, the school board informs Maria that there is evidence of academic dishonesty in the math and reading scores of Thomas High School's ninth graders. Maria later tasks me with replacing those grades with NaNs while keeping the rest of the data intact, repeating the school district analysis, and describing how the changes affected the overall analysis. 

## Analysis Results

#### District Summary
The district's metrics were not greatly affected with the changes to our code because the percentage of students removed was 1% of the student population; 461 ninth graders from Thomas High School were removed from the total population of 39,170 students. The changes to the scores are evident in the tenths place; however, due to formatting policies where percentages are whole numbers and are rounded up if the decimal is equal to or greater than .50, the difference is only seen prior to formatting.

![Initial District Summary](https://github.com/carolinaroca007/School_District_Analysis/blob/master/district_summary_pre.png)

![Final District Summary](https://github.com/carolinaroca007/School_District_Analysis/blob/master/district_summary_post.png)

### School Summary
The schools' metrics saw a change to its top five performing schools after the changes to our code where we removed the reading and math scores of the Thomas High School's ninth graders.

![Initial_School_Summary](https://github.com/carolinaroca007/School_District_Analysis/blob/master/school_summary_pre.png)
![Final_School_Summary](https://github.com/carolinaroca007/School_District_Analysis/blob/master/school_summary_post.png)

#### Highlights
- Math and reading scores by grade: The scores for the 10th graders increased
- Scores by school spending: The scores of the $630-644 spending bin increased slightly
- Scores by school size: The scores of the school Medium size increased slightly
- Scores by school type: The scores of the District school type increased slightly


## Analysis Summary
Maria was able to submit the district and school metrics summaries to the school board and superintendent to support their decisions regarding the schools' budgets and priorities. After the school board found evidence of academic dishonesty in the grades of Thomas High School ninth graders, we were able to quickly alter our code to present a new summary to the school board while they made time to investigate the issue. Altering the reading and math scores of the Thomas High School ninth graders lowered the total number of students, the percentage of students passing math increased, the percentage of students passing reading increased, and the overall percentage of students passing also increased. We can conclude that the ninth graders' scores were skewing the overall passing data for Thomas High School.

