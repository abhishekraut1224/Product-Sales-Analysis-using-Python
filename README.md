# Product-Sales-Analysis-using-Python

#### Project Overview
  This project analyzes product sales data for 2019. The dataset consists of monthly sales reports that have been merged and cleaned for analysis. The project aims to gain insights into sales trends, customer purchasing behavior, and product performance.

#### Problem Statement 
The business wanted to understand its sales trends, peak sales period, and customer buying behavior to improve marketing and inventory decisions

#### Dataset Information
- The dataset contains sales data for 12 months of 2019.
- The data includes Order ID, Product, Quantity Ordered, Price Each, Order Date, and Purchase Address.

#### Goal 
    My goal was to analyze data to identify
    1) The best Month and City for sale
    2) The Optimal time for Advertisement
    3) Frequently bought products together
    4) Top-selling products with a reason for their performance


## Total Sales Over Months in all Year
![image](https://github.com/user-attachments/assets/db90a200-34e3-4e38-8fa0-39f544376637)

##### Since the data is from the USA, the increase in sales during December
##### can be attributed to the Christmas season, when people tend to buy gifts
##### and do a lot of holiday shopping.

## What City had the highest number of Sales
![image](https://github.com/user-attachments/assets/b0928659-316b-4403-8815-df98f49e7e05)
##### San Francisco(CA 94016) are getting the best sales
##### San Francisco(CA 94016) Silicon Valley, so more electronic purchases are made there

##  What time should we display advertisements to maximize the likelihood of customers buying products
![image](https://github.com/user-attachments/assets/7ad7e765-40da-48ce-86f0-88963f337a0e)
##### sales peaked around Afternoon 11 AM, 12 AM, and Evening 7 PM

![image](https://github.com/user-attachments/assets/6b7d52b2-382f-4e30-9b37-b8b67c129897)
##### We should spend more on showing advertisements in the Afternoon and Evening
##### Cause at that time, the Customer is very Active on our site buying Products
##### less active on our site to buy a product in the Morning and at night

## What product sold the most? Why do you think it sold the most?
##### The Batteries are getting sold the most, and the LG Dryer is getting sold very less
##### Batteries are cheaper than most of the products like the LG Dryer

## Proving why people buy Batteries more than other products
![image](https://github.com/user-attachments/assets/565ec9a5-658a-455d-a38a-28445b8d0547)





#### Technologies and Libraries Used
I used Python throughout the project. To merge the monthly files, I used the os library, then performed all the data cleaning and transformations with pandas — like extracting the month, hour, and city. For calculating totals and other stats, I used NumPy. And to present insights visually, I built charts using matplotlib and seaborn.
  
While working on the project, I faced a few challenges, like merging large files efficiently and visualizing some complex patterns. So, I referred to documentation, used Google, and even took some help from ChatGPT to understand certain techniques better. It helped me speed up my learning and apply best practices.


#### Conclusion:
As a result of the analysis, I found that December had the highest sales, around 4.6M, likely due to holiday shopping. San Francisco had the most orders, and sales peaked around Afternoon 11 AM, 12 AM, and Evening 7 PM, suggesting those are ideal times for running ads. I also found that batteries and USB-C cables were frequently bought together, so recommending bundles could increase revenue. These insights could directly help with optimizing marketing and stock management.
