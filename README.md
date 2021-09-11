# school_district_analysis

## Overview
### Client is school district of XYZ county. They are asking for:
* analytics at district and school level performance
* identification of worst 5 and top 5 school per passing %
* average math and reading scores per grade level
* scores by (1) school size; (2) expenditure per student; (3) school type

### Possible grade manipulation and cheating has been reported:
Client asks for revamped analytics to see the exent and effect possible cheating
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

* Effect of grade manipulation: MINOR. Not statistically significant at the district level

### School Summary Comparisons
* Before THS wrangling:

![pre-school](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_school_summary.PNG)

* After THS data wrangling:

![post-school](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_school_summary.PNG)

* Effect of grade manipulation: MAJOR. Statistically significant at the school level
* How has it affected THS performane compared to other school?
    * from 65% to 90% passing rate -- THS shot up to the top ranked performing schools
    
### Scores by Grade Level Comparisons
* Before THS wrangling:

![pre-grade](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_per_grade.PNG)

* After THS data wrangling:

![post-grade](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_per_grade.PNG)

* Effect of grade manipulation: as expected 9th Grade THS scores are now NaN (not a number)

### Scores by School Expenditure Comparisons
* Before THS wrangling:

![pre-spend](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_spend.PNG)

* After THS data wrangling:

![post-spend](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_spend.PNG)

* Effect of grade manipulation: grades under expenditure bin 630-644USD are affected
* Expected as THS is within this spend per student bin classification

### Scores by School Size Comparisons
Before THS wrangling:
![pre-size](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_size.PNG)

* After THS data wrangling:
![post-size](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_size.PNG)

* Effect of grade manipulation: grades under Medim size bin are affected
* Expected as THS is within this school size bin

### Scores by School Type Comparisons
* Before THS wrangling:
![pre-type](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/pre_type.PNG)

* After THS data wrangling:
![post-type](https://github.com/nabilram/school_district_pandas_analytics/blob/main/resources/post_type.PNG)

* Effect of grade manipulation: grades under Charter classification affected.
* Expected as THS is classified as a charter school. 

## Summary
* Grade manipulation had the most effect on school level metrics
* Grade manipulation had least effect of district level metrics. 
* Effect on data using different indices varies -- depending on index used. 
    * Overall, the index in which THS falls under is what is most affected








