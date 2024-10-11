Computers & Industrial Engineering 110 (2017) 92–108

##### 1. Introduction

- **On the complexity of demand forecasting**:  
    "Quantifying the consumption of airplane spare parts is highly complicated, especially due to the nonlinear, grey and trending characteristics of demand."
    
- **On the importance of accurate demand forecasting**:  
    "The key to solving this problem is to forecast the demand for spare parts accurately."  
    "Demand forecasting is the foundation of ordering decisions for spare parts."
    
- **On the significance of scientific methods in forecasting**:  
    "Consequently, suppliers should gauge the consumption of spare parts and use scientific methods to forecast demand."
    
- **On challenges faced in demand forecasting**:  
    "Current studies and applications on demand prediction often encounter two major challenges: inconsistent data with actual demand and less accurate forecasting approaches."
    

---

### 2. Importance of Demand for Minimum Stock Levels

- **On the role of accurate forecasting in order management**:  
    "Assessing future demand plays an important role in order management for spare parts, which requires accurate forecasting."
    
- **On the impact of forecasting methods**:  
    "The accuracy of different forecasting theories and methods is often directly affected by the manner in which they are applied."
    
- **On the need for in-depth research to understand demand**:  
    "The accurate forecast for spare parts demand requires in-depth research to identify the factors influencing that demand."
    
- **On principles for forecasting**:  
    "To forecast the demand for spare parts accurately, we need to adhere to two principles. First, the influence factors should be objective and easily identifiable in practice. Second, the influence factors should be consistent with actual consumption."
    
- **On the various factors that influence demand**:  
    "According to the above principles, we mainly consider the following factors: Annual aircraft strength of a fleet, Annual total flight time of a fleet, Annual average flight time of an aircraft, Annual total takeoff-landing times of a fleet, Annual average takeoff-landing times of an aircraft, Annual total spare parts supply good rate of a fleet, Annual average spare parts supply good rate of an aircraft, Annual total spare parts fault number of a fleet, Annual average spare parts fault number of an aircraft, Annual total spare parts consumption number of a fleet, Annual average spare parts consumption number of an aircraft, Annual total spare parts turnover number of a fleet, Annual average spare parts turnover number of an aircraft."
    
- **On calculating consumption and turnover**:  
    "Annual consumption and turnover number of a fleet divided by annual number of aircraft is equivalent to annual consumption and turnover data of an aircraft."
    

---

### 3. Traditional Methodology

- **On the limitations of traditional forecasting approaches**:  
    "In recent decades, annual consumption data for an aircraft fleet are commonly adopted to forecast demand for aircraft spare parts, often causing the purchase quantities for reparable parts to far exceed the actual required turnover number."
    
- **On the waste of resources due to inaccurate forecasting**:  
    "The authors have been analyzing the overstocked and scrapped reparable spare parts for nearly 10 years and have found that the annual average cost of the overstocked and scrapped reparable spare parts accounts for about 11% of annual procurement funds for Chinese naval aviation."
    
- **Overview of statistical methods**:  
    "Classical methods include the exponential smoothing method and grey theory."
    
- **On the suitability of exponential smoothing methods**:  
    "The exponential smoothing method mainly includes three kinds: linear exponential smoothing (LES), secondary exponential smoothing (SES) and cubic exponential smoothing (CES), which have different prediction accuracies for different regular time series."
    
- **On the effectiveness of grey theory**:  
    "Grey theory performs well in the demand forecasting for spare parts with a small sample size."
    

---

### 4. Modern Machine Learning Methodology

- **On forecasting strategies**:  
    "There are currently two forecasting strategies for spare parts... One is to forecast directly by individual forecasting methods, which is known as an item-level forecast... The other is to forecast indirectly by combining individual forecasting methods, which is known as a group-level forecast."
    
- **On the innovative approach of the double-level combination forecast**:  
    "A double-level combination forecast model can obtain a superior final result by automatic optimization combination of multiple models, which does not require decision makers to make subjective judgments."
    
- **On neural networks as a forecasting method**:  
    "Of these methods, neural network has a suitable adaptive and self-learning ability and strong anti-interference properties, which is suitable to solve linear and non-linear problems."
    
- **On the limitations of traditional neural networks**:  
    "However, a general neural network has faults such as a slow convergence rate and a high tendency to fall into local minima."
    
- **On genetic algorithms optimizing neural networks**:  
    "To overcome these faults, a genetic algorithm is often used to optimize neural network."
    

---

### 5. Neural Network Implementation Approach

- **On the need for advanced forecasting methodologies**:  
    "It is very important for demand forecasting models to forecast a large number of spare parts precisely, and it is not possible for each spare part to make subjective judgments again to find a superior result after forecasted by different methods."
    
- **On the uniqueness of the proposed methodology**:  
    "In summary, this paper adopts relevant data pre-processed in accordance with actual demand. In addition, a double-level combination forecast model is established using advanced and reliable methods to forecast the demand for repairable spare parts."
    
- **On combining different forecasting methods**:  
    "To solve this problem, different direct forecast methods are often combined to perform forecasts, which can provide distinct useful information."
    
- **On the superiority of combination forecasts**:  
    "It has been demonstrated that combination forecast is superior to direct forecast."
    
- **On the proposed double-level combination forecast approach**:  
    "To further improve the forecasting precision of common combination forecast models, this paper proposes a double-level combination forecast approach to forecast demand."
    
- **On the convergence condition for optimization**:  
    "Set n as the error precision of the objective function. Then the convergence condition is ESSE < n."
    

---

### Conclusion

- **On addressing forecasting challenges**:  
    "To address the problem, we adopt annual turnover data rather than annual consumption data to forecast the demand for repairable spare parts, which can ensure forecasting results consistent with actual demand."
    
- **On the effectiveness of the proposed models**:  
    "The theoretical and computational analyses suggest that the models and approaches provided in this paper have higher accuracy and applicability for repairable spare parts; the forecasting results are consistent with the actual demand for repairable spare parts."
    
- **On accuracy and stability**:  
    "The proposed double-level combination forecast model can well solve the problem of insufficient accuracy of current methods; meanwhile, it has higher stability."
    
- **On the implications of forecasting accuracy**:  
    "If the forecasts based on the consumption data of a fleet are used to purchase and supply, the backlogs of these spare parts will be 31.27%, 61.72% and 38.91% more than the actual consumption data."  
    "Therefore, the forecasting results based on the turnover data of an aircraft are more accurate than the forecasting results based on the turnover data of a fleet."