# Restaurant - Exploratory Data Analysis
During my Data Science internship undertaken at Cognifyz technologies in Jan-Feb 2024, I was given 3 levels of tasks to perform analysis of restaurants and factors affectig its ratings. The main objective was to to gather meaningful insights by conducting exploratory data analysis on the large restaurant dataset, as well as build a ML model to predict ratings.This github repo contains all the files I worked on including the necessary data exploration, preprocessing and various visualization methods to dive deep into finding interesting insights. More details are listed below:

### Tasks
All tasks in details can be found [here](https://drive.google.com/file/d/1vTXJU5eMKMFsmg5R8taLV1k2n9rNWNBj/view?usp=sharing).

### Dataset
It can be downloaded from [here](https://drive.google.com/file/d/16rijnmAWo4IqsobwtaVXQIQYFZhw1Pvv/view?usp=sharing).

### Platform used
Google Colab

### Libraries and Tools used
pandas, numpy, matplotlib, seaborn, scikitlearn, folium, geopanda 

## Data Preprocessing & Feature Engineering
* Cuisines had 9 null values. So dropped the rows 
* Removed features that will inhibit model performance 
* Split training data and test data in the ratio 8:2 
* Some features/columns needed label encoding

## Model Training and Performance
* Used Random Forest, Decision Tree Logistic Regression algorithms to build  the 
models 
* My restaurant rating prediction model (Random Forest and Decision Tree) 
obtained an aggregate R2 score of 0.93 

## EDA : Insights
(level and task wise conclusions are given in repo folders in detail.) 
* There are many restaurants having 0 rating probably due to less popularity. 
* Visualized the geospatial distribution of restaurants on the map coordinates 
using folium and geopanda 
* Most popular restaurants come in the range of ratings 3 to 3.5. 
* Expensive restaurants (higher price range) tend to have higher ratings. 
* New Delhi has the highest number of restaurants. 
* By country, country code “1”, probably North America has most no of 
restaurants.   
* 'North Indian' is the most popular cuisine overall, followed by "Chinese" and 
"fast food". 
* Restaurants having table booking facility have fairly higher average rating. 
* “Sunda” is the highest rated cuisine and also has the most votes. 

## Some visualizations for reference
  ![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/955223f3-3c28-4027-aa0b-74ae3e93b6f1)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/996ef9a6-327b-4c53-a560-19016ec9fe0f)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/df299531-addb-4a07-b54b-2b896dc9136a)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/e4f1574a-dfbb-4959-9694-56b8e63215b9)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/f157aa0a-7c6d-439c-82f9-48b4eb18640c)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/9d1a09be-63db-456b-b32b-b73bb7da9594)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/4bdad205-2656-4a67-88b1-32cc6e83b6f2)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/8a3a32c2-7299-4475-8d3a-b2c06252bbf9)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/6eaee4f2-34fc-4ccb-b485-e97b83b21dd6)
![image](https://github.com/galax19ksh/Restaurant-Analysis-and-Predictive-Model/assets/112553872/904992df-bd11-4fd3-8ca8-b40058ce7975)








