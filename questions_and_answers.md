# Questions and Answers

## Demographic Makeup
### 1. How many customers are female vs. male?
<img src=images/sql_script/1_gendercount.png width="420" height="250">  

#### Results:  
| Total_Count | Sex |
| --- | ---|
| 1248 | Female
| 2552 | Male |  

### 2. What is the maximum and minimum age of the customers?
<img src=images/sql_script/3.maxage.png width="420" height="250">

#### Results:
| Max_age |
| --- |
| 70 |

<img src=images/sql_script/4_minage.png width="420" height="250">

#### Results:
| Min_age |
| --- |
| 18 |  

### 3. What is the average age of the customers?
<img src=images/sql_script/2_avgage.png width="480" height="250">

#### Results:
| Rounded_Avg_Age |
| --- |
| 44 |  

### 4. Does the average age change when looking at gender?
<img src=images/sql_script/5_avgage_bygender.png width="480" height="250">

#### Results:  

No, the average age does not change when looking at gender - the average age is 44 for both Female and Male.  

| Rounded_Avg_Age | sex |
| --- | --- |
| 44 | Female |
| 44 | Male | 

### 5. What is the state where most customers are ordering from? How about the top five states?
<img src=images/sql_script/6_customergeo.png width="480" height="250">

#### Results:
| Total_Customers | State |
| --- | --- |
| 96 | Montana |

<img src=images/sql_script/7_topfivegeos.png width="480" height="250">

#### Results:
| Total_Customers | State |
| --- | --- |
| 96 | Montana |
| 95 | California |
| 93 | Idaho |
| 92 | Illinois |
| 89 | Alabama |  

## Order Information
### 6. List the total number of purchases made for each type of item. What are the most and least popular items purchased?
<img src=images/sql_script/8_itempopularity.png width="480" height="250">

#### Results:

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

### 7. List the average amount spent for each type of item. What items are customers spending the most on, on average? 
<img src=images/sql_script/9_purchaseamount.png width="480" height="250">

#### Results:  

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

### 8. List the total number of purchases made for each item size.
<img src=images/sql_script/10_popularsize.png width="480" height="250">

#### Results:
| Total_Purchases | size_of_item |
| --- | --- |
| 1755 | M |
| 1053 | L |
| 663 | S |
| 429 | XL |

### 9. List the average rating customers give to each category of items. 
<img src=images/sql_script/16_avgrating_by_category.png width="480" height="250">

#### Results:
| avg_rating | category |
| --- | --- |
| 3.79 | Footwear |
| 3.77 | Accessories |
| 3.75 | Outerwear |
| 3.72 | Clothing |

## Shopping Behavior
### 10. Do customers who are subscribed to the site make more frequent purchases than those who are non-subscribers?
<img src=images/sql_script/12_purchase_frequency.png width="480" height="250">

#### Results: 
| count_of_purchases_made_by_subscribers | frequency |
| --- | --- |
| 160 | Annually |
| 157 | Weekly |
| 154 | Every 3 Months |
| 153| Fortnightly |
| 149 | Monthly |
| 140 | Quarterly |
| 140| Bi-Weekly |

<img src=images/sql_script/13_purchase_frequency_nonsubscribers.png width="480" height="250">

#### Results: 
| count_of_purchases_made_by_nonsubscribers | frequency |
| --- | --- |
| 430 | Every 3 Months |
| 423 | Quarterly |
| 412 | Annually |
| 407 | Bi-Weekly |
| 404 | Monthly |
| 389 | Fortnightly |
| 382 | Weekly |

Comparing the two, subscribers tend to make more frequent purchases than nonsubscribers - with weekly purchases as their second top frequency of when they make purchases. Nonsubscribers make most of their purchases every 3 months, followed by quarterly. 

