# CustomerChurnANN

#### https://nbviewer.jupyter.org/github/noopurm912/CustomerChurnANN/blob/main/CustomerChurnANNScientificComputingII_273784.ipynb

### Customer Churn Prediction using ANN
##### Churn is defined as the loss of a customer or a client from any bussiness. Churn rate is a measure of the number of customers leaving a collective group over a specific period. Traditionally, bussinesses can only know about the customers leaving only when they show their intentions to the company then customer retention is the solution to customer churn by providing different offers or the best solution possible. Churn prediction analysis is critical to predict the possiblity of a customer leaving even before they express their intentations. The companies can offer or improve the current services to retain their customers. The goal is to understand and take steps to change it before the costumer gives up the product or service. The customer data can be analyze the pattern or any important information to predict the customer churn. We can use classification algorithm or Artificial Neural Network model to make those prediction.
##### Data Source : https://www.kaggle.com/blastchar/telco-customer-churn
#### Data Dictionary: 
##### customerID : Unique Customer ID
##### gender : Gender of the Customer(male or female)
##### SeniorCitizen : Whether the customer is a senior citizen or not (1, 0)
##### Partner : Whether the customer has a partner or not (Yes, No)
##### Dependents : Whether the customer has dependents or not (Yes, No)
##### tenure : Number of months the customer is with the company
##### PhoneService : Whether the customer has a phone service or not (Yes, No)
##### MultipleLines : Whether the customer has multiple lines or not (Yes, No, No phone service)
##### InternetService : Customer’s internet service provider (DSL, Fiber optic, No)
##### OnlineSecurity : Whether the customer has online security or not (Yes, No, No internet service)
##### OnlineBackup : Whether the customer has online backup or not (Yes, No, No internet service)
##### DeviceProtection : Whether the customer has device protection or not (Yes, No, No internet service)
##### TechSupport : Whether the customer has tech support or not (Yes, No, No internet service)
##### StreamingTV : Whether the customer has streaming TV or not (Yes, No, No internet service)
##### StreamingMovies : Whether the customer has streaming movies or not (Yes, No, No internet service)
##### Contract : The contract term of the customer (Month-to-month, One year, Two year)
##### PaperlessBilling : The statys of paperless billing (Yes, No)
##### PaymentMethod : Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic) used by customer
##### MonthlyCharges : The monthly amount charged to the customer 
##### TotalCharges : The total amount charged to the customer
##### Churn : Whether the customer churned or not (Yes or No)(Target Variable)
=============================================================
### Artificial Neural Network: 
##### Artificial neural networks (ANNs),also called as neural networks (NNs), are computing systems inspired by the the neural Networks in our brain. An ANN is a collection of connected units or nodes also called neurons, which loosely model the neurons in a biological brain. Deep learning uses artificial neural networks that behaves similarly to the neural networks in our brain. A neural network works when some input data is fed to it and this data is processed via layers of perceptron to produce a output.

##### Keras: Keras is a powerful and easy-to-use Python library for developing and evaluating deep learning models. It wraps the efficient numerical computation libraries such as TensorFlow and allows to define and train neural network models.
#####  https://keras.io/guides/sequential_model/
##### Step:
##### Define Keras Model.
##### Compile Keras Model.
##### Fit Keras Model.
##### Evaluate Keras Model.
##### Make Predictions
