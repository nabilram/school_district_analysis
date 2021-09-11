# school_district_analysis

## Overview
### Client is school district of XYZ county they are asking for:
* analytics district and school level performance
* identification of worst 5 and top 5 school per passing %
* average math and reading scores per grade level
* scores by (1) school size; (2) expenditure per student; (3) school type

### Possible grade manipulation and cheating has been reported.
Client asks for revamped analytics to see the exent and effect cheating.
* remove all 9th grade scores from Thomas High School (THS)
* rerun overall metrics to see if there is any effect or statistical difference
* report back to see if any actions should be taken
* ipynb notebook, AFTER THS cheating reports, is found [HERE](https://github.com/nabilram/school_district_pandas_analytics/blob/main/PyCitySchools_Challenge.ipynb) .

## Results of Analysis
### District Summary Comparisons
* Before THS wrangling: 
![pre-dis](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_district_summary.PNG)

* After THS data wrangling:
![post-dis](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_district_summary.PNG)

* Effect of grade manipulation: MINOR. Not statistically significant at the district level. 

### School Summary Comparisons
* Before THS wrangling:
![pre-school](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_school_summary.PNG)

* After THS data wrangling:
![post-school](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_school_summary.PNG)

* Effect of grade manipulation: MAJOR. Statistically significant at the school level
* How has it affected THS ranking?
    * THS Ranking dropped but still in top 5: meaning their 10-12th graders do well in school.

### Scores by Grade Level Comparisons
![pre-grade](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_per_grade.PNG)

![post-grade](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_per_grade.PNG)

### Scores by School Expenditure Comparisons

![pre-spend](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_spend.PNG)

![post-spend](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_spend.PNG)

### Scores by School Size Comparisons

![pre-size](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_size.PNG)

![post-size](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_size.PNG)

### Scores by School Type Comparisons

![pre-type](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_type.PNG)

![post-type](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_type.PNG)







