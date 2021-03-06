***
#                                                   Project 1 - MLB ANALYSIS - HOW TO WIN IT ALL!?
***
### Major League Baseball, like other America professional sports, has become a multibillion-dollar industry. The institution free agency had led to the escalation of payrolls and altered the make-up of rosters by dramatically reducing owners "Monopsony Power". The ability of large market clubs such as the New York Yankees to compete continually for the game's greatest prize illustrates the power of the dollar. This project illustrates the salary spent vs the World Series Champions and all other teams among the years from 1985 through 2015 and also shows the main pays and game strategies results on what really gives the winner a way to be the Champion.
--------
## OBJECTIVES:
 #### 1. Compare the Total Salary Spent between the World Series Winners and “Losers”
  
 #### 2. Do the teams that spend the most, win the most?
  
 #### 3. Evaluate spending parameters for the World Series Winners
  
 #### 4. Statistical commonalities between World Series Winners
  
---------

### Data Collection
  * Baseball has a history of statistical analysis
  * Kaggle has a great baseball databank full of csv files
  * Able to read in those csv files, clean, merge, and get to work!
  * Limited scope of analysis to more modern era (1985-2015)
  
  Sample DataFrame
  
 ![alt text](https://github.com/Krla20/Project1/blob/main/Images/1ff44120ab1b151c44a0273583f58291.png)
 ---------
 ***
 ## OBJECTIVES VISUALIZATION
 ***
 ### 1. Compare the Total Salary Spent between the World Series Winners and “Losers”

![alt_text](https://github.com/Krla20/Project1/blob/main/Images/Salary_Spent_Winners_Losers_by_year.png)

####  * Conclusions:
      
      * We can conclude:
        - Some time around 1990 spending became a formidable weapon in the pursuit of a championship
        - By and large, teams that win the championship are spending more than teams that don’t win the championship
      
      * We cannot conclude:
        * We can’t definitively say that you HAVE to spend more than the league average to win a championship
        * Can’t definitively say that spending more money will GUARANTEE a championship
----------
### 2. Do the teams that spend the most, win the most?

- Analyze further the effect of spending on winning championships
- How often do teams that are top 5 spenders in the league for that year win the championship
- 30 teams in MLB, how often do the top 5 teams (16.67%) win the championship?

![alt_text](https://github.com/Krla20/Project1/blob/main/Images/98f3303699bb4493665502303c4e415b.png)

![alt_text](https://github.com/Krla20/Project1/blob/main/Images/WS_Champs_Top_vs_all_others.png)

####  * Conclusions:
        
        * We can conclude:
          - If an owner is willing to be a top 5 spender, they have about a 50% chance of winning the World Series
        
        * We cannot conclude:
          - Cannot conclude that you have to be a top 5 spender to win
          - Over half of the winners from 1985-2015 were not top 5 spenders

-----------
### 3. Evaluate spending parameters for the World Series Winners
 
 - On average, winners spent .79 STD’s above the mean for that year
    - Spending Formula: Spend Amount($) = Mean Salary + (STD * .79)
Example:
2021 Expected Mean Salary: $150MM
2021 Expected STD: $40MM
$150MM + ($40MM * .79)

- We would recommend the owner spend $181,600,000 if serious about winning!!!

 ![alt_text](https://github.com/Krla20/Project1/blob/main/Images/Salary_WS_Winners_STD_from_Mean_Year.png)
 
####  * Conclusions:
       
       * We can conclude:
          - Winning teams spend, on average, .79 STD’s above the mean salary
          - Spending Formula
        
        * We cannot conclude:
          - Can’t conclude that spending .79 STD’s above the mean will guarantee a championship
          - Spending Formula Problems:
          - How to project Salary Mean and STD in coming years

-----------
### 4. Statistical commonalities between World Series Winners
- Are there statistical commonalities between World Series Champions?
- Can we create a statistical profile of a typical World Series Champion- First we plotted each Champion in comparison with each other
- We found that we were not able to glean much information from this.
![alt_text](https://github.com/grav85/Project1-1/blob/main/Images/so_plot_by_WS_Champs.png)
- Next, we plotted that same data and compared it to every team over the 30 year period
- Here we were able to see how teams compared to all teams and not just champions
- This allowed us to make better observations
![alt_text](https://github.com/grav85/Project1-1/blob/main/Images/WS_Winner_SOAllowed_vs_30_years_breakdown.png)

####  * Conclusions:

        * We can conclude:
         	 - The offensive profile is evenly distributed. 
           - Hits and the ability to steal bases seem to be the best indicator of success.
           - The most important conclusion seems to be that most champions tend to perform in the top 50% of all teams over the 30 years period in every statistical category.
           - It also appears that better pitching is a better indicator of success than offensive stats.
           - ERA and Hits allowed tend to be the best indicator of success.        

        * We cannot conclude:
          	- Team of Destiny Syndrome
           - Ebbs and Flow
           - Cheating
***
> Contributors: Andrey Tokarev, Karla Murphy, Jared Graeve, Simon Feinsilver

> Internet source for csv files: http://kaggle.com/
  
  > CSV Files: https://github.com/Krla20/Project1/tree/main/Resources

> Working file: https://github.com/Krla20/Project1/blob/main/Final_Project_MLB_Analysis.ipynb

> All graph images for all the project: https://github.com/Krla20/Project1/tree/main/Images
