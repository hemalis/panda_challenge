# Overview of School District Analysis

The purpose of this School District analysis is to understand & analyze affects on removing altered grades of Thomas high school's 9th Grade.

# Results:

By removing the altered 9th grade results,here are the observations of the overall school district analysis.

**1.** District summary changed due to Thomas High school's math, reading and overall percentage has changed little bit compared to before. All of them went down as you can see below

##### Before

| Total | Schools | Total Students | Total Budget   | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----- | ------- | -------------- | -------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| 0     | 15      | 39,170         | $24,649,428.00 | 79.0               | 81.9                  | 75             | 86                | 65                |

##### After

| Total | Schools | Total Students | Total Budget   | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----- | ------- | -------------- | -------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| 0     | 15      | 39,170         | $24,649,428.00 | 78.9               | 81.9                  | 74.8           | 85.7              | 64.9              |

**2.** Below are the changes to school summary. That changes similary and went down compared to before except average reading score.

| Metric            | Before    | After     |
| ----------------- | --------- | --------- |
| Math Avg Score    | 83.418349 | 83.350937 |
| Reading Avg Score | 83.848930 | 83.896082 |
| % Passing Math    | 93.272171 | 93.185690 |
| % Passing Reading | 97.308869 | 97.018739 |
| % Overall Passing | 90.948012 | 90.630324 |

**3.** Thomas High School's performance went down compared to other schools in top 5. It still holded it's position at #2.

##### Before

| School Name         | School Type | Total Students | Total School Budget | Per Student Budget | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------- | ----------- | -------------- | ------------------- | ------------------ | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Cabrera High School | Charter     | 1858           | $1,081,356.00       | $582.00            | 83.061895          | 83.975780             | 94.133477      | 97.039828         | 91.334769         |
| Thomas High School  | Charter     | 1635           | $1,043,130.00       | $638.00            | 83.418349          | 83.848930             | 93.272171      | 97.308869         | 90.948012         |
| Griffin High School | Charter     | 1468           | $917,500.00         | $625.00            | 83.351499          | 83.816757             | 93.392371      | 97.138965         | 90.599455         |
| Wilson High School  | Charter     | 2283           | $1,319,574.00       | $578.00            | 83.274201          | 83.989488             | 93.867718      | 96.539641         | 90.582567         |
| Pena High School    | Charter     | 962            | $585,858.00         | $609.00            | 83.839917          | 84.044699             | 94.594595      | 95.945946         | 90.540541         |

##### After

| School Name         | School Type | Total Students | Total School Budget | Per Student Budget | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------- | ----------- | -------------- | ------------------- | ------------------ | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Cabrera High School | Charter     | 1858           | $1,081,356.00       | $582.00            | 83.061895          | 83.975780             | 94.133477      | 97.039828         | 91.334769         |
| Thomas High School  | Charter     | 1635           | $1,043,130.00       | $638.00            | 83.350937          | 83.896082             | 93.185690      | 97.018739         | 90.630324         |
| Griffin High School | Charter     | 1468           | $917,500.00         | $625.00            | 83.351499          | 83.816757             | 93.392371      | 97.138965         | 90.599455         |
| Wilson High School  | Charter     | 2283           | $1,319,574.00       | $578.00            | 83.274201          | 83.989488             | 93.867718      | 96.539641         | 90.582567         |
| Pena High School    | Charter     | 962            | $585,858.00         | $609.00            | 83.839917          | 84.044699             | 94.594595      | 95.945946         | 90.540541         |

**4.** Here is how it's affected the following:

### Math and reading scores by grade

- As we removed 9th Grade score it doesn't have it in after report. Others are not affected as below.

#### Before

| School Name           | 9th  | 10th | 11th | 12th |
| --------------------- | ---- | ---- | ---- | ---- |
| Rodriguez High School | 81.0 | 80.6 | 80.9 | 80.4 |
| Shelton High School   | 84.1 | 83.4 | 84.4 | 82.8 |
| Thomas High School    | 83.7 | 84.3 | 83.6 | 83.8 |
| Wilson High School    | 83.9 | 84.0 | 83.8 | 84.3 |
| Wright High School    | 83.8 | 83.8 | 84.2 | 84.1 |

#### After

| School Name           | 9th  | 10th | 11th | 12th |
| --------------------- | ---- | ---- | ---- | ---- |
| Rodriguez High School | 81.0 | 80.6 | 80.9 | 80.4 |
| Shelton High School   | 84.1 | 83.4 | 84.4 | 82.8 |
| Thomas High School    | nan  | 84.3 | 83.6 | 83.8 |
| Wilson High School    | 83.9 | 84.0 | 83.8 | 84.3 |
| Wright High School    | 83.8 | 83.8 | 84.2 | 84.1 |

### Scores by school spending

- This didn't change drastically as we can see below. It changed at 2 digit float values but rounded values are not changed.

#### Before

| Spending Ranges (Per Student) | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----------------------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| <$586                         | 83.5               | 83.9                  | 93             | 97                | 90                |
| $586-630                      | 81.9               | 83.2                  | 87             | 93                | 81                |
| $631-645                      | 78.5               | 81.6                  | 73             | 84                | 63                |
| $646-675                      | 77.0               | 81.0                  | 66             | 81                | 54                |

#### After

| Spending Ranges (Per Student) | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----------------------------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| <$586                         | 83.5               | 83.9                  | 93             | 97                | 90                |
| $586-630                      | 81.9               | 83.2                  | 87             | 93                | 81                |
| $631-645                      | 78.5               | 81.6                  | 73             | 84                | 63                |
| $646-675                      | 77.0               | 81.0                  | 66             | 81                | 54                |

### Scores by school size

- This didn't change drastically as we can see below. It changed at 2 digit float values but rounded values are not changed.

#### Before

| School Size        | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------ | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Small (<1000)      | 83.8               | 83.9                  | 94             | 96                | 90                |
| Medium (1000-1999) | 83.4               | 83.9                  | 94             | 97                | 91                |
| Large (2000-5000)  | 77.7               | 81.3                  | 70             | 83                | 58                |

#### After

| School Size        | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------ | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Small (<1000)      | 83.8               | 83.9                  | 94             | 96                | 90                |
| Medium (1000-1999) | 83.4               | 83.9                  | 94             | 97                | 91                |
| Large (2000-5000)  | 77.7               | 81.3                  | 70             | 83                | 58                |

### Scores by school type

- This didn't change drastically as we can see below. It changed at 2 digit float values but rounded values are not changed.

#### Before

| School Type | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Charter     | 83.5               | 83.9                  | 94             | 97                | 90                |
| District    | 77.0               | 81.0                  | 67             | 81                | 54                |

#### After

| School Type | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ----------- | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| Charter     | 83.5               | 83.9                  | 94             | 97                | 90                |
| District    | 77.0               | 81.0                  | 67             | 81                | 54                |

# Summary

There were few changes after we updated 9th Score grades with NaNs at district summary level as shown below.
It made changes to the scores and percentages for both subjects but as it wasn't a big drastic update as thankfully it was altered for 1 grade-1 school only (9th grade at Thomas High School)

| Metric                | Before    | After     |
| --------------------- | --------- | --------- |
| Math Avg Score        | 83.418349 | 83.350937 |
| Reading Average Score | 83.848930 | 83.896082 |
| % Passing Math        | 93.272171 | 93.185690 |
| % Passing Reading     | 97.308869 | 97.018739 |
| % Overall Passing     | 90.948012 | 90.630324 |
