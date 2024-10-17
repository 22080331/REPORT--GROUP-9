                                   INTRODUCTION TO DATA SCIENCE
                                                            -Lecturer:EMANUELPLAN

                                    REPORT-GROUP 9 :TOPIC BASKETBALL 

  ![](images/nab2.jpg)  
  

 INTRODUCTION 
 
  -The dataset "NBA Players Stats since 1950" is sourced from Kaggle, a well-known platform for data science competitions and datasets. It contains detailed statistical data for NBA
    players, starting from the 1950s to recent seasons. The dataset includes various player performance metrics like points per game, assists, rebounds, shooting 
    percentages, and more. Its purpose is to provide analysts and researchers with a comprehensive view of player performances across different eras of NBA history, enabling 
    comparisons and trend analysis over time
                                  
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

           
HEIGHT ISSUES

   In the dataset, the height information is provided in the format 'feet-inches', where a height of 70 inches would be represented as '6- 
   10', meaning 6 feet 10 inches. Since this format can complicate calculations, I have written the following code to convert these values 
   into the equivalent number of inches.
   
BASIC ANALYSIS

  The goal is to observe changes in the players over the years from 1947 to   2018

 ![](images/chart3b.png)  

 
 COMPARATIVE ANAYLYSIS          
        
  ![](images/chart4.png)  

 LONGEVITY 
   
   Lastly let's attempt to get a sense of whether players who come into the NBA today are staying longer, or exiting quicker than those of  
   
  the 70s to 90s era. To do this however, we must omit players who are still playing, as they do not have a year_end date

 ![](images/chart3c.png) 


**FINAL THOUGHTS**

This dataset serves as a rich resource for sports analysts, researchers, and basketball enthusiasts. Its breadth and depth allow for deep

dives into player performances and the changing dynamics of the NBA. By analyzing this data, one can uncover trends in playing styles, 

individual achievements, and how the league has evolved over time. Whether for academic purposes or fan engagement, the dataset offers a 

robust foundation for NBA-related insights.

SOURCES
 
     https://www.kaggle.com/drgilermo/nba-players-stats?select=player_data.csv
   
                  
                                                         
