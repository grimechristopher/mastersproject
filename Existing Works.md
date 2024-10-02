
## While my paper is not concerned with maintenance I am concerned with accurately determining the RUL 

Tao Yan, Yaguo Lei, Naipeng Li, Xiaosheng Si, Liliane Pintelon, Reginald Dewil,
Online joint replacement-order optimization driven by a nonlinear ensemble remaining useful life prediction method,
Mechanical Systems and Signal Processing,
Volume 173,
2022,
109053,
ISSN 0888-3270,
https://doi.org/10.1016/j.ymssp.2022.109053.
(https://www.sciencedirect.com/science/article/pii/S0888327022002254)
Abstract: Remaining useful life (RUL) prediction and maintenance optimization are two critical and sequentially connected modules in the prognostics and health management of machines. Due to the advantages of obtaining more accurate RUL prediction results and the effectiveness of addressing replacement scheduling and spare parts provision dynamically, ensemble RUL prediction and online joint replacement-order optimization are paid specific attention to. Despite substantial works on those two aspects, there are still two limitations that compromise their performances in practical applications: 1) Existing ensemble RUL prediction methods neglected the nonlinear relationships among individual prediction models. 2) No online joint optimization model that utilizes ensemble RUL information is available. Faced with these two limitations, this paper first proposes a nonlinear ensemble RUL prediction method, which takes nonlinear relationships among models into consideration. Furthermore, an online joint replacement-order model is formulated using the ensemble RUL prediction results, and an iterated local search-based optimization algorithm is utilized for dynamically finding the near-optimal joint policies. Through the experimental study of milling cutter life tests, the proposed nonlinear ensemble RUL prediction method is verified with higher accuracy, and the joint optimization model utilizing the ensemble RUL results is shown to provide more effective joint policies.
Keywords: Nonlinear ensemble; Online joint optimization; Prognostics and health management of machine; Remaining useful life prediction


## Another paper I like discussing method of ordering spare part optimization
Like Zhang, Qianwang Deng, Bingxin Miao, Xiaoyan Liu, Haidong Shao,
Parallel service mode of production and inventory for spare part inventory optimization,
Knowledge-Based Systems,
Volume 241,
2022,
108282,
ISSN 0950-7051,
https://doi.org/10.1016/j.knosys.2022.108282.
(https://www.sciencedirect.com/science/article/pii/S0950705122000892)
Abstract: Previous studies on inventory adopt the serial supply mode of “from production to inventory to customer demand”, that is, at the end of the previous period, the spare parts requirements predicted for the next period need to be ready. Trying to cancel the preparation of some spare parts in the previous period and transfer them to the production resources in the next period, the capital occupation and inventory holding cost incurred by these spare parts can be reduced. Therefore, we propose a parallel service mode of production and inventory for inventory optimization, in which production resources are arranged from the scheduling level and cooperate with inventory to meet customer demands. By introducing virtual warehouses that each contains infinite spare parts, the problem of inventory optimization is transformed into a scheduling problem with objectives of minimum inventory capital occupation and minimum total cost including inventory holding cost, transportation cost and tardiness cost. The optimal inventory setting of each actual warehouse is determined based on the usage of spare parts in each corresponding virtual warehouse in the optimal scheduling solution. To obtain the optimal scheduling solution, an evolutionary algorithm is proposed, in which a modified idle time insertion method and five problem-specific knowledge-guided local search operators are developed. Numerous experiments are conducted and the results demonstrate the effectiveness of the proposed algorithm compared with other well-known algorithms. Furthermore, the superiority of the parallel service mode compared with the serial supply mode is verified.
Keywords: Parallel; Inventory; Production scheduling; Distributed flowshop; Spare parts


## Same industry, Same idea!!

Willem van Jaarsveld, Twan Dollevoet, Rommert Dekker,
Improving spare parts inventory control at a repair shop,
Omega,
Volume 57, Part B,
2015,
Pages 217-229,
ISSN 0305-0483,
https://doi.org/10.1016/j.omega.2015.05.002.
(https://www.sciencedirect.com/science/article/pii/S0305048315001024)
Abstract: We study spare parts inventory control for an aircraft component repair shop. Inspection of a defective component reveals which spare parts are needed to repair it, and in what quantity. Spare part shortages delay repairs, while aircraft operators demand short component repair times. Current spare parts inventory optimization methods cannot guarantee the performance on the component level, which is desired by the operators. To address this shortfall, our model incorporates operator requirements as time-window fill rate requirements for the repair turnaround times for each component type. In alignment with typical repair shop policies, spare parts are allocated on a first come first served basis to repairs, and their inventory is controlled using (s, S) policies. Our solution approach applies column generation in an integer programming formulation. A novel method is developed to solve the related pricing problem. Paired with efficient rounding procedures, the approach solves real-life instances of the problem, consisting of thousands of spare parts and components, in minutes. A case study at a repair shop reveals how data may be obtained in order to implement the approach as an automated method for decision support. We show that the implementation ensures that inventory decisions are aligned with performance targets.
Keywords: Spare parts inventory control; (s, S) policies; Case study; Assemble-to-order systems

## Somewhat related "Spare parts management for irregular demand items"
Francesco Costantino, Giulio Di Gravio, Riccardo Patriarca, Lea Petrella,
Spare parts management for irregular demand items,
Omega,
Volume 81,
2018,
Pages 57-66,
ISSN 0305-0483,
https://doi.org/10.1016/j.omega.2017.09.009.
(https://www.sciencedirect.com/science/article/pii/S0305048316309161)
Abstract: Inventory optimization of high-value spare parts may generate a significant reduction of cost to allow a better allocation of resources in maintenance management. Sherbrooke's METRIC (Multi Echelon Technique for Recoverable Item Control) is the most common method to define an overall optimization process adopting a system-approach. Its main assumption consists of adopting a Poisson distribution to describe the demand pattern of the items. However, many studies proved that in high-availability systems, high-cost spare parts often follow irregular demand patterns, with very frequent zero-demand values. For this purpose, we propose an innovative model for a single site, the ZIP-METRIC, to take advantage of a distribution yet widely adopted in the healthcare and biological sciences, i.e. the Zero-Inflated Poisson. A case study of 1745 items of a European airline fleet demonstrates the model effectiveness, confirming that the ZIP-METRIC outperforms the traditional Poisson-based approach.
Keywords: Inventory management; Logistic; Intermittent demand; Lumpy demand; Zero-inflated model


# Simulation based method for predicting when parts will fail. Interesting though probably not applicable since we are working with historical failure data
Pankaj Sharma, Makarand S Kulkarni, Vikas Yadav,
A simulation based optimization approach for spare parts forecasting and selective maintenance,
Reliability Engineering & System Safety,
Volume 168,
2017,
Pages 274-289,
ISSN 0951-8320,
https://doi.org/10.1016/j.ress.2017.05.013.
(https://www.sciencedirect.com/science/article/pii/S0951832016306718)
Abstract: Equipment of the Army encounters various modes of exploitation depending on the scenario in which it is used. Typically, the missions are followed by intervals which can be used for maintenance. This is a suitable condition for employment of selective maintenance strategy. However, this maintenance interval is bound by the constraints of time, resources and desired reliability before the start of the next mission. This calls for optimization of maintenance activities that can be fitted into the maintenance break. There is also a requirement of having a forecasting technique for reducing the supply lead times. This paper lays out a methodology to use simulation for predicting failures in the army equipment. A Genetic Algorithm (GA) based approach is then used for optimizing the maintenance activities before the start of the maintenance break. The process of Simulation plus GA Optimization is automated using a program in MATLAB. The novelty of the work lies in modifying the process of Simulation and GA Optimization to suit the exact modus operandi employed by the Army in deploying equipment for peace, training exercise and war (mission with or without some maintenance break) separately. In addition to optimizing the maintenance activities, the methodology also helps in forecasting the requirement of spare parts both before and during the mission.
Keywords: Mission reliability; Simulation; Genetic algorithm; Army; Failure simulation; Spare parts forecasting


# # A double-level combination approach for demand forecasting of repairable airplane spare parts based on turnover data --- Uses aircraft data and neural networks and problem matches up perfectly
Feng Guo, Jun Diao, Qiuhong Zhao, Dexin Wang, Qiang Sun,
A double-level combination approach for demand forecasting of repairable airplane spare parts based on turnover data,
Computers & Industrial Engineering,
Volume 110,
2017,
Pages 92-108,
ISSN 0360-8352,
https://doi.org/10.1016/j.cie.2017.05.002.
(https://www.sciencedirect.com/science/article/pii/S036083521730195X)
Abstract: To address the problem that the demand forecasting methods for repairable airplane spare parts are not advanced, and that the basic forecasting data are not consistent with actual consumption, this paper proposes a double-level combination forecasting approach for repairable spare parts based on relevant data. First, we conduct an analysis for the factors that influence the demand of repairable spare parts. Second, five types of individual direct forecasting models are combined to establish a double-level combination forecast model, which is superior to both individual combination forecasting models and individual direct forecasting models. Finally, we evaluate the forecasting performance by utilizing consumption data for an aircraft fleet and turnover data for an aircraft. The forecasting results provide strong evidence that that the double-level combination forecast model is more accurate and consistent with actual demand.
Keywords: Demand forecasting; Repairable airplane spare parts; Double-level combination forecast; Genetic neural network; Exponential smoothing; Grey model


## Using an RNN to determine demand levels
Hossein Abbasimehr, Mostafa Shabani, Mohsen Yousefi,
An optimized model using LSTM network for demand forecasting,
Computers & Industrial Engineering,
Volume 143,
2020,
106435,
ISSN 0360-8352,
https://doi.org/10.1016/j.cie.2020.106435.
(https://www.sciencedirect.com/science/article/pii/S0360835220301698)
Abstract: In a business environment with strict competition among firms, accurate demand forecasting is not straightforward. In this paper, a forecasting method is proposed, which has a strong capability of predicting highly fluctuating demand data. Therefore, in this paper we propose a demand forecasting method based on multi-layer LSTM networks. The proposed method automatically selects the best forecasting model by considering different combinations of LSTM hyperparameters for a given time series using the grid search method. It has the ability to capture nonlinear patterns in time series data, while considering the inherent characteristics of non-stationary time series data. The proposed method is compared with some well-known time series forecasting techniques from both statistical and computational intelligence methods using demand data of a furniture company. These methods include autoregressive integrated moving average (ARIMA), exponential smoothing (ETS), artificial neural network (ANN), K-nearest neighbors (KNN), recurrent neural network (RNN), support vector machines (SVM) and single layer LSTM. The experimental results indicate that the proposed method is superior among the tested methods in terms of performance measures.
Keywords: Demand prediction; Time series forecasting; Statistical methods; LSTM; RNN


##Another paper that mentions # Poisson Bayesian
M.Z. Babai, H. Chen, A.A. Syntetos, D. Lengu,
A compound-Poisson Bayesian approach for spare parts inventory forecasting,
International Journal of Production Economics,
Volume 232,
2021,
107954,
ISSN 0925-5273,
https://doi.org/10.1016/j.ijpe.2020.107954.
(https://www.sciencedirect.com/science/article/pii/S0925527320303078)
Abstract: Spare parts are often associated with intermittent demand patterns that render their forecasting a challenging task. Forecasting of spare parts demand has been researched through both parametric and non-parametric approaches. However, little has been contributed in this area from a Bayesian perspective, and most of such research is built around the Poisson demand distributional assumption. However, the Poisson distribution is known to have certain limitations and, further, empirical evidence on the inventory performance of Bayesian methods is lacking. In this paper, we propose a new Bayesian method based on compound Poisson distributions. The proposed method is compared to the Poisson-based Bayesian method with a Gamma prior distribution as well as to a parametric frequentist method and to a non-parametric one. A numerical investigation (on 7400 theoretically generated series) is complemented by an empirical assessment on demand data from about 3000 stock keeping units in the automotive sector to analyse the performance of the four forecasting methods. We find that both Bayesian methods outperform the other methods with a higher inventory efficiency reported for the Poisson Bayesian method with a Gamma prior. This outperformance increases for higher demand variability. From a practical perspective, the outperformance of the proposed method is associated with some added complexity. We also find that the performance of the non-parametric method improves for longer lead-times and higher demand variability when compared to the parametric one.
Keywords: Forecasting; Inventory; Intermittent demand; Bayesian method; Empirical investigation


## Possible use of machine learning for determining spare parts usage
József Dombi, Tamás Jónás, Zsuzsanna Eszter Tóth,
Modeling and long-term forecasting demand in spare parts logistics businesses,
International Journal of Production Economics,
Volume 201,
2018,
Pages 1-17,
ISSN 0925-5273,
https://doi.org/10.1016/j.ijpe.2018.04.015.
(https://www.sciencedirect.com/science/article/pii/S0925527318301701)
Abstract: In order to provide high service levels, companies competing in the electronics manufacturing sector need to ensure the availability of spare parts for repair and maintenance operations. This paper examines the purchase life-cycles of electronic spare parts and presents a new way of modeling and forecasting spare part demand for electronic commodities in the spare parts logistics services. The presented modeling methodology is founded on the assumption that the purchase life-cycles of spare parts can be described by a curve with short term fluctuations around it. For this purpose, a flexible Demand Model Function is introduced. The proposed forecasting method uses a knowledge discovery-based approach that is built upon the combined application of analytic and soft computational techniques and is able to indicate the turning points of the purchase life-cycle curve. The novelty lies in the fact that the model function has certain characteristics which support describing and interpreting the demand trend as a function of time. The application of our methodology is mainly advantageous in long-term forecasting, it can be especially useful in supporting purchase planning decisions in the ramp-up and declining phases of purchase life-cycles of product specific spare parts. A demonstrative example is used to illustrate the applicability of the proposed methodology. Its forecasting capability is compared to those of some widely applied methods in business practice. From the results, the new method may be viewed as a viable alternative spare part demand forecasting technique in spare part logistics sector.
Keywords: Spare part logistics; Electronic aftermarket services; Purchase life-cycle forecasting; Knowledge discovery; Clustering time series




## Good background on topic substation Equipment Spare Parts’ Inventory Prediction Model Based on Remaining Useful Life

Tang, Bing, Ma, Zhenguo, Zhang, Keqi, Cao, Danyi, Zhang, Jianyong, Substation Equipment Spare Parts’ Inventory Prediction Model Based on Remaining Useful Life, _Mathematical Problems in Engineering_, 2022, 3396850, 11 pages, 2022. [https://doi.org/10.1155/2022/3396850](https://doi.org/10.1155/2022/3396850)

### BOOK: INVENTORY ANALYTICS

## Interesting paper ### [==Inventory== optimization in large scale multi-echelon ==spare parts inventory== systems](https://csu-fullerton.primo.exlibrisgroup.com/discovery/fulldisplay?docid=cdi_proquest_journals_305026305&context=PC&vid=01CALS_FUL:01CALS_FUL&lang=en&search_scope=everything_filtered&adaptor=Primo Central&tab=Everything_custom&query=any%2Ccontains%2Ccalculating%20warehouse%20demand%20inventory%20spare%20parts&offset=0)


###### [Methodology to calculate the required number of spare parts in order to ensure the required operability of equipment parks](https://csu-fullerton.primo.exlibrisgroup.com/discovery/fulldisplay?docid=cdi_proquest_journals_2512957396&context=PC&vid=01CALS_FUL:01CALS_FUL&lang=en&adaptor=Primo Central&tab=Everything_Rapido&query=any%2Ccontains%2Ccalculate%20spare%20parts&offset=0) 
## Similar idea to what I am thinking but not exactly
# Methodology to calculate the required number of spare parts in order to ensure the required operability of equipment parks

B G Kim1 and Z N Shakir2

Published under licence by IOP Publishing Ltd  
[IOP Conference Series: Materials Science and Engineering](https://iopscience.iop.org/journal/1757-899X), [Volume 1103](https://iopscience.iop.org/volume/1757-899X/1103), [International Scientific Conference Interstroymeh (ISM 2020) 17th-18th December 2020, Samara, Russia](https://iopscience.iop.org/issue/1757-899X/1103/1) **Citation** B G Kim and Z N Shakir 2021 _IOP Conf. Ser.: Mater. Sci. Eng._ **1103** 012010 **DOI** 10.1088/1757-899X/1103/1/012010

https://iopscience.iop.org/article/10.1088/1757-899X/1103/1/012010/pdf




## Another RNN Large-Scale Inventory Optimization: A
Recurrent-Neural-Networks-Inspired Simulation
Approach


## Book # Demand-Driven Inventory Optimization and Replenishment: Creating a More Efficient Supply Chain