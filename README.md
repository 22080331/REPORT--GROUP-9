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

## 2.BASIC ANALYSIS
![](images/ảnh1.png)                      ![](images/ảnh2.png) 


## 3.ANALYSIS CONSIDERATIONS📌

-Career longevity: By looking at "#year_start - #year_end", that can analyze trends in player longevity and how it has changed over the years.

-Position trends: The position column allows you to understand how a player's role has evolved in the sport, which can then be used to analyze trends in the average height of each position

-Physical attributes: Height and weight can be analyzed to determine whether there are optimal physical characteristics for specific positions or overall performance.

           
## 4.WHAT CLEANING DATA 

-Handling Missing Values: Remove or impute missing data in critical columns (like school, position, height, weight, etc.)

-Removing Duplicates: Remove any duplicate player records.

-Filtering: Select players, or teams relevant to the analysis


# 5.BASIC ANAYLYSIS 📊

###### 5.1.WEIGHT  

 ![](images/)  

COD (Cash on Delivery):
Observation: COD ranks high on the popularity scale as it was utilized for nearly 700 of the transactions made.
Possible Reasons: Customers who are unsecure by insecurity about either a good or a retailer frequently prefer to pay on delivery as they can always check out what they want to purchase before making any payment.
In Clothing and Electronics category, COD is frequently employed in low to middle market segments. This is probably because COD type transactions are risk ,  people may also be wary to utilize them to purchase high value items for reasons of safety 

UPI (Unified Payment Interface):
Observation: UPI is the second most practice payment mode, as its number of transactions is significantly high.
Possible Reasons: UPI is cost effective since it involves low or none transaction costs and it is quite efficient for making smaller and fast . UPI may be generally deployed while making medium range purchases in the Furniture and Electronics categories as it is simple and safe. It is possible that high valued transactions via this method are less frequently used as a result of transfer limitations or security issues for bulk amounts.

Debit Card:
Observation It was noted that though a Debit Card was used, it is not the preferred method compared to UPI or COD.
Possible Reasons: It is possible to theorize that some customers do not like to utilize debit cards too often for security reasons, so they will likely use UPI and other secure methods such as the Cash on Delivery.
Consumers may view Debit Cards as an alternative form of payment, offsetting the spending amount lower than UPI on average. However, this is particularly true in instances where UPI limits the purchasing power but the total value is modest enough to enable a single transaction.

Credit Card:
Observation: Usage of a Credit Card is not much different from that of a Debit Card.
Possible Reasons: It must be noted that a sizable portion of the purchase made with a Credit Card comes with either some rewards, cash back or installments and thus offers great value to slightly higher-value items. Nevertheless, they may be avoided for minor or routine transactions to avoid debt accruements.
It is probable that customers may utilize Credit Cards generally for their higher value purchases, more so electronics. It is possible their usage may be driven by the credit available as well as their reward points for purchases where payment cannot be made immediately.

Debit Card:
Observation: Debit Card is moderately popular nowadays but less use than UPI or COD.
Possible Reasons: Some customers do not feel very inclined to use any debit cards because of security issues, hence would rather do UPI or pay cash on delivery.
 UPI is expected to have lower average spending amounts as compared to than Debit Cards even in Categories like Furniture. When UPI limits set are too low, but the cost of the intended purchase can be paid in one sitting then it will be preferred.

Credit Card:
Observation: The observation in respect to Credit Card is the same as that of Debit Card.
Although Credit Cards offer good rewards/cash back or pay in installments, they are still only beneficial if the purchase value is low and so paying for smaller or routine transactions will not build up debt.
 Credit Card may also be used in case of customers making higher value purchases in the category of Electronics. Possibly the combination of credit and reward points could be a reason for usage especially for individuals who foresee that at the time of purchase they would not be able to make the payment.

###### 5.2.HEIGHT  

  ![](images/ảnh1.png) 

-Normal distribution chart

-The histogram chart analyzes the average height trend of NBA players by position, with the height difference between positions becoming more and more pronounced.

 -Center: The height distribution graph of the Center is skewed to the right, indicating that most players in this position are above average in height.

 -Forward: The height distribution graph of the Forward is quite symmetrical, indicating that the height distribution of players in this position is relatively even.

 -Guard: The height distribution graph of the Guard is skewed to the left, indicating that most players in this position are below average in height.


###### 5.3.RELATION OF WEIGHT AND HEIGHT

 ![](images/NAM5.png) 

-This chart shows how height and weight relate among NBA players, divided by their positions—Guards are faster, Forwards are versatile and Centers are strong.There’s a positive link between height and weight. As height goes up, weight usually goes up too for all positions, creating a clear upward trend. 

 -Distinct Position Clusters: guards (blue) are usually shorter and lighter; they tend to cluster on the left side of the chart. Forwards (green), however, have a wider range: they 
  appear between 190–210 cm and 80–120 kg. This shows a balance between size and agility, but centers (red) dominate the upper right side. They are the tallest and heaviest players 
  because their physical requirements are crucial for playing near the basket. 

  -Overlap between Positions: there’s a bit of overlap between Forwards and Centers, especially at heights of about 195–210 cm and weights around 90–120 kg. This means that some 
   players can take on either role. However, it really depends on the team’s needs and the skills each player brings to the table. 

  -Greater Variability in Heavier Positions: centers show a larger spread in weight ,some players even exceeding 140 kg. This suggests a wider range of body types in that position, 
   however, it could also reflect the style of play each season. Although the playing style has changed, the central position still requires good physical stature.

  -Guards with Outliers: there are a few Guards that are notably heavy for their height. This hints at outliers, however, they might have unique physiques or playing styles. Although 
   some might think this is unusual, it can actually be an advantage. Because of their weight, they can hold their ground better during games, but it's not just about size.

# 6.CONCLUSION

This chart shows the physical diversity within the NBA by position. It highlights how body size plays a big role in deciding a player’s position.However, there are still exceptions that differ from the majority, showcasing the diversity and uniqueness of the NBA.

SOURCES
 
    
     [Github](https://github.com](https://www.kaggle.com/drgilermo/nba-players-stats?select=player_data.csv)
   
                  
                                                         
