# Analysis of Airline Data

## Team Members: Mukund Kalantri, Reid Glaze, and Rohit Kharat

## Project Description: 
In this project, we have airline data taken from approximately 2 million US domestic flights and analyze the delays and cancellations of these flights. We aimed to answer the following questions:
- Which airports should be focused more on infrastructure development to mitigate the frequency and severity of delays?
- What are the relationships between airline carriers and flight delays/cancellations?
- What are the most common reasons for flight delays based on airports?
- What are the relationships between days in a week or times in a day when there are a lot of cancellations and delays?

Additionally, we build a prediction model that will be used to calculate the arrival delay for a flight based on the other attributes. The customers and the airport authorities could directly use this. We also build several classification models to predict the reason for cancellations of flights based on the attributes provided by the dataset.

## Summary of Key Results: 
For our first question, we found out which airports we should focus on infrastructure development concerning carrier and aircraft delays. This information will help us to mitigate the frequency and severity of delays for passengers. The solution for the second question was found by which airlines have the most percentage of their flights delayed during departure and arrival based on different delay times. For the third question, we found the most common reasons for delays in flights based on origin airports, origin state, and airlines. The analysis was done to find the top 10 candidates which cause the delay in flights, so that information will help make informed decisions about which airlines and airports should be preferred. For our last question, we determined which times are optimal for consumers to purchase a flight to minimize the probability of delays.

We tried to build two types of prediction models. The first one was a Multiple Linear Regression model and the second one was a Neural Network. We concluded that the neural network was much better at predicting flight delays and the predicted values were much closer to the actual values. These predictions could be further improved with additional data and a more complex model. Neural networks did the best task in prediction of flight delays with mean absolute difference value of 14.7

Multi-classification models were built to classify or predict the reason for cancellations.  The models which we built for this task were decision tree, random forest, AdaBoost classifier, extra trees classifier, gradient boosting classifier, XGBoost, Naive Bayes, and logistic regression. Among these models, we got the highest classification metrics values for the random forest classifier, followed by the extra trees classifier. We got highest classification metrics (accuracy, precision, recall, F1 score) of 0.84 from random forest classifier. 

## Application: 
Our project can help with a lot of real-world applications. Our findings related to the delay in flights because of airports will help the airports with poor performance improve their services. Having good performance would also help these airports in terms of business as the airlines and the passengers would prefer more to travel via these airports.

The results where we see the airline carrier performance in terms of delays will force the poor performing airlines to improve their services otherwise it would have a big impact on their business. These results also help the passengers to select better and more reliable flights.  

We have also done an analysis of the reasons for delays at each airport which again would help the airport authorities to see what could be done to have better flight operations.

Our detailed analysis of delays based on the day of the week or time in a day would be more helpful to the customers when they are booking flights, as they can update their travel plans while considering the possibility of delays.

The classification model will serve the purpose of providing the reason for the cancellation of a flight to the airport authorities. This information can be shared by the authorities with the customer and can make an informed decision about the flight. This will also help in diverting a flight to a safer airport based on weather, national security, or any other issues. This knowledge will lead to help the airport as well as airline authorities to prevent losses incurred due to the cancellation of flights. Also, the customer will be provided with prior updates on the flight status. 

The prediction model although not extremely efficient, gives decent predictions about the delays.  Our experiments show how neural networks can be used in a more efficient way to make a very efficient and reliable delay predictor which could be eventually incorporated into airports’ and airlines’ websites and mobile applications. This would make it very helpful for the customers to chart out their travel plans with consideration of flight delays.

## Link to the video demonstration: 
https://drive.google.com/file/d/1tFNXBeGWgvO279kmX0j8H3mXri9UwV8C/view?usp=sharing

## Link to our final project paper: 
https://drive.google.com/file/d/1-1LUKGP2DKAdC8t3_b0wWjrclRyfEODE/view?usp=sharing
