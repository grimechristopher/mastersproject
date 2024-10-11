
Int. J. Production Economics 232 (2021) 107954

### 1. Introduction

- **Explanation of Minimum Stock Level (MSL) and its importance.**
- **Challenges in balancing stock-outs and overstocking:**
    - "Demand forecasting and inventory control of spare parts, or any items associated with intermittent demand, are challenging tasks for inventory managers."
    - "This is mainly due to the compound nature of such demand patterns (demand occurrences are interspersed by intervals of no demand at all), which are often associated in practice with a lack of historical data to enable reliable estimates for the parameters of the assumed demand distribution."
- **Importance of accurate demand forecasting:**
    - "The focus of this paper is the Bayesian approach, which uses the Bayes Theorem to update a prior distribution into a posterior distribution by incorporating information provided by the observed data."
    - "The ability to combine all information and sources of uncertainty, and revise and update it as more data are acquired is particularly promising and appealing when (1) data are scarce and (2) there are considerable changes in the data."
- **Transition from traditional to modern methods:**
    - "Under such changes and uncertain conditions, parametric frequentist and non-parametric forecasting approaches are not adequate due to the assumption of constant demand distribution parameters over time."
- **On the advantages of the Bayesian approach:**
    - "The Bayesian approach provides practitioners with an opportunity to incorporate intuition and previous experience in a quantifiable form by selecting an appropriate choice of the prior distribution."

---

### 2. Importance of Demand for Minimum Stock Levels

- **Explanation of formulas for calculating MSL and the role of demand variability:**
    - "In fact, in practice the usage context is unlikely to stay the same throughout the lifecycle of a system, which renders the failure rate of a part changing over time."
- **Complexity of forecasting repair demand and its impact on MSL:**
    - "Moreover, the failure rate is often unknown either due to the absence of operational data at the time of initial provisioning, or due to the lack of data when changes in environment occur."
- **Factors influencing demand:**
    - "the demand dataset is composed of many SKUs with a low degree of intermittence since the average demand intervals can be almost equal to 1."
    - "In some cases, the average demand size can be as high as 193 units."
    - "In order to ensure that demand arrival is intermittent, we have considered the values of the parameter λ in the range 0.05–1.95."
    - "The transaction size variability ranges from 0.05 to 4.95 and the transaction size modality from 1 to 25."

---

### 3. Traditional Methodology

- **Overview of statistical methods used in traditional demand forecasting (ARMA, Exponential Smoothing, Poisson Process):**
    - "We assume that demand follows a compound Poisson distribution, which means that demand arrivals follow a Poisson process and the demand sizes are variable and characterised by a demand size distribution."
- **Limitations of these methods in dynamic environments:**
    - "Parametric frequentist and non-parametric forecasting approaches are not adequate due to the assumption of constant demand distribution parameters over time."
    - "the performance of WSS considerably decreases, especially compared to SBA, when the empirical data is used as opposed to theoretical data."
- **Examples of modern improvements to traditional methods (ZIP-METRIC, Poisson-Bayes):**
    - "the results also show that SBA is more efficient than WSS... when a low demand variability is considered."

---

### 4. Modern Machine Learning Methodology

- **Introduction to machine learning for demand forecasting:**
- **Key machine learning techniques used, including neural networks:**
- **Discussion of different neural networks (RNNs, LSTMs) and their application in demand forecasting:**
- **On the Bayesian approach in the context of demand forecasting:**
    - "The Bayesian approach is intuitively appealing when forecasting spare parts demand due to the appropriate assumption of demand distribution parameters changing over time, which reflects the changing failure rates."
- **Advantages of ML over traditional methods, especially in complex, volatile environments:**
    - "the empirical results reveal that SBA and CPB lead to almost the same achieved CSLs, which can be 2% higher than that of WSS."

---

### 5. Neural Network Implementation Approach

- **Detailed steps for implementing neural networks in demand forecasting:**
- **Data collection, training models, handling overfitting, and computational challenges:**
    - "Finally, it should be noted that in practice most companies store demand data periodically, which means that data are somehow aggregated over a certain time period..."
    - "The lead-time for all SKUs is less than a month, therefore we assume in the empirical investigation that the lead-time L = 1 month."
    - "It should be noted that, when calculating the order-up-to-level St, the numerical evaluation of the predictive distribution in the CPB method is more computationally demanding than that of SBA."
    - "...numerical integration methods based on analytic approximations or quadrature. However, the computational effort involved would be considerable."

---

### 6. Conclusion

- **Summary of the advantages of modern methods:**
    - "the two Bayesian methods lead to the highest efficiency since for a fixed stock on hand they lead to the lowest backorders and the highest achieved CSLs."
- **Acknowledge challenges but highlight the superior accuracy of machine learning and neural networks in forecasting:**
    - "Hence, the contribution of this paper is three-fold: (1) We propose a new Bayesian method based on compound Poisson demand; (2) We evaluate the empirical performance of the Poisson-based Bayesian method; (3) We compare the empirical performance of the two Bayesian methods to a parametric frequentist and a non-parametric one."
- **On the contribution of the research:**
    - "The empirical results show that the CPB method leads to an over-achievement of all target CSLs. However, when the PGB, SBA and WSS methods are used, they enable the achievement of the targets CSL = 85% and CSL = 90%, but not CSL = 95%."