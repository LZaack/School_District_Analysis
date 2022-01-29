# School District Analysis

## School District Analysis Overview

My first assignment was to help Maria analyze data on student funding and students’ standardized test scores. She gave me access to every student’s math and reading scores as well as various information on the schools she attended. My task was to aggregate the data and showcase trends in school performance. 

This analysis could help the school board and superintendent in making decisions regarding the school budgets and priorities.

The list of deliverables for the analysis of the school district is:

**A.** A high-level snapshot of the district's key metrics, presented in a table format;

**B.** An overview of the key metrics for each school, presented in a table format; and

**C.** Tables presenting each of the following metrics:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

### Last minute change

I recently delivered my analysis when the school board notified Maria that the CSV file we have worked with, shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 

Therefore, she has asked me to replace the math and reading scores for Thomas High School ninth-graders with NaNs while keeping the rest of the data intact. Consequently, of replacing the math and reading scores, Maria asked me to write up the following report to describe how these changes affected the overall analysis.

## School District Analysis Results

The reduction of the sample taking out the 461 Thomas High School ninth-graders, provoked the following changes:

***I.*** In the district summary:

`After`

![district_summary_df_1](https://user-images.githubusercontent.com/95454286/151656603-d845e0e4-6635-4e1e-b70c-1f644afe671e.png)

`Before`

![district_summary_df_2](https://user-images.githubusercontent.com/95454286/151656606-f2a31603-ca0e-4b1e-9f34-0cc2b765ab21.png)

As you may notice, the % Passing Math, % Passing Reading, and %Overall Passing slightly decreased, but no other data was affected.

***II.*** In the school summary:

`After`

![per_school_summary_df_1](https://user-images.githubusercontent.com/95454286/151656623-1316a5e2-0d07-462b-a278-8cf734c65fed.png)

`Before`

![per_school_summary_df_2](https://user-images.githubusercontent.com/95454286/151656625-e0dd8575-5065-409a-af46-bd47d342e19d.png)

As it is shown, the % Passing Math, % Passing Reading, and %Overall Passing in Thomas High School row slightly decreased, but the budget and the other columns were not affected.

***III.*** The Thomas High School’s performance relative to the other schools:

`After`

![top_schools_1](https://user-images.githubusercontent.com/95454286/151656638-21917fa4-eee1-4a46-bd72-be1cf9326aa7.png)

`Before`

![top_schools_2](https://user-images.githubusercontent.com/95454286/151656643-4547969c-faf3-44fb-8927-49b02c82313c.png)

It did not affect the position in the list of top schools, and the grades took off slightly increased the percentages of math, reading, and overall.

***IV.*** Math and reading scores by grade:

`After`

![math_scores_by_grade_1](https://user-images.githubusercontent.com/95454286/151656655-6b21b422-e3a6-4943-a4c3-66e346f628fb.png)
![reading_scores_by_grade_1](https://user-images.githubusercontent.com/95454286/151656658-71ec27f2-d727-4eb4-8eca-1fb536841290.png)

`Before`

![math_scores_by_grade_2](https://user-images.githubusercontent.com/95454286/151656661-12a265fa-6de1-41b7-b049-fb41b0ef21cc.png)
![reading_scores_by_grade_2](https://user-images.githubusercontent.com/95454286/151656664-bb1ef8b3-923e-4572-b9c8-5947badfb696.png)


There is no change.

***V.*** Scores by school spending:

`After`

![schools_spending_1](https://user-images.githubusercontent.com/95454286/151656669-61afd9df-7b9c-4989-a4bc-6b1b1ceaf831.png)

`Before`

![schools_spending_2](https://user-images.githubusercontent.com/95454286/151656673-f30e19ff-c686-4248-82c0-dc89b552c73a.png)

The % Passing Math, % Passing Reading, and %Overall Passing in Thomas High School row slightly decreased, but it still in the same spending range.

***VI.*** Scores by school size:

`After`

![schools_size_1](https://user-images.githubusercontent.com/95454286/151656682-ddc08016-b14e-4707-aa8c-3aa626f88976.png)

`Before`

![schools_size_2](https://user-images.githubusercontent.com/95454286/151656684-3d7ba72a-5be5-4687-806b-6029d1ede5a9.png)

The % Passing Math, % Passing Reading, and %Overall Passing in Thomas High School row slightly decreased, but it still in the same size range.

***VII.*** Scores by school type:

`After`

![school_type_1](https://user-images.githubusercontent.com/95454286/151656687-1032f803-4eb3-49b9-a8b8-b1a632ed9b58.png)

`Before`

![school_type_2](https://user-images.githubusercontent.com/95454286/151656689-1e8347e2-cc47-4174-9fbd-084da51bd667.png)

Due to the Thomas High School being a charter school, the charter percentages in the data by school type were slightly affected.

## Summary of changes updated School District Analysis

**1.** The % Passing Math, % Passing Reading, and %Overall Passing slightly decreased in the district summary.

**2.** The % Passing Math, % Passing Reading, and %Overall Passing in Thomas High School row slightly decreased.

**3.** The grades took off slightly increased the percentages of math, reading, and overall, so it did not affect the Thomas High School position in the list of top schools.

**4.** The charter percentages in the data by school type were slightly affected.
