# Yes-Bank-Stock-Price-Prediction.
![images](https://user-images.githubusercontent.com/88246578/166191402-282abd5e-e767-4033-a3b4-5a86561003b5.jpg)




Capstone Project -Supervised Learning (Regression)
Our problem statement -Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month

Our main motive of the project was to predict the stock's closing price of the month. To determine the YES bank's stock’s future value on the national stock exchange. The advantage of a successful prediction of a stock's future price could results insignificant profit. The efficient-market hypothesis recommends that stock costs mirror all right now accessible data and any value changes that are not founded on recently uncovered data subsequently are an unpredictable. We have to build model which help us to predict the future stock prices.
The stock market is known for being volatile, dynamic, and nonlinear. Accurate stock price prediction is extremely challenging because of multiple (macro and micro) factors, such as politics, global economic conditions, unexpected events, a company’s financial performance, and so on. But, all of this also means that there’s a lot of data to find patterns in. So, financial analysts, researchers, and data scientists keep exploring analytics techniques to detect stock market trends. This gave rise to the concept of algorithmic trading which uses automated, pre-programmed trading strategies to execute orders.

The Challenge we face is due to small dataset so it’s difficult to get good model accuracy

In EDA part we observed that

1) There is increase in trend of Yes Bank's stock's Close price till 2018 and then sudden decrease.

2)There is increase in trend of Yes Bank's stock's Open price till 2018 and then sudden decrease.

3)We observed that open vs close price graph concluded that after 2018 yes bank's stock hitted drastically.

implementing all model we get accuracy.

1)KNN regressor with highest accuracy - 92.00%

2)linear regression accuracy - 82.00%

3)SVM regressor accuracy - 79.00%

Overall, we can say that K-Neighbors Regressor is the best model among all regression model which gives around 92.00% accuracy of predicting stock price of our dataset.
