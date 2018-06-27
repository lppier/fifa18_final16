# Prediction Model for Final 16 in the FIFA World Cup 2018

Data obtained from here : https://www.kaggle.com/agostontorok/soccer-world-cup-2018-winner/data

Two datasets were used : 

Dataset 1 : A FIFA World Ranking database of all the countries that play soccer competitively. 
Dataset 2 : Results of all international soccer matches since 1872.

## Data Preparation

* Only data since the last world cup was used considering the team line-up has changed prior to last world cup
* Only 2018 Rankings was used
* Only World Cup matches' data was used (Qualifers, or otherwise) 
* Data Balancing was done

## Model
* After trying several algorithms, a random forest model was eventually chosen. 

## Metrics 
area under curve: 0.7699254768220285
accuracy: 0.7696629213483146
precision: [ 0.78409091  0.75555556]
recall: [ 0.75824176  0.7816092 ]
fscore: [ 0.77094972  0.76836158]
support: [91 87]

## Prediction - Germany vs South Korea
The model predicted that **Germany** would win the match, with 77% accuracy. 
