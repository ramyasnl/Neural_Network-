## Module 19 Challenge Deliverable 4: A Written Report on the Neural Network Model
## Overview of the analysis
Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! </br>
Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.</br>

With our knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.</br>

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. </br>Within this dataset are a number of columns that capture metadata about each organization, such as the following:</br>

EIN and NAME—Identification columns</br>
APPLICATION_TYPE—Alphabet Soup application type</br>
AFFILIATION—Affiliated sector of industry</br>
CLASSIFICATION—Government organization classification</br>
USE_CASE—Use case for funding</br>
ORGANIZATION—Organization type</br>
STATUS—Active status</br>
INCOME_AMT—Income classification</br>
SPECIAL_CONSIDERATIONS—Special consideration for application</br>
ASK_AMT—Funding amount requested</br></br>
IS_SUCCESSFUL—Was the money used effectively</br>

## What We Are Creating</br>
This new assignment consists of three technical analysis deliverables and a written report.</br> 
Deliverable 1: Preprocessing Data for a Neural Network Model</br>
Deliverable 2: Compile, Train, and Evaluate the Model</br>
Deliverable 3: Optimize the Model</br>
Deliverable 4: A Written Report on the Neural Network Mode</br>
## Results </br>
## Deliverable 1: Preprocessing Data for a Neural Network Model</br>
### Data Preprocessing</br>
1.Variable considered as the target for your model y=application_df["IS_SUCCESSFUL"],</br>
2.Variable(s) that are considered to be the features for your model X = application_df.drop(["IS_SUCCESSFUL","SPECIAL_CONSIDERATIONS_N"]</br>
3.Variable , neither targets nor features, and should be removed from the input data "SPECIAL_CONSIDERATIONS_N"</br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d1.png)</br>

## Deliverable 2: Compile, Train, and Evaluate the Model</br>
Number of  neurons, layers, and activation functions used for our neural network model,</br>
1.number_input_features = 42, hidden layer1 =80, hidden layer 2 = 30 , relu,relu,sigmoid as activation function </br>
2.number_input_features = 42,hidden_nodes_layer1 =  70,hidden_nodes_layer2 = 40,hidden_nodes_layer3 = 30,relu,relu,relu,sigmoid as activation function </br>
3.number_input_features = 42,hidden_nodes_layer1 =  80,hidden_nodes_layer2 = 50,hidden_nodes_layer3 = 40,relu,LeakyReLU,LeakyReLU,sigmoid as activation function </br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d2i.png)</br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d2ii.png)</br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d2iii.png)</br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d2iv.png)</br>
## Deliverable 3: Optimize the Model</br>
This is our optimized model 
number_input_features = 42,hidden_nodes_layer1 =  70,hidden_nodes_layer2 = 40,hidden_nodes_layer3 = 30,relu,relu,relu,sigmoid as activation function </br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d3i.png)</br>
![Alt Text](https://github.com/ramyasnl/Neural_Networks/blob/master/Challenge/images/d3ii.png)</br>
