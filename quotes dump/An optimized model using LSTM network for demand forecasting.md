
Computers & Industrial Engineering 143 (2020) 106435


### 1. Introduction

- **On the significance of demand forecasting**:
    - "Demand forecasting is the basis of all planning activities (Haberleitner, Meyr, & Taudes, 2010)."
    - "Accurate demand forecasting guarantees suitable supply chain management and enhances customer satisfaction by preventing inventory stock-out (Kumar, Shankar, & Alijohani, 2019)."
- **On the challenges of traditional methods**:
    - "Strict competition among firms in any domain has made it difficult for businesses to accurately forecast the customers’ demands using traditional demand forecasting methods (Guo, Diao, Zhao, Wang, & Sun, 2017; Kumar et al., 2019)."
    - "Therefore, companies are increasingly moving toward the use of advanced data science techniques to forecast customer demand."
- **On the formulation of demand forecasting**:
    - "In general, customer demand is modeled as a sequential data of customer demands over time. Hence, demand forecasting problem can be formulated as a time series forecasting problem (Villegas, Pedregal, & Trapero, 2018)."
- **On Demand Forecasting Accuracy**:
    - "The aim of this study is to obtain an accurate model for demand forecasting of a furniture company."

### 2. Importance of Demand for Minimum Stock Levels

- **On the application of time series forecasting**:
    - "Time series prediction has been applied in various areas of application such as credit scoring... forecasting call center arriving calls... ATM cash demand forecasting... weather forecasting (Maqsood, Khan, & Abraham, 2004), etc."
- **Demand Variability**:
    - "The main limitation of ARIMA is that it assumes that the given time series is linear."
    - This can relate to the challenges in demand variability when calculating Minimum Stock Levels (MSL).
- **Calculating Future Demand**:
    - "The best way to manage the optimum quantity of raw material and product is to find out the future demand for these materials and products."
- **Challenges in Forecasting Demand**:
    - "These sudden shifts in trend make the forecasting task difficult."
- **On Time Series Characteristics**:
    - "...considering the intrinsic characteristics of the demand time series (being nonlinear and non-stationary)."

### 3. Traditional Methodology

- **Overview of statistical methods used in traditional demand forecasting**:
    - "To evaluate the performance of the proposed approach, two statistical time series forecasting methods (ETS, ARIMA) were considered."
    - "Widely-used statistical time series forecasting methods such as ARIMA suppose that the time series contains only linear components. However, most real-world time series data consist of nonlinear components too."
    - "This causes the procedure of finding a proper model for time series to become more complex."
- **Limitations of ARIMA**:
    - "The main limitation of ARIMA is that it assumes that the given time series is linear."
- **Exponential Smoothing Methods**:
    - "Exponential smoothing methods are similar to moving average, except for the fact that predictions are obtained by considering weighted averages of past values in a time series."
- **Overview of ANN**:
    - "ANN is a computational model that emulates human brain operations in processing information."
- **On Challenges with Traditional Methods**:
    - "...trying to overcome the challenges of obtaining an accurate forecasting model."

### 4. Modern Machine Learning Methodology

- **Introduction to machine learning for demand forecasting**:
    - "Recently, computational intelligence techniques including artificial neural networks (ANN), support vector machine (SVM), K-nearest neighbors (KNN), and adaptive neuro-fuzzy inference system (ANFIS) have been frequently used for the problem of time series prediction."
- **On the advantages of computational intelligence techniques**:
    - "ANNs have several advantageous characteristics, including universal approximation, being data driven, and the ability to better capture nonlinear patterns in data (Khashei & Bijari, 2011; Panigrahi & Behera, 2017)."
- **Comparison with Machine Learning Methods**:
    - "Our method outperforms ETS in terms of both performance measures."
- **Performance Measures**:
    - "From Table 8, it is clear that the best results achieved using our approach in terms of RMSE and SMAPE."
- **On recurrent neural networks (RNNs)**:
    - "A specific class of ANNs are recurrent neural networks (RNNs). Unlike in feedforward ANNs, the connections between nodes in an RNN establish a cycle which allows signals to move in different directions (Parmezan, Souza, & Batista, 2019)."
    - "RNNs provide a short-term memory by storing the activations from each time step."
- **On Deep Learning Approaches**:
    - "We exploit recent deep learning methods to specify the best time series forecasting model for solving the demand forecasting problem."
- **On Hyperparameter Optimization**:
    - "...the proposed method focuses mainly on optimization of hyperparameters of LSTM network."
- **On the capability of computational intelligence techniques**:
    - "This indicates that computational intelligence techniques have great capability in capturing patterns of real-world time series data."

### 5. Neural Network Implementation Approach

- **Detailed steps for implementing neural networks in demand forecasting**:
    - "In this study, we propose a method based on a multi-layer LSTM network by using the grid search approach."
    - "The capability to capture nonlinear patterns in time series data is one of the main advantages of our method."
- **On Data Preparation**:
    - "Data cleaning and normalization are the two essential data preparation tasks which will be applied to prepare data for forecasting task."
- **On Hyperparameter Selection**:
    - "Obtaining good performance with LSTM networks is not a simple task, as it involves the optimization of multiple hyperparameters."
- **On Importance of Hyperparameters**:
    - "Hyperparameter selection improves the model performance."
- **On Model Configuration and Training**:
    - "...the input at time tit_iti​, s(ti)s(t_i)s(ti​) is input into the first LSTM hidden layer along with the h(1)(ti−1)h(1)(t_{i-1})h(1)(ti−1​), the output value of the first LSTM block at time point ti−1t_{i-1}ti−1​."
- **On Model Evaluation**:
    - "...to evaluate the generated candidate models, performance of each model is assessed using RMSE metric which is calculated based on denormalized input and predicted output data."
- **Overview of RNNs**:
    - "RNNs can model temporal dependencies and are especially suitable for the prediction of sequence data."
- **On LSTM Advantages**:
    - "LSTM can store long-range time dependency information and can suitably map between input and output data."

### Conclusion

- **Summary of the advantages of modern methods**:
    - "The results of these methods are compared, and we demonstrate that the model built by employing the proposed method performs substantially better than the alternatives."
- **On the comparative performance of forecasting methods**:
    - "There are significant differences among the applied models."
    - "We compare the proposed method with some well-known time series forecasting techniques from both the statistical and computational intelligence methods categories."
    - "The results demonstrate the superiority of the proposed method in comparison to all utilized methods."
    - "Our experiments on the original demand time series reveal that our method reaches the best performance in terms of both RMSE and SMAPE, followed by SVM and ANN."
- **Weak Performance of Traditional Methods**:
    - "The results of the experiments showed that traditional statistical methods such as ETS and ARIMA yield weak performance in comparison to SVM, ANN, and LSTM."
- **Future Directions**:
    - "As future work, we can employ the proposed method on other areas such as customer future behavior forecasting."
    - "Also, future study can utilize other deep learning methods such as attention-based neural networks for time series forecasting."