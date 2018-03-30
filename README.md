CoinTrader
=======

My goal with this project was to train a machine learning algorithm to predict the future price of Bitcoin using historical data. The data set used in the project was downloaded from kaggle and is too large to add to the repository. 

![alt text](https://raw.githubusercontent.com/tylermooney86/CoinTrader/master/images/features.png)

I used the data set to classify an SGD classifier using a method similar to the popular stock trading method featured in the book "The Way of the Turtle".

![alt text](https://raw.githubusercontent.com/tylermooney86/CoinTrader/master/images/buysell1d.png)

![alt text](https://raw.githubusercontent.com/tylermooney86/CoinTrader/master/images/SGD.png)

After testing the classifier I created a trading simulator that started with $1000 and used the classifier and bitcoin price data to determine if it was an advantageous time to buy or sell. 

![alt text](https://raw.githubusercontent.com/tylermooney86/CoinTrader/master/images/btctrading.png)

After adjusting the parameters on the classifier and tweaking the training data, my best result from the simulation yielded just over $1 billion after 3 years of simulated trading. Although these results were impressive the real world application would be much different due to trading fees and slow trade confirmation times. For these reasons I do not believe that this approach would be very useful outside of an academic context.
