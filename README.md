# taxi_adhoc_EN

XYZ is the multi-service mobility joint venture

You are the Product Analyst who is helping the B2B Product team to better understand their business customer’ needs based on their performance :
Using the data please answer:
1. How do you define the business customer’ lifecycle based on the provided data? Clearly define the stages and relevant KPIs to measure the customer lifecycle
2. How would you segment our business customers and what segments are doing well?
3. Can you help us to identify the stage in which we have to fight for customer’ attention? Can you recommend any business initiatives or product changes that could help us to have customer life cycle progression?

1._Business_Customer
A table with data on Business Customers including:
● id_business: the business customer ID
● signup_date: the date when the business customer has signed up in XYZ
● signup_process_type: the business customers would be absorbed by sales managers or can sign up themself in XYZ business website
● business_type: It shows the business customer portfolio and it could be COMPANY , HOTEL or RESTAURANT
● country: Place where the business customer is located

2. _Business_Customer_employees
● id_business: the business customer ID
● id_employee : the employee id
● method: It shows how the employee has been connected to XYZ. It could be either by sending an invite or adding manually to the XYZ profile of a business customer.
● invite_date: the date when the employee has been invited to XYZ
● connection_date: the date when the employee has been connected to XYZ

3. _Business_Customer_Activity
A summary of the Business Customer’ activity including:
● id_ride : the ride id
● ride_date : the date when the business customer employee had a ride with XYZ mobilities
● id_employee : the employee id ( actual passenger)
● Id_business : it shows to which business customer the employee has been connected . A person can work for several companies and being connected to several XYZ business customers
● ride_value: the price which has been paid at the end in local currency
