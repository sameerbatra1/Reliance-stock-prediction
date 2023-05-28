# Reliance-stock-prediction

link of dataset: https://www.kaggle.com/datasets/kapturovalexander/20-largest-companies-in-india-share-prices?select=1_RELIANCE.NS.csv

## Introduction
The goal of this AI project was to predict the prices of Reliance stocks using machine learning algorithms. The project utilized a Kaggle dataset on Reliance stocks and employed various algorithms to make predictions. The performance of these algorithms was evaluated using Mean Squared Error (MSE) and R2 Score.

## Dataset
The Kaggle dataset used in this project consisted of historical stock data for Reliance Industries Limited, including various features such as opening price, closing price, volume, and other relevant market indicators. The dataset spanned a specific time period from 1996 to 2023 and served as the basis for training and evaluating our machine learning models.

## Model Evaluation
The performance of each algorithm was assessed using two common evaluation metrics: Mean Squared Error (MSE) and R2 Score. MSE measures the average squared difference between the predicted and actual stock prices, while R2 Score indicates the proportion of variance in the target variable that can be explained by the predictors.

## Comparitive Analysis
Based on the MSE and R2 Score, the algorithms can be compared as follows: 
* Random Forest Regressor achieved the lowest MSE of 0.000017, indicating its ability to make precise predictions. It also obtained the highest R2 Score of 0.999949, signifying its excellent fit to the data and high explanatory power. Random Forest Regressor outperformed all other algorithms in terms of accuracy and predictive capability.
* Decision Tree Regressor also performed exceptionally well, with a low MSE of 0.000030 and a high R2 Score of 0.999907. It demonstrated strong predictive performance and captured the underlying patterns in the data effectively. 
* Linear Regression, and Ridge algorithms obtained similar results in terms of MSE and R2 Score. They achieved relatively higher MSE values compared to Random Forest Regressor and Decision Tree Regressor but still exhibited high R2 Scores, indicating a good fit to the data. 
* Lasso algorithm achieved the highest MSE of 0.035431 and the lowest R2 Score of 0.870334 among the algorithms used. Although it had slightly reduced predictive accuracy compared to the other algorithms, it still provided valuable insights into the dataset.

## Conclusion
In this AI project, various machine learning algorithms were employed to predict the prices of Reliance stocks. The results of the comparative analysis demonstrated the superior performance of Random Forest Regressor and Decision Tree Regressor in terms of accuracy and predictive power. These algorithms exhibited the lowest MSE values and the highest R2 Scores, indicating their effectiveness in capturing the underlying patterns in the data. 

It is important to note that the performance of these algorithms may vary in different market conditions and time periods. Therefore, it is recommended to regularly evaluate and update the models to ensure optimal predictions. Additionally, further experimentation and analysis can be conducted to fine-tune the algorithms and explore additional features that might enhance the prediction accuracy. 

Overall, this project showcased the potential of machine learning algorithms in predicting the prices of Reliance stocks and provided valuable insights for decision- making in the financial domain.
