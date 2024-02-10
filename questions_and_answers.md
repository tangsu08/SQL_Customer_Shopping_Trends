# Questions and Answers

1. How many customers are female vs. male?
<img src=images/sql_script/1_gendercount.png width="600" height="250">

**Results:**
| Total_Count | Sex |
| --- | ---|
| 1248 | Female
| 2552 | Male |  

2. What is the maximum and minimum age of the customers?
<img src=images/sql_script/3.maxage.png>
<img src=images/sql_script/4_minage.png>

**Results:**
| Max_age |
| --- |
| 70 |  

| Min_age |
| --- |
| 18 |  

3. What is the average age of the customers?
<img src=images/sql_script/2_avgage.png>

**Results:**
| Rounded_Avg_Age |
| --- |
| 44 |  

4. Does the average age change when looking at gender?
<img src=images/sql_script/5_avgage_bygender.png>

**Results:**
| Rounded_Avg_Age | sex |
| --- | --- |
| 44 | Female |
| 44 | Male | 

No, the average age does not change when looking at gender - the average age is 44 for both Female and Male.
