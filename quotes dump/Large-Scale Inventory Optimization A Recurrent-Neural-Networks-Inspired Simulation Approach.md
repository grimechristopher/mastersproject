arXiv:2201.05868v1


### Introduction

1. **Importance of Inventory Management:**
    
    - "Effective management of inventory can offer tremendous potential for increasing manufacturing efficiency and reducing operational cost."
    - "Inventory management has always been a core part of modern enterprise supply chain management."
2. **Challenges in Inventory Management:**
    
    - "These complex production systems also impose tremendous challenges and opportunities to inventory management."
    - "With the ongoing global pandemics and international trade frictions, the global supply chains are facing increasingly more risks and, therefore, how to manage these large-scale production and inventory systems becomes not only challenging but also extremely important."
3. **Role of Advanced Methods:**
    
    - "To overcome the first drawback of the traditional simulation approach, we notice that the simulation of a production-inventory system is very similar to the forward pass of a recurrent neural network (RNN)."
    - "This analogy is critical to the speedup of the simulation approach, because RNNs are sometimes bigger than the production-inventory systems that we consider."

### Importance of Demand for Minimum Stock Levels

1. **Dynamic Inventory Costs:**
    - "The overall inventory costs of these production systems are often very high and, therefore, any savings may be quite significant."

### Traditional Methodology

1. **Limitations of Traditional Methods:**
    
    - "The simulation approach first builds a simulation model that simulates the evolution of the production and inventory system with randomly generated demands and given inventory policies."
    - "Even though the simulation approach is simple conceptually and it is capable of modeling complex production-inventory systems, it has two drawbacks that prevent it from solving the large-scale problems considered in this paper."
2. **On the Simplicity of Base-Stock Policies:**
    
    - "Notice that the base-stock policies may not be the optimal policies for our problem. However, they are widely used in practice because of its simplicity... and they are known to be optimal for serial systems and assembly systems."
3. **On Limitations of Traditional Approaches:**
    
    - "For large-scale production-inventory systems, considering capacity constraints will turn the inventory optimization problem into a complex production planning/scheduling problem."

### Modern Machine Learning Methodology

1. **Machine Learning Advantages:**
    
    - "By applying the SA algorithm directly, we observe that the solution typically keeps inventory for almost all nodes and it is very difficult to implement in practice."
    - "We propose to use L1-regularization to force the solution of the optimization problem to be sparse, thus only allowing a small number of nodes to have non-zero base-stock levels."
2. **Deep Learning Tools:**
    
    - "It finds that the modeling of a complex production-inventory system is analogous to a RNN, and its simulation optimization is analogous to the training of a RNN."
    - "This analogy opens the door so that we can take advantages of efficient computational tools of deep learning to solve large-scale inventory problems."
3. **On the Complexity of Inventory Systems:**
    
    - "The generality also brings tremendous challenges in computation, especially for large-scale problems that are considered in this paper."
4. **On Stochastic Demand Management:**
    
    - "But we assume that they follow known distributions (or, at least, may be generated through a simulation algorithm) that take only integer values."
5. **On the Need for Inventory Position Calculation:**
    
    - "It is a measure used under a base-stock policy for making ordering decisions, which equals the on-hand inventory plus the on-order quantity (i.e., the amount that is ordered but not yet received through either procurement or production) minus the backorders."
6. **On Stochastic Demands and Their Implications:**
    
    - "We allow all production items to have outside demands, because some intermediate items are needed for maintenance or service. In our model, the outside demands, the production time, and the procurement times may be stochastic."

### Neural Network Implementation Approach

1. **Implementation Insights:**
    
    - "We test different methods to implement the algorithms, including the use of TensorFlow for simulation and for automatic calculation of the sample-path gradients, the use of parallel CPU processors and the use of GPUs."
2. **On Computational Challenges in Inventory Simulation:**
    
    - "The simulation of a single replication of a system with only 5,000 nodes for 100 periods may take about an hour, and the calculation of its sample-path gradient may take over ten hours."
3. **On the Iterative Nature of Inventory Simulation Algorithms:**
    
    - "The aforementioned Steps 1 to 4 form an iteration (i.e., a period) of the inventory simulation algorithm, and it runs for T periods to calculate (an observation of) the cumulative cost."
4. **On the Capability of RNNs:**
    
    - "RNN is a class of neural networks that allow previous outputs to be used as inputs while having hidden states. This enables it to exhibit temporal dynamic behaviors and to model time series data."
5. **On the Performance of RNNs:**
    
    - "RNN models have achieved the-state-of-the-art performance on tasks that include speech recognition... and image captioning."
6. **On RNN Architecture:**
    
    - "A common implementation of an RNN can be described by the following updating equations..."
7. **On Optimization of RNNs:**
    
    - "To train an RNN is to find the network parameters that solves the following optimization problem..."
8. **On Similarities Between RNN and Inventory Optimization:**
    
    - "Both models have a complex network that evolves over time, and both have external and internal inputs in each period."
9. **On the Optimization Formulations:**
    
    - "The objective function of the inventory optimization problem is an expectation, which may be approximated by the sample average of N samples."

### Simulation Model Quotes

1. **On Neural Networks and Inventory Optimization:**
    
    - "RNN and other neural network models are typically represented in terms of tensors."
    - "Indeed, tensors are so important that Google even named its machine learning library as 'TensorFlow'."
2. **On the Importance of Tensorization:**
    
    - "Therefore, to achieve a significant speedup of the simulation model for large-scale inventory problems, a critical step that we learned from the success of RNN is the tensorization of the simulation model."

### Matrix Representation of BOM Quotes

1. **On Bill of Materials (BOM):**
    
    - "A BOM is a list of raw materials, sub-assemblies and their quantities and manufacturing relations needed to manufacture the final products."
    - "Because we consider general inventory systems in this paper, the BOMs of these systems may be represented by complex directed networks."
2. **On Computational Efficiency:**
    
    - "However, according to our observations of practical large-scale supply chains, the adjacency matrix is typically very sparse. In fact, sparsity is a common feature of large-scale complex networks in the real world."

### Tensorization of the Simulation Model Quotes

1. **On Representing Variables:**
    
    - "With these vectors and the adjacency matrix, the equations introduced in Section 2.1 can be rewritten in the form of vector and matrix operations."
2. **On the Complexity of Operations:**
    
    - "Computational complexity is often used to understand the efficiency of an algorithm and to compare the efficiency of different algorithms."

### Complexity Analysis Quotes

1. **On Computational Complexity and Efficiency:**
    - "Using the sparse matrix techniques to handle the adjacency matrix, the complexity is O(T ρn²)."
    - "This is a significant reduction especially when handling large-scale inventory systems, where n is in the orders of 10⁴ to 10⁵."

### Gradient Estimation Methods

1. **Gradient Estimation Methods:**
    
    - "The simplest method for gradient estimation may be finite difference approximations. It is easy to understand and implement. However, it produces biased estimators and the computation time is prohibitively long..."
2. **Infinitesimal Perturbation Analysis (IPA):**
    
    - "IPA is one of the most important gradient estimation methods in the field of stochastic simulation..."
3. **Back Propagation Algorithm:**
    
    - "The idea of the BP algorithm is to compute the gradient using a reverse mode, after finishing the calculation of the function value. It is different from the IPA algorithm, which uses a forward mode to calculate the gradient alongside the calculation of the function value."
4. **Computational Complexity:**
    
    - "The computational complexities of lines 2-4 and 8 are O(n), and those of lines 6-7 and 10-12 are O(1) and they are executed O(n) times in each period. Therefore, the computational complexity of Algorithm 3 is O(Tn)."
5. **Gradient Estimation in Large-Scale Systems:**
    
    - "Numerical results also show that for large-scale inventory systems, gradient estimation using IPA is rather time-consuming. In order to meet the needs of further simulation optimization, more efficient gradient estimation methods need to be considered."

### General Performance of Algorithms

1. **Performance Comparison:**
    
    - "We test the performance of our algorithms... to compare it with the GS model of Graves and Willems (2000) on small- to medium-scale problems."
2. **Computational Complexity:**
    
    - "The computational complexities of the traditional algorithm and the tensorized algorithm with dense matrices are approximately O(n²), while that of the tensorized algorithm with sparse matrices is approximately O(n)."
3. **Efficiency of Algorithms:**
    
    - "Even though tensorization does not improve the computational complexity, it reduces the computational time significantly."
4. **TensorFlow Implementation:**
    
    - "One major impediment to the use of our algorithms in general inventory optimization is the construction of the computational graph and the derivation of the sample