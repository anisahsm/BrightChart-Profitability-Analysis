# BrightChart Profitability Analysis
BrightCart is an online retailer that sells products across 8 categories through its website, mobile app, third-party marketplaces, and social commerce. The company did $1M+ in gross revenue over the past two years, but net margins have been shrinking.
The CEO wants to know:
1.	The average profit margin by product category
2.	The profitability across sales channels 
3.	The return rate by category and channel
4.	The platform delivers the best ROAS
5.	The strategy to cut 20% of the marketing budget

## A.	Dataset Structure  
The dataset consisted of three tables: information about order-level transactions, a product catalogue with cost data, and monthly marketing spend by platform.  

## B.	Key Insights  
### 1.	Profitability by Product Category  
<img width="808" height="472" alt="1" src="https://github.com/user-attachments/assets/b14e4052-8cc6-44ef-8d12-44307f551665" />  

BrightCart generated $236,318 in net revenue, with an overall average net margin of 23.8%. Electronics delivered the strongest performance with a 31.1% net margin. Books (11.9%), Beauty (17.4%), Clothing (20.0%), and Sports (23.5%) performed weakly and had below average margins.  

The analysis shows that product cost and shipping cost are the primary drivers of margin performance. Electronics has a relatively lower cost ratio, allowing the category to retain more profits. On the other hand, Books and Beauty have higher product and shipping costs, which lessen profitability. Additionally, categories with higher discount and refund ratios need further attention, as these factors reduce net revenue and negatively impact overall profitability.

### 2.	Profitability by sales channels  
<img width="809" height="472" alt="2" src="https://github.com/user-attachments/assets/3f6fa645-d14c-4295-8c90-977076f0df17" />  

The Mobile App emerged as the strongest-performing channel with approximately $36 profit per order, followed by the Website with $32 profit per order. These channels outperform others primarily because they operate without platform fees. In comparison, Marketplace and Social Commerce channels generate approximately $16 in profit per order, indicating that platform-related fees significantly reduce profitability. 

### 3.	Return rate by category and channel  
<img width="808" height="472" alt="3" src="https://github.com/user-attachments/assets/14d72f8a-f564-4134-b77d-13c50346846d" />  

Refund-related costs totaled around $20,582. At the product category level, Electronics (8.6%), Books (8.4%), and Clothing (8.2%) recorded the highest return rates. From a channel perspective, Social Commerce showed the highest overall return rate at 9.1%.   

Further analysis indicates that Food & Beverages, Clothing, Home & Kitchen, and Books sold through Social Commerce recorded return rates exceeding 12.5%, making them key areas of concern. 

### 4.	Platform with the best ROAS  
<img width="808" height="472" alt="4" src="https://github.com/user-attachments/assets/1b69b1e0-f145-4127-85bf-f344c1b95d1c" />  

TikTok Ads delivered the strongest performance with a ROAS of 24, making it the most efficient marketing channel.   

On the contrary, Email Marketing generated the lowest ROAS with 4.8, while simultaneously showing the highest Cost per Click (CPC) and Cost per Acquisition (CPA). This indicates that the company is spending more to acquire customers but receiving relatively low returns.

### 5.	Marketing budget  
To reduce the marketing budget by 20%, spending patterns were reviewed by considering both ROAS performance and spending levels. The budget reductions should focus on platform-month combinations where high spending is accompanied by low ROAS, as these areas indicate inefficient resource allocation.   
The following areas are suggested for budget reduction:  
<img width="721" height="168" alt="5" src="https://github.com/user-attachments/assets/b7bc7dce-9b5b-421f-a6a6-ebe60eb03a4d" />  

## C.	Strategic Recommendations  
1.	Improve profitability in low-margin categories  
Focus on reducing product and shipping costs in Books, Beauty, Clothing, and Sports, while reviewing discount and refund strategies to improve margins.  
2.	Prioritize growth through owned channels  
Increase investment in Mobile App and Website, as these channels generate the highest profit per order and avoid platform fees.  
3.	Reduce return rates in high-risk segments  
Prioritize improvements in Social Commerce, especially for Food & Beverages, Clothing, Home & Kitchen, and Books, by enhancing product information and quality control.  
4.	Reallocate marketing investment to high-performing platforms  
Increase focus on strong-performing channels such as TikTok Ads and optimize or reduce spending in underperforming channels.  
5.	Optimize budget allocation based on performance  
Reduce spend in low-ROAS, high-spend campaigns and periods, while protecting high-performing investments to improve overall marketing efficiency.

## Tools  
Excel (Pivot Table, Pivot Chart, Power Query, Power Pivot, DAX)

## Author  
Anisah Septiani M.  
LinkedIn: https://www.linkedin.com/in/anisahseptiani/  
GitHub: https://github.com/anisahsm  
Email: anisahseptianim@gmail.com






