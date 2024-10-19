                                   INTRODUCTION TO DATA SCIENCE
                                                            -Lecturer:EMANUELPLAN

                                    REPORT-GROUP 9 :TOPIC BASKETBALL 

  ![](images/nab2.jpg)  

  Members of group:  
                    
                     ĐINH LÂM PHƯƠNG-22080337
  
                     ĐẶNG TRỌNG NAM-22080331
                     
                     NGÔ TIẾN HUY-22080319
                     
                     HOÀNG QUỐC BẢO-22080304
                     
                     HÀ NGỌC ANH-22080294
                     
                     TRẦN KHÁNH LINH-22080324
                

INTRODUCTION 
 
  -The dataset "NBA Players Stats since 1950" is sourced from Kaggle, a well-known platform for data science competitions and datasets. It contains detailed statistical data for NBA
    players, starting from the 1950s to recent seasons. The dataset includes various player performance metrics like points per game, assists, rebounds, shooting 
    percentages, and more. 
                                  
 PLAYER SET CREATION

  ![](images/chart5d.png)      

    
  name: The name of the player.

  year_start: The starting year of the player's career or the year they began playing in the dataset.
  
  year_end: The ending year of the player's career or the year they stopped playing in the dataset.
  
  position: The positions that players typically occupy, with percentages indicating the proportion of players in each position:
  
  height: The height of players, categorized into ranges (e.g., 6-7, 6-8) with the percentage indicating how many players fall into each 
   range.

  weight: The weight of players, possibly indicating distribution across different weight ranges.
  
  birth_date: The birth dates of players, with a histogram showing how many players were born in specific years.
  
  college: Indicates the colleges that players attended, with a percentage showing the proportion of players from a specific college (e.g., 
    University of Kentucky: 7%).

ANALYSIS CONSIDERATIONS
  
  -Career Longevity: By looking at # year_start and # year_end, you can analyze trends in player longevity and how it has changed over the years.
  
  -Position Trends: The position column allows for an understanding of how player roles have evolved in the sport, which can influence team dynamics.

  -Physical Attributes: Height and weight can be analyzed to determine if there are optimal physical characteristics for specific positions or overall performance.

  -Demographic Insights: The birth_date and college columns provide insights into the demographics of the player pool, which can be useful for scouting and recruitment strategies.
    
  Overall, these columns provide a comprehensive framework for analyzing player statistics and drawing insights into performance, career trends, and team compositions.
           
WHAT CLEANING DATA

-Handling Missing Values

-Data Type Conversion

-Duplicate Removal

-Normalization/Standardization

   
BASIC ANALYSIS

  The goal is to observe changes in the players over the years from 1947 to   2018

 ![](images/chart3b.png)  

Normal distribution: The chart shows a nearly normal (bell-shaped) height distribution of NBA players.

Mean value: The average height of the players is in the range of 195-205cm, which is quite high compared to the average height of adults.

Overall: By visually inspecting the histogram, we can estimate that the mean (average) height of the players is around 200-205 cm. This is based on the peak of the distribution being located within this range.

-Considering Relationships

Height and Frequency: The relationship between height and the number of players is shown by the shape of the histogram. As height increases, the number of players initially increases, reaches a peak, and then decreases

The chart shows that height is an important factor affecting the selection and success of NBA players. However, besides height, other factors such as skill, physical strength, and tactics also play an important role in determining the success of a player.
 
COMPARATIVE ANAYLYSIS 

  ![](images/chart4.png) 
  
Overall, the chart reflects the change in the average height structure by position in the NBA over time, in which the height difference between positions is increasingly evident.

The average height of different positions has changed markedly over time: - The average height of larger positions (midfielders and strikers) has tended to increase from the 1950s to the present.

-The average height of the guard position tends to increase slightly.

The height difference between positions is also increasing over time: -From about 15-20 cm in the 1950s, by 2015 the height gap was 20-30cm. -The average forward and striker positions are increasingly higher than other positions. 

The average height difference between locations is relatively stable, with no sudden changes.



LONGEVITY   

 ![](images/chart3c.png) 

Overall, the graph shows an upward trend from 1950 to 2000.

From the 1950s to the 1970s, there was a general trend of average career length decreasing, from over 4 years to under 4 years.

From the 1970s to the 1990s, we saw greater volatility, with clear peaks and troughs, as the average career length changed from around 3 years to over 6 years.

In the 1990s and 2000s, the average career length seemed more stable, fluctuating between 5-6 years.

Although there were many fluctuations, overall it still clearly shows that the career length of players is increasing over the years, showing that players are sticking with their football team for longer periods of time.

**FINAL THOUGHTS**

 By analyzing this data, one can uncover trends in playing styles, 
individual achievements, and how the league has evolved over time. Whether for academic purposes or fan engagement, the dataset offers
a robust foundation for NBA-related insights.

SOURCES
 
     https://www.kaggle.com/drgilermo/nba-players-stats?select=player_data.csv
   
                  
                                                         
