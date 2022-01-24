# Bitcoin Price Prediction with 2D Convolutional Neural Networks

---

### Abstract

This thesis aims to test an innovative and untested approach to classify the price of Bitcoin in a way that can later be used on algorithmic trading scenarios. A binary classification approach is preferred, instead of the more widely applied regression approach, to ease the prediction task. This choice is made in accordance with the conceived distribution of the proposed model, which is to be employed within a trading algorithm. The Bitcoin Financial Time Series task is approached similarly to a computer vision problem, leveraging a 2D Convolutional Neural Network. The data include not only the Bitcoin price data, but also Bitcoin on-chain features and metrics. On this data technical indicators are measured to increase the number of time series, which are made stationary by fractional differentiation. The time series are transformed into images using recurrence plots, and used to train the 2D Convolutional Neural Network as a standard image classification problem. On the test set, the proposed model reaches a Macro F1-score of 58%. According to a Financial Evaluation, the returns of the proposed model based algorithm exceed the bitcoin Buy-and-Hold by 7.88% with a 38.95% increase in the sharpe ratio. The performance of the proposed model are also compared with a k-Nearest Neighbors (k-NN) and a Random Forest (RF) classifier. It is interesting how the k-NN, despite being a very simple and intuitive model, was able to outperform the proposed proposed model. In the test set, it achieved a Macro F1-score of 63%. In terms of Financial Evaluation, it also achieved the best results, outperforming the bitcoin Buy-and-Hold by 75.69%, with a sharpe ratio increase of 50.86%.


---

**Read here: [Link](https://github.com/jerryfane/bitcoin-price-prediction-with-2d-cnn/blob/main/Bitcoin%20Price%20Prediction%20with%202D%20Convolutional%20Neural%20Networks%20-%20Jerry%20Fanelli.pdf)**

**Presentation: [Link](https://github.com/jerryfane/bitcoin-price-prediction-with-2d-cnn/blob/main/Presentation.pdf)**

---

Contact me for feedbacks [LinkedIn](https://www.linkedin.com/in/jerry-fanelli/)
