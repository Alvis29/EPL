# EPL
the purpuse of this project to build a machine learning model on a EPL dataset to predict if the team is going to win the match or not.

## Goals of the Project:

1. Get the dataset by Web Scrapping with Pandas BeautifulSoup framework.
2. Clean the dataset with python and pandas framework.
3. Deal with the missing values if any present in the dataset.
4. Visualize the dataset with various plot types.
5. Get insights from the dataset after EDA.
6. With the help of EDA insights make dataset ready for the model building.
7. Split the dataset into Train and Test data. and prepare train and test data for machine learning model.
8. Try all the base model as well some of the enesemble model on train set and evaluate the model with the help of Sklearn framework.
9. Choose the few better working models with respect to this dataset. na do the cross validation and tunnig the models.
10. Finally check all the tune models on the test dataset and choose the best model for our dataset on the basis of right evaluation.


## Outline
1. Materials and methods
2. General part :   i) Libraries import  ii) Dataset exploration  iii) Deal with missing values iv) Clean the dataset  iv) Visualization with differnt plots  v) getting insights
3. Tasks : i) Web Scrapping ii)EDA iii) model Building.

    
## Materials and methods: 
The dataset was assembled by web scraping from the page : https://fbref.com/en/comps/9/Premier-League-Stats

About this Dataset: 

EPL is assembled dataset of one of the most watched football league (English Premiere League). dataset have over 3800 matches i.e  last 5 seasosns data. This tabular dataset consists of listings of all the matches played from the season2018-2019 to 2022-2023, along with details such as - team name , oppenent name , goals scored,  shot on target , attendance, etc.

## Task
In this project, we will try to fetch information from the WEB and with the help of EDA insights we will build a machine learning model.

1. WEB SCRAPPING

   with the help of python request and BeautifulSoup libraries we will fetch the data from the Webpage 'https://fbref.com/en/comps/9/Premier-League-Stats'.
   and the with the help of python pandas library we will create datframe of the fecthed data.
   

2. EDA

  we will clean the data and doing some basic EDA and visulization plots we will write some insights.

  We will try to answer following quetions :
  
    1. how many no of matches played every month. in last 5 seasons ?
    
    2. which top 4 teams  and bottom 3 teams with most number of goals and least number of goals scored in each of last five season ?
    
    3. top 10 teams with most win percentage and top 10 teams with most loss percentage accross all 5 seasons ?
    
    4. how does possesion affect the Goals scored and Goals concceded?
    
    5.which teams covers more distance on the ground w.r.t teams having more possession or less possession of the ball? how does it affect on result?
    
    6. how shots taken or shots on target affect the result?
    
    7. How does  expected goal ('xga') and expected goal against ('xga') impact the result?
    
    8. How does goals forword ('gf') and goal against ('ga') impact the result?
    
    9. does attendance of supporters affect the result in major way ? can Home venue gives advantage to the team playing in home.?
    
    10. top 5 most used formation in epl ? what are the wining percentage of each formation ?

3. MODEL BUILDING

  with the help of sklearn library we will try to build a model such that it predicts the team going to win a match or not.

  our main objective while building a model was that to choose or build amodel such that accuracy of classifing win or not win category is soomewhat similar (i.e Recall of both  category are somewhat similar).

  machine learning model we tried for the dataset :

    1. LogisticRegression
    2. KnearestNeighbour
    3. SVM
    4. NaiveBayes
    5. DecisionTree
    6. RandomForeset
    7.GradientBoosting

## USED LIBRARIES:
1. NUMPY
2. PANDAS
3. MATPLOTLIB
4. SEABORN
5. PLOTLY
6. SKLEARN
   
