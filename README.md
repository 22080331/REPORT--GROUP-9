                                   INTRODUCTION TO DATA SCIENCE
                                                            
                                                            -Lecturer:EMANUELPLAN

                                    REPORT-GROUP 9 :ONLINE SALES

  ![](images/nab2.jpg)  

  Members of group
  
                              |  FULL NAME      | ID number|  
                              |--------------   |----------|
                              | ĐẶNG TRỌNG NAM  | 22080331 | 
                              | ĐINH LÂM PHƯƠNG | 22080337 | 
                              | HÀ NGỌC ANH     | 22080294 | 
                              | TRẦN KHÁNH LINH | 22080324 | 
                              | HOÀNG QUỐC BẢO  | 22080304 | 
                              | NGÔ TIẾN HUY    | 22080319 | 
                  

# 1.INTRODUCTION 
-Online sales is the sale of goods over the Internet, allowing customers to easily purchase and pay securely online without having to visit a store. .In today's digital age, online sales have become an integral part of the goods business landscape. It has a significant impact on consumer behavior and business strategies, as well as the consumer market and most factors related to the goods business. This project explores the complexities of online sales through data visualization, aiming to uncover trends, patterns, and insights of customer that drive successful e-commerce strategies. We aim to answer essential questions related to sales total, customer buying habits, needs, and seasonal order fluctuations.This analysis contributes to businesses' ability to understand their current performance. Additionally, it supports forecasting future trends and making informed decisions and strategic directions for their business.

## 2.DATA SOURCES📌

![](images/order.jpg)                     

![](images/datail.jpg) 


           
## 3.WHAT CLEANING DATA 

-Date Formatting: Convert the Order Date column to a datetime format for easy time-based analysis.

-Data Type Conversion: Ensure each column has the correct data type (e.g., convert dates and numerical columns as needed).

-Removing Duplicates: Check for any duplicate Order ID entries.

-Handling Missing Values: Verify that all rows contain data; if any are missing, decide whether to fill or drop them.

-Standardizing Text: Standardize the format for entries in State and City to ensure consistency.

# 4.BASIC ANAYLYSIS 📊

###### 5.1. Distribution of state order

  
 ![](images/ảnh1.jpg)  


Overview: The chart "Distribution Top 10 States by order" shows the number of orders in the 10 states with the highest number of orders in India. The height of each column corresponds to the number of orders placed in that state, namely:
1. Maharashtra and Madhya Pradesh lead with similar orders, 94 and 93 orders respectively. These two states dominate the other states.
2. Rajasthan ranks third with 32 orders, followed by Gujarat and Uttar Pradesh with similar orders (27 and 25 orders).
3. States such as Punjab, Delhi, and West Bengal have orders ranging from 20 to 25, indicating a similar level of orders here.
4. States at the bottom of the list, such as Goa,
Sikkim, and Tamil Nadu have only 8 to 12 orders, indicating a much lower consumption level than the leading states.
=> Overall, Maharashtra and Madhya Pradesh are the two states with the most active online ordering activity, while other states have significant variations in the number of orders.

•	The large difference in the number of online orders between states in India is a common phenomenon and has many factors influencing it, specifically:
1.	Socio-economic factors
+ Level of economic development: States with more developed economies and higher per capita income often have higher consumption demand, including online consumption.
+ Infrastructure: Developed transportation, telecommunications, and banking systems will facilitate online shopping.
+ Level of urbanization: Large cities are often densely populated, have more young people and have access to high technology, thereby promoting the demand for online shopping.
+ Level of technology popularity: The higher the rate of people accessing the internet and using smart devices, the greater the demand for online shopping.
+ex:
 - Maharashtra, Madhya Pradesh, Gujarat: These states have large populations and high urbanization, creating a larger consumer market.
- Tamil Nadu, Sikkim: Smaller populations and lower urbanization levels may be responsible for lower order volumes.
- Maharashtra: As the economic hub of India, with high GDP and high per capita income, people are more likely to spend more on online shopping.
- Northern states: Some northern states have lower living standards and lower spending power on non-essential goods.

2.	Socio-cultural factors
+ Consumer preferences: Each region has different cultures, customs, and practices, leading to differences in consumer preferences.
+ Shopping habits: Some regions have a tradition of shopping directly at stores, while others are accustomed to online shopping.
+ Age and gender: Different population structures between states will lead to differences in needs and shopping behaviors.

3.	Market and competition factors
+ Presence of e-commerce platforms: Large e-commerce platforms often focus on investing in potential markets, creating competition and promoting growth.
+ Promotion and marketing policies: Effective promotion and marketing programs will attract customers and increase sales.
+ Payment methods: The development of online payment methods will facilitate online shopping.





###### 5.2.TREND BETW

  ![](images/nam1234.jpg) 

- Overall Trend and Regression Line Analysis
    This Scatter Plot shows a weak positive correlation. The blue regression line is slightly pointed upwards, indicating that for 
    increasing amounts spent, the profit also does an uptrend but not with constancy and strength.
    Here, the points are extensively scattered, indicating that other factors such as product type or pricing strategy do play a role in 
    setting the profit margin.
    The R-square value, if computed, would be comparatively low, an indication that expenditure on its own does not explain much of the 
    variation in profit.

1. Profit Trend Across Segments
Electronics-Red points:

    The electronics transactions have a wide range from low to high amount and profits are very volatile.
    Some of the electronics orders had negative profits, meaning below the zero of the Y-axis; this could imply pricing strategies like 
    discounts, promotions, or bundled offers.
    A small portion of the orders for electronics result in very high profits over 1000 units, which again points to the likelihood that 
    expensive orders for high-end devices or accessories bring in large returns.
    Furniture Gray points:
    
    Like electronics, furniture orders do have a wide range in their quantity, but there are more outliers in terms of very high quantities 
    above 2000. This reflects the fact that large purchases of furniture items, such as sofas or desks, tend to be costlier.
    It can be observed that the range of profit is very wide, with many large profits (> 1000) existing. These can be from high-margin 
    items or customized furniture pieces.
    Losses for small and medium-sized transactions cluster together; this may be due to logistics costs or discounts.
    Clothing (Blue points):
    
    Amounts and profits from clothing transactions tend to be low. This is due to typical retail trends where purchases of clothing are low 
    in amount and yield low profits.
    Most points are closely bunched between 0 to 500 in amount and -500 to 500 in profit. The variance compared with other categories may 
    be so small because of the standardized pricing and low margins in the clothing retail business.

2. Losses and Negative Profit Orders
    Several points below the zero profit line reveal that the orders resulted in losses.
    These are more frequent in electronics and furniture transactions; presumably because of high operating costs or heavy discounts, even 
    returns of merchandise.
    In the case of clothing, there are fewer losses, which could indicate that pricing strategies or inventory control might be better for 
    this category.

4. Outliers and Extreme Values
    Outliers appear in both profit and amount:
    For Furniture, a couple of points have values greater than 2000 with profits over 1000; these correspond to large or custom orders that 
    have disproportionately high profit margins. Electronics also shows some outliers, suggesting there are sometimes large-ticket items  
    that generate unpredictable profitability.

     5. Implications and Business Insights Furniture :
        
    indeed generate both super-high profits and huge losses, thus underpinning the importance of managing inventories and logistics related 
    to big items effectively.
    High variability in both profit and amount for Electronics suggests that product mix, discounting strategies, and customer demand are 
    key in profitability. 
    Clothing profits are consistent but smaller, reflecting a more predictable and stable business model with fewer large outliers or 
    extreme losses. 
   Conclusion and Recommendations
    The margin in electronics and furniture orders is somewhat volatile; therefore, there is the emergence of loss-making transactions. 
    Perhaps dynamic pricing or special bundle offers would keep profitability good.
    Clothing has more stable margins but may be improved by upselling strategies that increase the transaction amount.
    Overall, the weak positive correlation suggests that it cannot be stated with certainty whether increasing order amount alone 
    guarantees 
    increased profits. Rather, product mix, operational efficiencies, and pricing strategies hold the key to maximization of profits by the 
    owners of the businesses.
    



###### 5.3.DISTRIBUTION OF CATEGORY

 ![](images/category.jpg) 
 
 Overview:
• Clothing is clearly dominant, reflecting strong customer demand for fashion products.

• Electronics has a medium share, reflecting stable demand, but not as dominant as clothing.

• Furniture is the category with the lowest demand, possibly due to the product's high cost and infrequent purchase characteristics.

Analysis by Category
1. Clothing - 63.3%
• Dominance: With 63.3%,This shows a strong focus on fashion product Because fashion is often a necessity, abundant, and diverse, leading to high consumption. In addition, the seasonal factor and frequently changing fashion trends also encourage consumers to shop more.This also suggests that if businesses want to increase profits, they can consider adding new product lines or special promotional campaigns for clothing.

2. Electronics - 20.5%
• Average rate: Although not as high as Clothing, 20.5% is still a significant rate, showing that electronic devices have a stable demand in the market.Because electronic products are often high-value and feature constantly upgraded technology. Customers do not buy these products very often, but when they do, they are willing to pay more. This reflects the development of devices such as phones, computers, and technological home appliances.
Electronics is a highly profitable field due to stable demand and often high order values. Businesses can consider developing new technology products or other electronic products to meet the diverse needs of customers.

3. Furniture - 16.2%
• Lowest percentage: At only 16.2%, Furniture is the least popular category among the three, possibly due to the nature of the product. Because furniture is often high-value and does not need to be purchased frequently, resulting in fewer orders than products such as clothing. In addition, furniture purchases are often tied to long-term needs or special occasions such as moving house or renovating a living space.
Although demand may seem low, furniture is still a category that can be highly profitable due to large order values. Businesses can target high-end customers or expand into smaller, more easily consumed interior decoration products.

Conclusion
This chart not only shows the distribution of orders across categories but also provides insight into market demand and customer shopping behavior. Businesses can use it to adjust their business strategies, focusing on high-demand categories such as clothing, while maintaining a presence in other categories to serve the diverse needs of the market.

   
###### 5.4.DISTRIBUTION OF SUB-CATEGORY

 ![](images/subcategory.jpg) 

The chart shows:  

Quantity: Each column in the chart represents the product names belonging to a particular sub-category.

Sub-category: The sub-categories are shown from left to right in decreasing order of quantity.

Sub-Category Distribution:
Saree is the most frequent sub-category, followed by Hankerchief and Stole.

Tables and Trousers are the least frequent sub-categories.
Data Points:
The chart shows the distribution of sales across various sub-categories.

The y-axis represents the count of sales for each sub-category.

The x-axis lists the categories in descending order of frequency.
Insights:
The company appears to be selling a wide range of products, with a heavy focus on apparel and accessories.
• Sarees are the most popular item, indicating a potential and essential market demand for this product.

• Handkerchiefs and scarves also have a significant presence, indicating a potential market in these items.

Tables and Trousers have the lowest sales, which could indicate potential areas for improvement in marketing or product offerings.

Additional Considerations:
It would be helpful to overlay this chart with trends.

Analyzing sales data alongside other metrics and factors such as revenue, benefits, and customer demographics can provide additional insights and insights.

Recommendations:
Focus on promoting Sarees, Hankerchiefs, and Stoles to capitalize on their popularity and provide items that customers need.

Conduct market research to identify the reasons for low sales of Tables and Trousers.

Consider diversifying the product range or implementing targeted marketing strategies for these sub-categories.

###### 5.5.DISTRIBUTION OF PAYMENT MODE

![](images/ảnh2.jpg)

-COD (Cash on Delivery):
Observation: COD is most popular paymentmode

Relationship with Amount and Category:In Clothing and Electronics category, COD is frequently employed in low to middle market segments. This is probably because COD type transactions are risk ,  people may also be wary to utilize them to purchase high value items for reasons of safety 

-UPI (Unified Payment Interface):
Observation: UPI is the second most practice payment mode, as its number of transactions is significantly high.

Relationship with Amount and Category:UPI may be generally deployed while making medium range purchases in the Furniture and Electronics categories as it is simple and safe. It is possible that high valued transactions via this method are less frequently used as a result of transfer limitations or security issues for bulk amounts.

-Debit Card:
Observation: Debit Card is moderately popular nowadays but less use than UPI or COD.

Relationship with Amount and Category:UPI is expected to have lower average spending amounts as compared to than Debit Cards even in Categories like Furniture. When UPI limits set are too low, but the cost of the intended purchase can be paid in one sitting then it will be preferred.

-Credit Card:
Observation: The observation in respect to Credit Card is the same as that of Debit Card.

Relationship with Amount and Category:Credit Card  also be used in case of customers making higher value purchases in the category of Electronics. Possibly the combination of credit and reward points could be a reason for usage especially for individuals who foresee that at the time of purchase they would not be able to make the payment.

-EMI (Equated Monthly Installments):
Observation: EMI is one of the least popular forms of payment.

Relationship with Amount and Category: There may be more instances of EMI in Electronics or Furniture goods. The average order amounts per transaction using EMI are larger than per transaction amounts made using other payment modes because’s EMIs are for high cost produmets.



# 6.CONCLUSION


# 7.REFERENCES
    
     [https://www.kaggle.com/datasets/samruddhi4040/online-sales-dataGithub](
                  
                                                         
