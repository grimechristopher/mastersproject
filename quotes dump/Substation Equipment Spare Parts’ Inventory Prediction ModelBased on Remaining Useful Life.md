https://doi.org/10.1155/2022/3396850

### Introduction

1. **On Safety Stock and Demand Forecasting:**
    
    - "Safety stock is an important topic in inventory management and its main role is to meet the uncertainty of supply and demand."
    - "The definition of safety stock varies from industry to industry."
2. **On the Importance of Forecasting Models:**
    
    - "Spare parts inventory levels are often calculated based on certain historical data and forecasting models."
    - "With the development of computers and the demand for short-term and medium-term forecasting techniques, quantitative forecasting models have taken the dominant position."
3. **On Traditional vs. Modern Methods:**
    
    - "These quantitative forecasting approaches tend to have certain data requirements and also have obvious advantages and disadvantages, such as an emphasis on model improvement to improve the prediction accuracy, but less consideration is given to the factors affecting the inventory."

### Importance of Demand for Minimum Stock Levels

4. **On Demand Variability:**
    
    - "The expert meeting method and the Delphi method are less practical and reliable due to their reliance on expert experience."
5. **On Modern Techniques:**
    
    - "With the development of artificial intelligence, forecasting models based on AI techniques began to play an important role, such as machine learning, deep learning, support vector machine (SVM), backpropagation (BP) neural networks, and long short-term memory (LSTM)."
6. **On the complexity of demand forecasting:**
    
    - "It is difficult to obtain monitoring data since they are board-like devices of small size. The operation and maintenance (O&M) processes require a lot of manpower. It has a long procurement cycle."
7. **On the prediction curve and its relationship to actual demand:**
    
    - "From it, we can see that the prediction curve of the CPU with the quarterly cycle has almost the same trend as the real value, which means that the RUL-based prediction method is effective."
8. **On the implications of overestimating demand:**
    
    - "In the graph, we will also notice that the predicted value is slightly larger than the true value, which is intended to make the spare parts slightly more available in case there are no spare parts available when an unexpected event occurs, i.e., it is beneficial to the stability of the power system."

### Traditional Methodology

9. **On Statistical Methods:**
    
    - "Overview of statistical methods used in traditional demand forecasting (ARMA, Exponential Smoothing, Poisson Process)."
    - "These quantitative forecasting approaches... have obvious advantages and disadvantages, such as an emphasis on model improvement to improve the prediction accuracy..."
10. **On traditional forecasting limitations:**
    

- "Although the prediction results of these four forecasting models are the same as the true values in some quarters, the overall prediction results are not suitable for electric power companies mainly because the difference between the predicted and true values is positive and negative, which leads to the inability of Changzhou Power Supply Company to achieve the goal of purchasing by quarters."

### Modern Machine Learning Methodology

11. **On the Role of Machine Learning:**

- "These intelligent prediction techniques have played an important role in various industries with the help of excellent data processing capabilities."

12. **On Specific Machine Learning Techniques:**

- "Ding improved the BP neural network model based on the Adam optimization method to forecast the demand for materials in the Guizhou power grid, and the method can significantly reduce the error."
- "In [25], an effective model based on the long short-term memory (LSTM) recurrent neural network was put forward to predict the requirement for maintenance of spare parts."

13. **On the effectiveness of the RUL-based prediction model:**

- "The RMSE and MAE of the five method prediction methods are shown in Table 3. From Table 3, it can be seen that the RUL-based prediction results have the smallest RMSE and MAE among the above five prediction models. It further illustrates the effectiveness of RUL-based CPU prediction."

14. **On the need for decision-making based on forecasting:**

- "The purpose of forecasting on a quarterly cycle is to provide a decision basis for the procurement of spare parts for Changzhou Power Supply Company to save storage space as well as improve capital utilization."

15. **On the effectiveness of RUL in decision-making:**

- "The remaining useful life (RUL) plays an important role in many fields. It can provide strong support for upper-level decision-making, scientifically reduce the operating cost of the system, and enhance the reliability of the system."

### Neural Network Implementation Approach

16. **On Prediction Accuracy:**

- "To improve the prediction accuracy of the model, this study fully considers the factors that have direct and indirect effects on the RUL of equipment."

17. **On optimization in neural networks:**

- "The problem of solving the regression hyperplane can be transformed into the optimization problem."

### Conclusion

18. **On Advantages of Modern Methods:**

- "The model implements the following functions: ... To meet the requirement of saving inventory cost and storage space under the condition of achieving inventory safety and to provide decision support."

19. **On model efficiency and accuracy:**

- "For this study, we are pursuing the accuracy of the prediction and the conformity of the prediction results to the nature of the enterprise."

20. **On the importance of RUL in forecasting:**

- "The main idea of Algorithm 2 is to consider how many components have an RUL less than T in a prediction period T."