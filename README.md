                                   INTRODUCTION TO DATA SCIENCE
                                                            -Lecturer:EMANUELPLAN

                                    REPORT-GROUP 9 :TOPIC BASKETBALL 🏀

  ![](images/nab2.jpg)  

  Members of group:🎱
  
                              |Họ và Tên| MSV | 
                              |--------------   |-------|
                              | ĐẶNG TRỌNG NAM  | 22080331 | 
                              | ĐINH LÂM PHƯƠNG | 22080337 | 
                              | HÀ NGỌC ANH     | 22080294 | 
                              | TRẦN KHÁNH LINH | 22080324 | 
                              | HOÀNG QUỐC BẢO  | 22080304 | 
                              | NGÔ TIẾN HUY    | 22080319 | 
                  

# 1.INTRODUCTION 
 
  -The "NBA Player Statistics Since 1950" dataset is sourced from Kaggle, the dataset includes detailed statistical data for NBA players including: player name, starting year, ending year,position, height, weight, date of birth and college the players attended
                                  
## 2..PLAYER SET CREATION

  ![](images/chart5d.png)      

    
  name: The name of the player.

  year_start:  The year they began playing in the dataset.
  
  year_end:    The year they stopped playing in the dataset.
  
  position: The positions that players typically occupy 
  
  height: The height of players 

  weight: The weight of players .
  
  birth_date: The birth dates of players
  
  college: Indicates the colleges that players attended

## 3.ANALYSIS CONSIDERATIONS📌

-Career longevity: By looking at "#year_start - #year_end", that can analyze trends in player longevity and how it has changed over the years.

-Position trends: The position column allows you to understand how a player's role has evolved in the sport, which can then be used to analyze trends in the average height of each position

-Physical attributes: Height and weight can be analyzed to determine whether there are optimal physical characteristics for specific positions or overall performance.
           
## 4.WHAT CLEANING DATA 

-Handling Missing Values: Remove or impute missing data in critical columns (like school, position, height, weight, etc.)

-Removing Duplicates: Remove any duplicate player records.

-Filtering: Select players, or teams relevant to the analysis


# 5.COMPARATIVE ANAYLYSIS 📊

 ###### 5.1.WEIGHT

 ![](images/NAM3.png)  

-This chart shows the average weight of NBA players throughout the years. It's divided by position—Guards (blue), Forwards (green) and Centers (red). This pattern reveals how 
 different roles demand different body types

 -Upward trend over time: all three positions show a general increase in average weight from 1945 to 2015. This reflects changes in training and nutrition, but also the evolving 
  physical demands of the NBA.

 -Centers consistently heaviest the red line for Centers shows that players in this position have always been the heaviest. Centers often need a larger frame for rebounding and 
  defending the paint. The significant changes in weight over the years also reflect the intentions and strategies of the team at different times.

 -Weight of Guards remains the lowest Guards show a slow increase in weight over time, however, they stay the lightest position on the timeline. This is expected, because guards 
  depend more on speed and agility than on size.

 -The weight of the Forward position has changed significantly from 1945 to 2015. However, it generally remains stable at around 90-100 kg due to the need for balance between offense 
  and defense.

###### 5.2.HEIGHT  

  ![](images/NAM1.png) 

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

# 6.FINAL THOUGHTS

This chart shows the physical diversity within the NBA by position. It highlights how body size plays a big role in deciding a player’s position.However, there are still exceptions that differ from the majority, showcasing the diversity and uniqueness of the NBA.

SOURCES
 
     https://www.kaggle.com/drgilermo/nba-players-stats?select=player_data.csv
      ĐINH LÂM PHƯƠNG-22080337
  
                     ĐẶNG TRỌNG NAM-22080331
                     
                     NGÔ TIẾN HUY-22080319
                     
                     HOÀNG QUỐC BẢO-22080304
                     
                     HÀ NGỌC ANH-22080294
                     
                     TRẦN KHÁNH LINH-22080324
                

   
                  
                                                         
