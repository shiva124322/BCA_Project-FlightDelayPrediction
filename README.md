# Flight-Delay-Prediction

<img src="https://aeroclaims.asia/wp-content/uploads/2019/12/flight-delay-compensation-bannenr1.png" width="1000" height="200">

## Introduction
Flight delays pose significant challenges for airlines, airports, and passengers, leading to financial losses, operational inefficiencies, and inconvenience. As global air traffic continues to increase, predicting flight delays has become a crucial area of research. The complexity of the air transportation system, coupled with the vast volume of flight data, necessitates advanced analytical approaches for accurate delay forecasting.

Flight delay prediction involves comparing scheduled arrival and departure times with actual flight data. Researchers have employed various methodologies, including statistical models, machine learning techniques, and data-driven approaches, to improve prediction accuracy. Traditional statistical models, such as linear regression, have been used alongside more advanced methods like deep learning and ensemble techniques.

**Review of Literature:**

Several researchers have proposed models to forecast flight delays using different parameters, including weather conditions, airport congestion, historical flight data, and air traffic patterns. Studies have highlighted the effectiveness of machine learning algorithms like support vector machines, decision trees, and neural networks. However, challenges remain in handling large-scale flight datasets, accounting for multiple variables, and improving prediction accuracy.

Recent advancements have shown that hybrid models combining regression techniques with deep learning can enhance accuracy. Integrating external datasets, such as meteorological reports and air traffic control data, has further improved predictive capabilities. Nevertheless, achieving real-time, highly accurate predictions remains a work in progress. 

To better understand the entire flight ecosystems, vast volumes of data from commercial aviation is collected every moment and stored in databases. Submerged in this massive amount of data produced by sensors and IoT, analysts and data scientists are intensifying their computational and data management skills to extract useful information from each datum. In this context, the procedure of comprehending the domain, managing data and applying a model is known as Data Science, a trend in solving challenging problems related to Big Data. 

In this project, we’ve performed an extensive data analysis in order to extract the important attributes/factors that are responsible for the delay of flight. Also, there will other factors that may influence the delay of the flight such as climate, natural calamities, pandemic, or technical issues, etc. in the airplane which has not been considered in this project as this factors varying depend on the location and such problems occurring have very less frequency. 

## Problem Statement
Flight delays are quite frequent (19% of the US domestic flights arrive more than 15 minutes late), and are a major source of frustration and cost for the passengers. As we will see, some flights are more frequently delayed than others, and there is an interest in providing this information to travellers.

Flight prediction is crucial during the decision-making process for all players of commercial aviation. Moreover, the development of accurate prediction models for flight delays became cumbersome due to the complexity of air transportation system, the number of methods for prediction, and the deluge of flight data. 

Based on data, we would like to analyse what are the major cause for flight delays and assign a probability on whether a particular flight will be delayed. 

## Objective
The objective of the project is to perform analysis of the historic flight data to gain valuable insights and build a predictive model to predict whether a flight will be delayed or not given a set of flight characteristics.

Questions to be answered post analysis: • Does the month of flight have any impact on flight delays? • Flights to which destination have seen the most delays? • Which day of the week sees the least and most flight delays? • Which time of day is most suitable for preventing flight delays? • Which airline has the most number of flights delayed? • What are the primary causes for flight delays?

The objective of the predictive model is to build a model to predict whether a flight will be delayed or not based on certain characteristics of the flight. Such a model may help both passengers as well as airline companies to predict future delays and minimize them.

## Dataset Details
Dataset obtained from Kaggle: <br>
https://www.kaggle.com/lampubhutia/nyc-flight-delay

## Project Design
<img alt="DFD" src="https://user-images.githubusercontent.com/43583040/83272042-4e844f80-a1e8-11ea-99d1-d5f15d114e90.png" width="1000" height="400">

## Technologies Used
* Python
* HTML
* CSS
* Bootstrap
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Flask

**Conclusion**

This prediction not only helps the aviation industry but also the passengers taking a flight. The flight delay also shows the negative reputation of the airline and also thus decreases the reliability of the airlines.The analysis carried here not only predicts delays based on the pervious available data, but also give statistical description of airlines, their rankings based on their on-time performance, the peak hours delays.

<h3>Steps to get started</h3><br>
Clone the repository using: <br>
<code>>> git clone</code> <br>

Setup the virtual environment and turn it on <br>
<code>>> source Flight-Delay-Prediction/bin/activate</code> (For Mac and Linux)<br>
<code>>> .\Flight-Delay-Prediction\Scripts\activate</code> (For Windows) <br>

Run the script<br>
<code>>> python app.py</code><brt>
**Development of website**
<code>>> http://127.0.0.1:5000/</code>

<br>Contributors <br>
*  Name: S Siva Sankara Chari, 2214503405 <br>
*  Proj Gide: Prof. Mohammed Alisha
