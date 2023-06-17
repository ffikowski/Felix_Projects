# Felix' Projects
This side contains some of my study related projects up to January 2023.

# [Bitcoin Price and Tweets (03/23)](https://github.com/ffikowski/Bitcoin-Price-and-Tweets)
- This project has the goal to predict the bicoin price by using tweets containing hash tags like #BTC or #Bitcoin
- First we generate to each tweet a sentiment score by application off the pretrained transformer model finBERT
- Then the mean sentiment score per day is calculated
- This mean sentiment score is used among other variables in a VAR time series model to predict the bitcoin price

# [Text-as-Data (12/22)](https://github.com/ffikowski/Text-as-Data)
- Practical tasks which were part of the course Text as Data
- The first tasks were mainly focused on preprocessing of text data
- The later tasks focused on modelling
- The models were e.g. clustering models, topic models or embedding models


# [Statistics meets Linguistics (01/23)](https://github.com/ffikowski/Statistics-meets-Linguistics)
- This code is partly a result of the equaly named university course "Statistics meets Linguistics"
- The goal is to classify whether a speaker has a singaporean origin or a canadian origin
- The main focus was on the data preprocessing
- The Classification task was solved by a simple Linear Support Vector Classifier


# [GDP Growth Forecast - A Machine Learning Approach (06/22)](https://github.com/ffikowski/GDP-Forecast-Machine-Learning-Approach)
- In this project GDP growth of the U.S. is forecasted through a machine learning approach
- Therefore, different regression trees and a random forest are applied in R
- The data is taken from the FRED data base

# [GDP Growth Forecast - A Vector Autoregressive Approach (05/22)](https://github.com/ffikowski/GDP-Forecast-Vector-Autoregressive-Approach)
- In this project GDP growth of the U.S. gets forecast through a time series analysis approach
- Therefore, different autoregressive and vector autoregressive processes are applied in R
- The data is taken from the FRED data base

# [Blood Preasure Data (12/21)](https://github.com/ffikowski/Blood-Preasure-Data)
- Created and compared were different prediction models in R to predict whether a person has blood preasure or not
- Logistic regression and random forest were the two main modells
- For the random forests the number of trees, maximal depth and the number of variables to possibly split at in each node
- The separation parametes for both models got tuned according to the Accuracy and the ROC curve

# [Big-Data-Analytics - Practical-Tasks (01/22)](https://github.com/ffikowski/Big-Data-Analytics-Practical-Tasks-)
- Practical tasks performed in Python which were part of the course Big Data Analytics
- The tasks were mainly employed to a data set of the game FIFA 2020
- Most steps of the Knowledge-Discovery-in-Databases-Process are captured with focus on Data Mining

# [Petri-Dish Simulation (08/21)](https://github.com/ffikowski/Petri-Dish)
- This is a simulation of a petri dish which is implemented in Python
- The user can determine the size of the dish and also the number of performed time steps
- Three types of bacteria can be placed in the petri dish
- The bacteria are able to perform three actions:
  - Reproduction
  - Movement
  - Destruction of another bacteria

# [Armament-and-Unemployment-Data-Analysis - Bachelor Thesis (09/20)](https://github.com/ffikowski/Armament-and-unemployment-data-analysis)
- Bachelor thesis: Analysis of the connection between the armament industry and unemployment in Germany during the 1930s and 1940s
- Digitalization and preparation through Python (take into account that these are my first steps in coding without any preknowledge)
- Application of a Panel-data regression analysis in R
- Result: The Armament Industry had an signifcant influence on the unemployment figures in the respective cities
