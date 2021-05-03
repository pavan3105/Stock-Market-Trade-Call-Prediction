# Stock-Market-Trade-Call-Prediction
In financial markets,taking right trading decisions at right time is the most important thing and of course it is not that easy to predict them.So, so many traders take the suggestions of analysts to take such decisions.
Now,here we are using bollinger bands concept to predict the trade calls.For that purpose we are going to build a SVM classifier which takes the bollinger bands ,close prices of a security as features and trade calls as labels.So,why are we using bollinger bands and close price as the features? Because ,as we discussed in the previous article the trade calls are predicted based on the movement of the close prices with respect to the bollinger bands.So,trade calls depends on both close prices and bollinger bands.
Let us just recap the rules presented in the previous article which we will use to predict trade calls.
 Situation                         Trade Call
Close Pirce<Lower band                 Buy
Close Price>Upper band                 Sell
Lower band<Close Price<Upper band      Hold
