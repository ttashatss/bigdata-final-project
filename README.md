# bigdata-final-project
# Restaurant Satisfaction Prediction

### Purpose
The purpose of this project is to analyze and predict my satisfaction towards the restaurants in order to study my food 
consumption pattern and restaurant preference

### Background
Being an indecisive person, I have always had problems with deciding which restaurant I would like to dine in in each meal. 
My decision making process can take up to hours before coming into conclusion, yet I may not be satisfied with the restaurant 
I selected. Moreover, as my family of four always have meals together, choosing restaurant is always a burden since we all 
want to go to a place that will satisfy all of us. This project is purposely designed to evaluate whether I will be satisfied 
with the restaurant or not based on the restaurant data and my personal opinion in order to reduce the time wasted to deciding 
restaurants.

### Research Scope
This project includes only restaurants that I am familiar with in my regular daily routine. This project does not include 
restaurant to be chosen on vacation trips.

### Research Questions
#### Food Consumption Pattern Analysis
1. What cuisine shows the largest number of satisfied and unsatisfied restaurant?
2. What price range shows the largest number of satisfied and unsatisfied restaurant?
3. What is the keywords that leads to positive and negative opinion?
#### Satisfaction Prediction
1. What factors significantly affect my satisfaction towards a restaurant?

### Methodology

#### Natural Language Processing using 2-Layer-LSTM Model
Opinion is one factor to affect the satisfaction towards the restaurant. However, opinions are in words and cannot be put into 
a classification model as the input. To resolve this, using the natural language processing (2-layer-LSTM model), opinions can 
be classified into sentiment – ‘positive’, ‘neutral’, and ‘negative’ which then can be assigned to value of 1, 0, -1 respectively 
and can be put into a classification model afterwards.

2-layer-LSTM model is the most suitable for the sentiment prediction because of its advantage in memorizing text patterns. Also, 
its bidirectional wrapper helps with propagating the input in both forward and backward directions providing higher model accuracy.


#### Logistic Regression Model
In order to show the factors that have large impact on my satisfactory, logistic regression model is used to classify the 
restaurants into 2 classes – restaurants that will be satisfied and restaurants that will be unsatisfied. Logistic regression method 
is chosen because its ability to determine the coefficient of each input which is related to the importance of the input on the 
prediction result. Moreover, the model is used to predict whether I will be satisfied with the restaurant based on the provided data 
of the restaurant. 


