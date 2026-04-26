# Phone-Now-Telecom-Customer-Churn-Analysis
This project focuses on helping businesses prevent customer loss and improve customer service.

## Key Features:

📌 Predictive Churn Modeling: Identify at-risk customers before they churn, enabling proactive interventions and retention strategies.

📌 Customer Segmentation: Group customers based on shared characteristics and churn risk, allowing for targeted marketing and engagement efforts.

### What is Customer Churn?
Customer churn refers to the phenomenon where customers or subscribers stop engaging with or doing business with a company or service.

### What is a Churn Rate?
Churn Rate, sometimes known as attrition rate, is the rate at which customers stop doing business with a company over a given period. Churn may also apply to the number of subscribers who cancel or don’t renew a subscription. The higher your churn rate, the more customers stop buying from your business. The lower your churn rate, the more customers you retain. Typically, the lower your churn rate, the better.

*Churn Rate = (Churned Customers / Total Number of Customers) x 100%*

PhoneNow Telecoms, a big player in the telecommunications industry provide Service Subscriptions to customers. They also keep records customer information, which includes, customer Demographics, Account Information, and Service Subscriptions. In the telecommunications industry, customers have numerous service providers to choose from, making it easy for them to switch from one provider to another. This has led to an annual churn rate of 27% in this highly competitive market. 
From Client Perspective:
It can lead to:

•	Financial Risk: High-churn customers might pose a financial risk, especially if they contribute significantly to revenue (high TotalCharges or MonthlyCharges).

•	Operational Risk: Customers raising numerous numAdminTickets or numTechTickets might indicate service dissatisfaction or operational inefficiencies.

•	Behavioral Risk: Customers on month-to-month contracts or without bundled services might be more likely to churn, representing a retention risk.

### As a data analyst my role was to Design a multi-layered BI solution to:
•	Identify churn patterns 

•	Feature analysis (what causes churn)

•	Why are customers leaving? - Customers with higher churn rates may have specific contract types, high monthly charges, or a lack of certain services like tech support or online security.

•	Which users are at risk?  - Senior citizens or customers with shorter tenure could exhibit distinct churn behaviours.

•	Build a simple prediction model

•	Suggest - How to reduce churn?


### The dashboard should help the Stakeholders to:
•	By integrating predictive models and visualizing the data, businesses can proactively mitigate risks by tailoring retention campaigns or optimizing service quality.

•	Using this information, strategies can be developed to improve retention by targeting at-risk groups, improving service offerings, or addressing pain points.

### Dataset Overview
Dataset consisting of 7,043 rows and 23 columns of PhoneNow Telecoms

### 1.	Customer Demographics:
   
    •	customerID: Unique identifier for each customer.
  	
    •	gender: Gender of the customer.
  	
    •	SeniorCitizen: Indicates whether the customer is a senior citizen (1 = Yes, 0 = No).
  	
    •	Partner and Dependents: Whether the customer has a partner or dependents.
  	
### 2.	Account Information:
   
    •	tenure: Number of months the customer has stayed with the company.
  	
    •	Contract: Type of contract (e.g., Month-to-month, One year, Two year).
  	
    •	PaperlessBilling: Whether the customer uses paperless billing.
  	
    •	PaymentMethod: Payment method used by the customer.
  	
### 3.	Services Signed Up:
   
    •	PhoneService and MultipleLines: Whether the customer has phone service and multiple lines.
    
    •	InternetService: Type of internet service (DSL, Fiber optic, None).
    
    •	Services  as OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport,  StreamingTV, and StreamingMovies.

### 4.	Charges:
   
    •	MonthlyCharges: The monthly amount charged to the customer.

    •	TotalCharges: The total amount charged to the customer.

### 5.	Customer Interaction:

    •	numAdminTickets and numTechTickets: Number of administrative and technical support tickets raised by the customer.

### 6.	Churn:
	
    •	Churn: Indicates whether the customer churned (Yes = churned, No = retained).

    



