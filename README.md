# Prediction Model for Final 16 in the FIFA World Cup 2018

![Figure 1-1](https://img.maximummedia.ie/joe_ie/eyJkYXRhIjoie1widXJsXCI6XCJodHRwOlxcXC9cXFwvbWVkaWEtam9lLm1heGltdW1tZWRpYS5pZS5zMy5hbWF6b25hd3MuY29tXFxcL3dwLWNvbnRlbnRcXFwvdXBsb2Fkc1xcXC8yMDE4XFxcLzA2XFxcLzI0MTYzMTM4XFxcL2tyb29zLmpwZ1wiLFwid2lkdGhcIjo3NjcsXCJoZWlnaHRcIjo0MzEsXCJkZWZhdWx0XCI6XCJodHRwczpcXFwvXFxcL3d3dy5qb2UuaWVcXFwvYXNzZXRzXFxcL2ltYWdlc1xcXC9qb2VcXFwvbm8taW1hZ2UucG5nP3Y9NVwifSIsImhhc2giOiI2YWE5YmE4MWE4OGFjMmRiY2VhOWZlNDU4NjhjYjI5ZGFiNDUzYjNhIn0=/kroos.jpg "World Cup 2018")

Data obtained from here : https://www.kaggle.com/agostontorok/soccer-world-cup-2018-winner/data

Previous python notebook here : https://github.com/lppier/fifa18_final16/blob/master/fifa2018.ipynb

New improved model here : https://github.com/lppier/fifa18_final16/blob/master/fifa2018_improved.ipynb

Two datasets were used : 

**Dataset 1 :** A FIFA World Ranking database of all the countries that play soccer competitively. 

**Dataset 2 :** Results of all international soccer matches since 1872.

## Data Preparation

* Only data since the last world cup was used considering the team line-up has changed prior to last world cup
* Only 2018 Rankings was used
* Only World Cup matches' data was used (Qualifers, or otherwise) 
* Data Balancing was done

## Model
* After trying several algorithms, a random forest model was eventually chosen.  

# Improvements in v2
* Matches that drawed are no longer considered as final 16 there is no draw
* One hot encoding is used to remove possibility that model might consider the team number a ranked value
* Added latest results from the new matches so far into the data!

# Updated with Predictions for the Final 16 Quarter-Finals!
![Figure 1-2](https://github.com/lppier/fifa18_final16/blob/master/Quarter_Predictions.png "World Cup 2018")

