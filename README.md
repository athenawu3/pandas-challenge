# Pandas Challenge Overview
This script analyzes student performance in reading and math across many schools. My written report can be found below in this README.

## Code Sources

### Main Script
The main pandas script is located in 'PyCitySchools/main.ipynb'.

### Specific Code Sources

#### Function: Go through each row
- **Section 40, Line 17**: Assisted by ChatGPT

#### Function: Create a dataframe from another dataframe (copy)
- **Section 50, Line 6**: Assisted by ChatGPT

## Written Report

### Summary of Analysis
The district summary looks at the averages across all schools and suggests that while the percent of students passing math and reading individually seem to be high, only 65.17% percent are passing both. We then do a deeper analysis to find where the problem lies.

When looking at the percent of students passing overall for each school, it seems that most schools either have a high success rate (above 88%) or a low success rate (below 60%). No schools fall in between those ranges.

The top schools in terms of the percent of students passing overall are all charter schools with a smaller student body (900-2300). Their students all average around 83 for both their math and reading scores. 

Contrarily, the lowest-performing schools are all district schools with a larger student body (2900-5000). 

When grouping averages by the school's spending range per student, higher spending ranges ($630-680) were associated with lower success rates overall (below 65% passing). Lower spending ranges (under $630) saw higher success rates (above 80%).

When grouping averages by school size, a larger size (2000-5000) was associated with a lower success rate (below 60%), while smaller or medium-sized schools were associated with higher success rates overall (above 80%). 

And finally, there was a drastic difference in success rates fo reading, math, and overall between charter and district schools. Although the average scores were not far apart, the district schools saw significantly lower passing rates in all three categories. 

### Conclusions

Based on this data, there are two general conclusions that we can make. 

On a more superficial level, we can conclude the district schools perform worse than charter schools in terms of the percent of students who successfully pass reading, math, and overall. District schools, which tend to have a larger student body and a larger per student budget, have drastically lower success rates. This could be due to many factors. Perhaps larger class sizes make it difficult for students to connect with teachers and get help. Or, maybe the charter schools' utilize new and innovative approaches to their curriculum (not mandated by the government), which are more useful for learning. Maybe more qualified teachers are attracted to charter schools due to the flexibility. 

On a slightly different note, while the data shows that district schools perform worse than charter schools, this conclusion may be slightly skewed. Because district schools have significantly larger student bodies, it is possible that roughly the same number of students at both district and charter schools are passing overall, despite the percentages being different. Because the student populations are so different, it is hard to pinpoint whether the charter schools have a better curriculum or faculty. Therefore, we can conlude that more data is needed. 