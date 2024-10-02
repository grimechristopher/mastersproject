# Describing the Problem
**On the unpredictability of demand and the need for large safety stocks:**

> "Demand for each spare part is unpredictable, forcing repair shops to keep large spare parts safety stocks[1]."

**On the limitations of traditional stochastic models in demand forecasting and inventory control:**

> "Current stochastic inventory models do not provide sufficient control over those repair times[1]."

**On Inventory Policy**:

- "Inventory is under continuous review and is controlled using independent (s, S) policies."
    - This quote is important as it references the traditional **(s, S) inventory policies**, which are still widely used for stock management, offering a point of comparison between traditional methods and modern or machine learning-based approaches in your survey paper.

**On Complex Inventory Dynamics**:

- "Spare parts are allocated to repairs on a FCFS basis... even though other spare parts may still be missing."
    - This highlights an **operational detail** of first-come, first-served (FCFS) allocation of spare parts, showing the challenge of managing incomplete repairs. This could be contrasted with how neural network models might optimize such real-time allocation decisions.

### **Most Relevant to Your Paper**:

- The section's description of **(s, S) policies** and the use of **Poisson processes** for demand forecasting is highly relevant. These traditional approaches form the basis of inventory management, which you can contrast with more advanced methods like neural networks in your survey.
- The reference to **stochastic leadtimes** and **back-ordering** touches upon common challenges in inventory control, providing a good jumping-off point for discussing how modern techniques (e.g., neural networks) handle such uncertainty differently.
# Citations
[1] - Improving spare parts inventory control at a repair shop
-- Compound Poisson Demand


# Next Paper
> Large-Scale Inventory Optimization: A
Recurrent-Neural-Networks-Inspired Simulation
Approach

## Key Points

**Importance of Inventory Management:**

> "Effective management of inventory can offer tremendous potential for increasing manufacturing efficiency and reducing operational cost."

- **Context:** This emphasizes the critical role inventory management plays in operational efficiency, setting the stage for your discussion on demand forecasting's impact on inventory levels.

**Current Challenges:**

> "With the ongoing global pandemics and international trade frictions, the global supply chains are facing increasingly more risks and... how to manage these large-scale production and inventory systems becomes not only challenging but also extremely important."

- **Context:** This underlines the current relevance of inventory management and demand forecasting in light of global challenges, providing a timely context for your paper.

**Efficiency of Neural Networks:**

> "This analogy is critical to the speedup of the simulation approach, because RNNs are sometimes bigger than the production-inventory systems that we consider..."

- **Context:** This quote supports your focus on machine learning, specifically neural networks, illustrating their potential to enhance inventory management efficiency.


**Use of Regularization:**

> "We propose to use L1-regularization to force the solution of the optimization problem to be sparse, thus only allowing a small number of nodes to have non-zero base-stock levels."

- **Context:** This showcases an advanced technique in machine learning that can optimize inventory levels, relevant for your in-depth discussion on neural networks.


**Algorithm Efficiency:**

> "By combining the tools of RNNs and the use of sparse matrices, we improve the computational complexities... and reduce the computational times in the order of thousands to tens of thousands."

- **Context:** This emphasizes the effectiveness of machine learning algorithms in solving large-scale problems, aligning with your focus on modern adaptations in demand forecasting.

- **On Back Propagation (BP) and Efficiency:**
    
    - “It has been shown that, when the input is of a multi-dimensional vector...the BP algorithm is typically computationally more efficient than the forward mode algorithms.”
- **On the Importance of BP in Neural Networks:**
    
    - “The BP algorithm for training neural networks was proposed by Rumelhart et al. (1986), and it is one of the corner stones of deep learning.”
- **On Regularization Techniques:**
    
    - “The L1 regularization is also known as Lasso in the statistics literature, and it is known to introduce sparsity to the solution.”

- **On Gradient Estimation:**
    
    - “The simplest method for gradient estimation may be finite difference approximations. It is easy to understand and implement. However, it produces biased estimators and the computation time is prohibitively long, because at least n + 1 simulation runs are necessary to compute just one observation of the gradient.”
- **On Infinitesimal Perturbation Analysis (IPA):**
    
    - “IPA is one of the most important gradient estimation methods in the field of stochastic simulation...if the following conditions are satisfied: J(θ) is differentiable with probability 1, and J(θ) is stochastically Lipschitz.”

# Paper 3

> Substation Equipment Spare Parts’ Inventory Prediction Model
Based on Remaining Useful Life

**On Historical Data and Forecasting Models**:

- "Spare parts inventory levels are often calculated based on certain historical data and forecasting models."

- **On Quantitative Forecasting Models**:
    
    - "With the development of computers and the demand for short-term and medium-term forecasting techniques, quantitative forecasting models have taken the dominant position, such as gray forecasting models, linear regression, and autoregressive moving average (ARMA) models."
- **On Machine Learning and AI**:
    
    - "With the development of artificial intelligence, forecasting models based on AI techniques began to play an important role, such as machine learning, deep learning, support vector machine (SVM), backpropagation (BP) neural networks, and long short-term memory (LSTM)."


**On the Study's Contribution**:

- "We make an innovative model of an inventory prediction algorithm according to the RUL of the equipment and applied it to the inventory management system of relay protection equipment."




> Modeling and long-term forecasting demand in spare parts
logistics businesses

- **Importance of Spare Part Demand Forecasting**:
    
    - “Spare part demand forecasting is of crucial importance for maintenance systems, however, it is a complex issue due to the following reasons: in case of most electronic products the number of managed spare parts may often be high...”
- **Characteristics of Spare Parts**:
    
    - “Spare parts can be characterized by their own life-cycles which is associated with the life-cycle of the final products that utilize them.”
- **Life-Cycle Phases**:
    
    - “The purchase life-cycle (PLC) curve of an electronic spare part typically consists of three characteristic phases: an increasing first phase, a quasi-constant second phase and a declining third phase.”

- **Modeling and Forecasting**:
    
    - “In this paper a new way of modeling and forecasting electronic spare part demand is addressed and discussed.”
- **Reliability Data Utilization**:
    
    - “...already available reliability data of different, yet similar products could be utilized for products under (re)design by considering that these will typically have similar reliability characteristics.”
- **Demand Time Series Trends**:
    
    - “The trend curves of time series representing the demands for spare parts can be considered as purchase life-cycles (PLC) of spare parts.”
- **Forecasting Methodology**:
    
    - “The introduced comparative forecasting methodology regarding lumpy spare part demand is based on knowledge discovery techniques.”
- **Model Characteristics**:
    
    - “The presented modeling methodology is founded on the assumption that the purchase life-cycles of spare parts can be described by a curve with short-term fluctuations around it...”


> Paper 5 - An optimized model using LSTM network for demand forecasting


**Impact of Accurate Forecasting**:

- “Accurate demand forecasting guarantees suitable supply chain management, and enhances customer satisfaction by preventing inventory stock-out.”
- This quote emphasizes the practical benefits of accurate forecasting in inventory efficiency and customer satisfaction.

**Challenges of Traditional Methods**:

- “Strict competition among firms in any domain has made it difficult for businesses to accurately forecast the customers’ demands using traditional demand forecasting methods.”
- This can be used to underscore the limitations of traditional approaches and the need for modern solutions.


**Formulating Demand Forecasting as a Time Series Problem**:

- “In general, customer demand is modeled as a sequential data of customer demands over time. Hence, demand forecasting problem can be formulated as a time series forecasting problem.”
- This lays the groundwork for discussing the transition to time series analysis and machine learning methods.

- **Advantages of Neural Networks**:
    
    - “ANNs have several advantageous characteristics, including universal approximation, being data driven, and the ability to better capture nonlinear patterns in data.”
    - This can be utilized to discuss the benefits of neural networks in demand forecasting.
- **Challenges with RNNs**:
    
    - “The weakness of RNNs is the vanishing and exploding gradient problem, which makes it hard to train.”
    - This quote addresses some of the limitations of recurrent neural networks, which is relevant for your in-depth discussion on neural networks.
- **Proposed Method and LSTM**:
    
    - “In this study, we propose a method based on a multi-layer LSTM network by using the grid search approach.”
    - This can introduce your exploration of specific neural network models in demand forecasting.
