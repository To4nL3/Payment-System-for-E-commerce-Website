# **Part 1: Planning**

## **1.1 Introduction About the Problem Domain**

People like to shop online because it is efficient. Moreover, they do not have to go out to physical stores in order to buy the products they need. However, it is not easy for the owner of an e-commerce store to provide customers with fast and convenient services. Setting up a secure online payment process can be challenging as it requires continuous monitoring and improvements.

Nowadays, e-commerce has various payment methods that offer low transaction fees, have various currency options, and provide cashless services. This system is being developed to satisfy this demand by online retailers and to serve the consumer with fast and convenient checkout services.

## **1.2 System Request**

**System Request: Payment System for E-Commerce Website**

**Project Sponsor: Doug McMillon, the president of Marketing**

**Business need:** This system is being developed for an online retailer/e-commerce business and is aimed at providing an efficient payment system for consumers.

**Business Requirements  
**

Two kinds of users can access the system. They are customers and business owners.  

1\. **Customers**:

- Customers fill out the order, payment, and other necessary information on the “checkout” page and click the “submit” button to finalize their purchase.

2\. **Business Owners:**

- The owner of the online store will have access to the transaction history, which includes the names, addresses, phone numbers, amount paid, and payment information of all customers’ transactions. They will also be able to modify the transactions in case of cancellations or errors.

**Business Value**

The internet allowed for the creation and popularization of e-commerce websites/services. Additionally, it has greatly increased in popularity in the past decade, driving online sales to new heights. Therefore, an effective payment system is imperative to any modern-day online retailer.

By improving our payment system using end-to-end encryption with SSL Certificate and a third-party gateway to secure payments across all e-commerce websites using this service gives our business unlimited potential for growth.

in every transaction they make. (By using a secure third-party gateway in every transaction people will be more likely to purchase things online.)

## **1.3 Feasibility Analysis**

**Technical Feasibility**

The payment system is feasible technically, although there are some risks.

_The project risk regarding familiarity with payment systems is medium:_

- The processes and necessary functions of the payment system are known and understood.
- The methodology and steps needed for full functionality of the necessary functions is not clear.
- Knowledge of the finance and banking/payment industry is limited.

_The project risk regarding familiarity with technology needed to create the system is medium:_

- All seven members of the team developing this system have some experience with software engineering.
- The entire team has the knowledge to create and implement small Java/Python programs and understand the basics of programming.
- This is not the first time this system has been created; detailed information is publicly available on the internet for reference by the team.

_The project risk regarding the project size is medium:_

- This project is being created by a team of seven members over the course of 2 ½ months.
- Time allocated to the project should be enough to complete it in time for the deadline.
- The system is straightforward and does not require any complex and time-consuming technologies and methods.

_The compatibility with the current system should be good:_

- The difficulty of integration is relatively low since it is a payment system. Website builders and programming languages have the necessary capabilities for smooth integration.
- The system uses a simple database to store basic transactional data for the administrators to view.

**Economic Feasibility**

In terms of costs, there will be none.

Benefits: (1) An increase in the efficiency of the payment process for customers. (2) The increase in security given that there is no reliance on any third-party payment portals, like Amazon, or PayPal. (3) An increase in engagement with the website now that there is a secure and quick easy to make transactions with the e-business.

The overall ROI will be a net positive, considering there will be no money spent on this system and all the benefits it brings.

**Organizational Feasibility**

From an organizational perspective, this project has low risk.

The overall goal of the project aligns with the goals of the business owners: to increase their customer base and to increase the efficiency of their checkout process while decreasing costs. It will also provide ample customer information to the business owners for future use and reference.

The users, AKA customers, will benefit and greatly appreciate the new payment system. It is designed for convenient use by customers while also providing benefits to the business owners.

## **1.4 Requirements Definitions**

**Non-functional requirements:**

**1.** **Operational requirements:**

- The system should scale correctly to support high traffic load.
- The system should provide secure payment to process each transaction.

**2\. Performance Requirements:**

- None

**3\. Security Requirements:**

- There is a unique account for administrators.
- Users must use username and password to access their account information.
- Every user should pass through a secure third-party gateway to process transactions.

**4\. Cultural and political Requirements:**

- None

**Functional Requirements:**

1. **Log In:**

- Users will have the ability to input their email and password to log in.
- There will be a forgot password button in case the user has forgotten their password.

1. **Input Payment Information:**

- Users will be able to input their method of payment into the system. Information will include: first and last name for the payment method, credit/debit card number, CVV number on back of the card, and billing address.
- After the user enters the payment information, the system will securely process the transaction.

1. **Management:**

- The electronic device or server provided by the payment gateway provider that interacts with the point of sale for the payment transactions. The payment gateway device should offer an API, application programming interface, that allows the point of sales system to request payment transactions.
- The payment transactions are managed by the payment gateway device and can be accepted or rejected. Payment gateway devices can also manage refunds.
- The service should support all types of payments.

1. **Maintain Payment Information:**

- The system will be able to store the user’s payment information.
- The necessary security protocols will be enforced in the system to prevent data breaches.

#
