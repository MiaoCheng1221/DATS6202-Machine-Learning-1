# Pokémon Combat

### Introduction:
This data set includes about 721 Pokémon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed.  Based on HP, Attack, Speed, Defense, Special Attack, Special Defense and other features to predict which Pokémon will win the battle.

### Data Source:
Download the dataset from Kaggle, and link is shown below.
https://www.kaggle.com/terminus7/pokemon-challenge/data

### Setup and Run:
* Platform: Anaconda-Juypter
* Package: pandas, numpy, seaborn, matplotlib.pyplot, sklearn
* Run each chunk: Shift + Return

### Methods:
Classification:
* Naive Bayes
* Support Vector Machine
* Random Forest
* K-NN

Prediction:
* Logistic regression: 0.88344
* Naive Bayes: 0.80776
* Random Forest: 0.95184
* K-NN: 0.90376
* Gradient Boosting: 0.94848
* Decision Tree: 0.91552

### Results:
In conclusion, we can say that we were able to predict who the winner could be but failed to predict the type of Pokémon. The reason is that we used four methods to predict the type of Pokémon, but because the accuracy of the four methods are very low, so that we decided to predict whose the winner in the Pokémon’s battle. It was our first time to do a bit of data engineering and use Machine Learning Algorithms and we did encounter with a lot of difficulties but were able to cope with them and get to our result.

### Author
Cheng Miao, Hao Cheng, Rahul Sethi