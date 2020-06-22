# fifa-project

Flatiron Module 2 Linear regression Project

# Project Overview

Working with the FIFA 19 video game data, I'll be analyzing, the different aspects of the players game atributes to build a linear regression model that would predicit market value of the players in the top 5 leagues in Europe. The English, German, French, Italian and Spanish leagues.

# Approch

* my process had 6 parts:

* Getting my Data

* Cleaning and analyzing the data using Pandas

* Running Statistical tests on my data using scipy

* Visualizing our insights using Seaborn and Mathplotlib

* Engineering Features for my model

* Fiting my model




## Getting my data 
From Kaggle, I got the fifa 19 game data, complete with all the different attributes for each player.Each row contained each player in the game and the columns contain different information about them.

## Cleaning and analyzing the data using Pandas
I spent sevral hours cleaning the data using Pandas Dataframes and Series to prepare it for analysis. I removed or updated Null values. I group relevating information together and created new columns When necessary. I was able to select a data frame with just the players belonging to the top five leagues in Europe.I  also changed the datatypes of many columns so I could make calculations and comparisions acorss columns. 

## Running Statistical tests on my data using Scipy
I ran sevral statistical test on my data using sciypy. For example,  I ran an ANOVA test to see if the average age was the same accross the different leagues.

## Visualizing our insights using Seaborn and Mathplotlib

I explored my data and provided various visualiztions for the statistical tests I carried out and also to gain more insigt on the factors I considered to have and effect on how much a player is valued.


## Engineering Features for my model

I created new features from the information in my data. I was able to uptain knowlege from the EDA  on things that affect the value of my data. I checked for coorelation and dropped features that were coorelated to the value which is my target varribale. I transformed non linear relationships with my target varriable to better capture a linear relationship so my model would fit accordingly.

## Fiting my model with ols (statsmodels) and sklearn Lasso regressoion 

After all the feature selection, I split my data so I could have a test sample after I fit my model to check its acurracy.
I carried severally fits with ols from statsmodel, Lasso and the ordinary linear regression model form sklearn.
I went on the sepreate my data set to outfield players and Goalkeepers and fit two different models to test for better accuracy.



# Conclusion
I was able to fit my model to R square greater that 0.90 and root mean square error within 0.4 of the standard devation of the test sample, which was a very good model.
