Hi everyone this in my planned project. I am planning to implement a neural network to help determine optimal inventory levels in companies. Particularly companies that do manufacturing and repairs. My presentation will discuss the background of calculating Inventory Levels, explain some of the traditional methods and newer machine learning methods as well as what will be required for an implementation

---
2
Inventory management consists of making sure you have enough of a product without also having too much. Having too much of a product means the company is wasting space storing a product. They aren't able to sell the products quick enough. This leads to waste and increased storage costs.

Not having enough inventory leads to the opposite problem, the company can't meet demands and will end up having delays in fulfilling orders. This is inefficient, it slows down business. If it happens often it will end up with customers losing confidence in the business. 

So the problem ends up being an optimization problem. We must minimize the amount of products stored while also ensuring that there are enough to meet the demand for orders.

---
3
Optimization is important because it leads to reduced storage costs, it increases customer confidence and it provides a competitive advantage. The advantage comes from lower operational costs and also less operational delays. 

--- 
4
What goes into determining the optimal or minimal inventory levels? Things like customer demand, lead time, which is the amount of time that it takes to receive parts, then there is also service level which is what percentage of orders you want to ensure you will always meet on time, which then helps determine safety stock levels.  Common service levels are 95% - 98%. 

---
Slide 5 ?????????

---
6
The focus of my project is going to be demand forecasting. I want to find a way to determine the demand for products as well as the point to reorder more. Demand forecasting is what slows companies to plan ahead and anticipate changes in demand, rather that is increased customer sales, economic changes. It helps them mitigate risk by identifying possible supply chain disruptions, and helps optimize the operation. These optimizations start  with just quantities of products on shelves but lead to better personnel management and logistics management. 

----
7
It sounds easy right? Order x  when we are at x levels. It turns out its not quite that easy. There are actually a ton of complexities that go into the calculation for product demand. 

Firstly we have sales trends. Sales trends can vary based off seasonality, sales growth, and cyclical fluctuations. In the commercial aerospace industry cyclical fluctuation can be important. 

There are economic factors, long term industry changes. 

Market trends change over time, the constant competition with competitors has an influence on demand as well. Even changes in customers productions plays a part. For example everyone is probably aware of Boeing's current issues. Boeing's issues are rippling throughout the industry. Less Boeing planes are coming off the line which is reducing the amount of orders for installations on new planes. 

The supply chain is also a big one especially over the last few years weve had many disruptions due to the pandemic. Theres also issues due to Natural disasters. Supply companies, logistical issues a few years ago that ship got stuck and blocked one of the major canals in the world which had a large effect on supply chains. 

So there are a lot of factors right here that already need to be considered. 

---
8
When you are a company that deals with repairs, you've just opened up another layer of complexity. Parts break abd must be repaired so now the ompany maust determine how often parts break. Those broken parts must be shipped bacck to the warehouse and when they arrive they need to be repaired. Companies do want broken parts waiting for more part so that they can be repaired and sent out. So products must be broken down into subparts when determining demand. Tracking this requires preety good data collection about the parts that broken down, how long theyve been in service and what sub parts had to be replaced. It also requires knowing how long parts take to ship and be repaired. 

--- 
9
Now we come to how companies currently determine product demand.

Firstly we have traditional methods. Traditionally companies use statistical models to determine the optimal inventory levels.

Some common methods I found through my research are ARMA models, Exponential Smoothing, and Poisson Processes. 

These models are very good for simpler supply chains. Exponential Smoothing is helpful for companies where trends are shifting over time. Poisson Processes are good for adding an element of randomness to the demand calculations. 

---
10
Theses statistical methods have been modified over time and improved. There are more advanced statistical methods that try to account for some of the complexities in demand forecasting. Particularly, interesting is the Poisson-Bayes method I found while researching. this method helps account for some more unusual order, it is fairly good for repairs forecasting. 

One technique listed here is Ensemble forecasting, which isn't necessarily a method itself but the combination of methods. This is actually still a very good method even today with neural networks. Its used by quite a few companies in other industries such as Netflix, they actually have a combination of different recommendation algorithms they use depending on the circumstances. So if I am able to, I think it would be a great addition to my project to try training and use a few different models. 

---
11
Why use Neural Networks or Machine Learning if there's already methods? Well they aren't perfect and the more complex, that means the more products,and different suppliers the company has the less effective the statistical methods are. 

The statistical methods also cant account for external factors such as supply chain disruptions or rapidly changing trends. 

The traditional methods struggle to forecast demand for irregularly ordered parts. They also fail when demand is non-linear. 

---
12
This brings us to using Machine Learning to forecast demand and in particular Neural networks. There are quite a few papers discussing the use of neural networks for this purpose and really they seem like a perfect fit for this kind of problem.

This problem consists of many inputs, tons of data and many relations between the data that isn't necessarily easy to uncover. They also can learn over time. They are able to recognize changes in the data so they can uncover many trends in real time. 

They can be hard to implement, especially for companies that dont have a ton of data. They require a lot of data and computational power.

---
13
I found two types of neural networks in my research. I found Recurrent Nueral Networks and Long Short Term Memory networks. RNNs are god for finding trends over time. They can also handle inconsistent demand changes, which makes them perfect for this project.

LSTMs are a modified RNNs. They have a mechanisms to remember or forgetring certain facts over time and are good at handling complex data sets. 

I plan to implement an RNN for my project and if possible also implement an LSTM. I am new to RNNs so it will be a few months of researching implementations over the next couple months. I do have a general idea and plan for what needs to be done. 

---
14
Firstly I need to do some data gathering, Historical sales data, market trends, repairs data. The data needs to be processed, cleaned up, outliers need to be removed missing data needs to be cleaned, The data needs to be time series formatted and also normalized. Next the model needs to be trained and then once the model is trained it needs to be tested for accuracy with current data. 

---
15
I will personally be using the following data. The company I work for is quite interested in this project and has said they will kindly be providing annonamized data to me. 

So I will be looking at historical sales, projected sales, repairs data (for example mean time between failure data) and also explore some real time data. This could be market or economic trends. 

---
16
Next there is data preparations and model training, I will be exploring various training methods and optimizations, I will also be exploring ways to integrate this project into a current system.

I hope to have a model that will take in the current date, current inventory quantities, and then output the products and the quantities that need to be ordered. 

--- 
17
In conclusion I hope this explained the problem I will tackle with my project. 

I hope that I can find and implement a neural network that is an improvement for companies looking to improve their demand forecasting.

Do we have any questions? 

