# Titanic Gradient Boosting

## In this case study I will utilize gradient boosting to improve predictions based on information from the residuals. We want to predict if a passenger survived the from the Titanic crashing into the iceberg in 1912. This survived column will be our dependent variable for our classification problem.

![image](https://user-images.githubusercontent.com/86930309/227742995-b734507f-9839-4f6b-9bdf-7d11b9595e3c.png)

- ## Data Wrangling

- ## EDA

- ## Gradient Boosting Modeling

- The best learning rate for the GB model was 1:
- Learning rate:  1
- Accuracy score (training): 0.854
- Accuracy score (validation): 0.783

- When we use the learning rate of 1 our model predicts if a passenger survved or not 87% of the time with teh AUC ROC curve.

![image](https://user-images.githubusercontent.com/86930309/227744250-0a021133-9ca2-41c5-97ba-041425d6e802.png)

- ## Conclusion

Our model is considered excellent at predicting if a passenger of the Titanic has survied or not. An 87% prediction rate from the AUC ROC curve is a good model to work with.  
