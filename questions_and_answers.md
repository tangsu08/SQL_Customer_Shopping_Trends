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

No, the average age does not change when looking at gender - the average age is 44 for both Female and Male.  

| Rounded_Avg_Age | sex |
| --- | --- |
| 44 | Female |
| 44 | Male | 

5. What is the state where most customers are ordering from? How about the top five states?
<img src=images/sql_script/6_customergeo.png>

**Results:**
| Total_Customers | State |
| --- | --- |
| 96 | Montana |

<img src=images/sql_script/7_topfivegeos.png>

**Results:**
| Total_Customers | State |
| --- | --- |
| 96 | Montana |
| 95 | California |
| 93 | Idaho |
| 92 | Illinois |
| 89 | Alabama |  

6. What are the most and least popular items purchased?
<img src=images/sql_script/8_itempopularity.png>

**Results:**  

Blouse, jewelry, and pants are the top three most popular items purchases while backpack, gloves, and jeans are the least popular items. 

| Number_of_purchases | item_type |
| --- | --- |
| 171 | Blouse |
| 171 | Jewelry |
| 171 | Pants |
| 169 | Shirt |
| 166 | Dress |
| 164 | Sweater |
| 163 | Jacket |
| 161 | Belt |
| 161 | Coat |
| 161 | Sunglasses |
| 160 | Sandals |
| 159 | Socks |
| 158 | Skirt |
| 157 | Scarf |
| 157 | Shorts |
| 154 | Hat |
| 153 | Handbag |
| 151 | Hoodie |
| 150 | Shoes | 
| 143 | Backpack |
| 140 | Gloves | 
| 124 | Jeans|

7. What items are customers spending the most on, on average? 
<img src=images/sql_script/9_purchaseamount.png>

**Results:**  

T-shirts, boots, and dresses are the top three items customers are spending the most on, on average.

| Avg_Amount_Spent | item_type |
| --- | --- |
| 62.9 | T-shirt |
| 62.6 | Boots |
| 62.2 | Dress |
| 61.6 | Shoes |
| 61.1 | Shirt |
| 60.9 | Blouse |
| 60.9 | Hat |
| 60.9 | Jeans |
| 60.9 | Scarf |
| 60.6 | Gloves |
| 60.4 | Backpack |
| 60.1 | Shorts |
| 59.9 | Sunglasses |
| 59.8 | Belt |
| 59.6 | Sneakers |
| 59.5 | Skirt |
| 59.0 | Pants |
| 58.5 | Jewelry |
| 58.2 | Socks |
