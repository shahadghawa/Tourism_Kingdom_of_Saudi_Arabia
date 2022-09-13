# Tourism_Kingdom_of_Saudi_Arabia
<img width="1512" alt="Screen Shot 1444-02-12 at 1 13 07 PM" src="https://user-images.githubusercontent.com/94755943/189503586-5d19cc99-a07d-4528-8aef-5b9ac904a7d4.png">


# Intro:
Problem Statement: Tourism development is an important driver of growth for the future of Saudi Arabia. It is one of the key pillars at the heart of Vision 2030’s plan to help diversify the economy and reduce reliance on oil. Ministry of Tourism in Saudi Arabia is playing huge role to achieve The Kingdom of Saudi Arabia’s 2030 Vision.<br />
It is part of Quality of Life program which was launched in 2018 to improve the quality of life of residents and visitors to the Kingdom by developing the necessary environment to create more vibrant options that enhance the participation and experience of citizens and residents.


# The goal of the case study:
Building Classification model to study the state of Riyadh city in quality of life program, is Riyadh in the right path to achieve the Kingdom’s vision? or more work and efforts are needed?<br />
We studied many aspects of hotels in Riyadh to have a comprehensive visualization of hotels status. <br /> The classification models will help the Ministry of Tourism to predict if the specific hotel is meeting the standards or not, and the results of models will assist the ministry to improve the tourist experience.


# Datasets :

1- Statistical data from the Ministry of Tourism <br />
2- Web scrpaing of TripAdvisor website <br />
3- Web scrpaing of Booking website

# Preprocessing :
We had to deal with the dataset separately and clean it in each sector 

# The file guides :
1-ThingsToDoRiyadh.csv : Web scrpaing of TripAdvisor for Thing to do in Ryiadh <br />
2-Final_activity.ipynb : Preprocessing and eda for the thing to do in Ryiadh <br />
3-RUHResturant.xlsx :  Web scrpaing of TripAdvisor for restaurant in Ryiadh <br />
4-RUHResturnat_cleaning.ipynb : Preprocessing and EDA for the restaurant in Ryiadh <br />
5-RUHResturant_Dataset : The dataset for restaurant After cleaning in Excel <br />
6-WebScrapingBooking.ipynb : Web scrpaing of Booking For Riyadh city <br /> 
7-RiyadhHotelBooking.xlsx : Dataset from wep scrpaing <br />
8-BookingHotelsPreProcessing.ipynb :  Preprocessing for the Booking website <br />
9-BookingDashbord : Dashboard in python for Booking  <br />
10-Booking_ML.ipynb : Machine Learning ( Classification Algorithms) <br />


# Results :
The first version of the dataset was very limited, we forced to do another web scraping to have additional layer of information that makes effects in Exploratory Data Analysis, and Classification models.

We then made classes for the continuous columns, after that, transformed them into dummy variables.

In the machine learning models, we directly used Random Forest and XGBoost and built 8 classification models, because they usually provides us the highest accuracy and better predictions.

The best results out of these 8 is:<br />

1- Predict type of review rating (ReviewRatingVec column) using XGBoost<br />

Accuracy: 0.95 <br />
2- Predict class of residence (Starsvec column) using XGBoost <br />

Accuracy: 0.95 <br />
# Future work :

1- Using regression models to predict the price of the hotels based on the season, class of residence, customers reviews, location, distance to airport . <br />

2- Deploy the models. <br />


# Recommendations:
1 - Utilization of digital transformation. <br />
2 - Focusing on trending applications and international websites. <br />
3 - Motivate the tourist places to activate their accounts on the related platform. <br />
4 - Motivate Evaluation Culture. <br />

