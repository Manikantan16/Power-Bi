# Power-Bi
Power BI is a business analytics tool developed by Microsoft. It helps users visualize and analyze data, share insights, and make data-driven decisions. Power BI can connect to various data sources—like Excel, databases, online services, and more—and transform that data into interactive reports and dashboards.

### There are three main components to Power BI:

#### Power BI Desktop 
  - A free, downloadable application where you can create and design reports and dashboards.
#### Power BI Service 
  - An online platform for sharing, collaborating, and distributing reports and dashboards across teams and organizations.
#### Power BI Mobile 
  - An app that allows users to access and interact with reports and dashboards on mobile devices.

#### About this project

#### Brief Overview
 - 📊 Completed a Power BI Desktop project that focused on analyzing customer churn rates.
 - The project included developing an interactive dashboard to visualize and explore churn patterns, taking into account various customer demographics and financial metrics.

#### Project Structure
 - The project on customer churn rate analysis included the following tasks:
 - 1st imported the Churn Data to the PowerBI Desk
 -  Transformed the data by following the below steps:
     -  customer_id: ID of the customer
     -  **surname:** (Not relevant for visulatisation, hence deleted from the dataset)
     -  credit_score: (credit score) of the customer
     -  Geography : Country of the customer
     -  gender: Gender of the customer (Male or Female)
     -  age: Age of the customer
     -  tenure: Number of years the customer has been with the bank
     -  balance: Account balance
     -  NumOfProducts: Product categorized by number
     -  HasCrCard: Whether the customer owns (1) or does not down (0) a credit card
     -  IsActiveMember: 1 for Active customers, 0 for Inactive customers
     -  **estimated_salary:** Salary of the customer (Not relevant for visulatisation, hence deleted from the dataset)
     -  Churned: Whether the customer has left the bank (1 for churned, 0 for not churned)
     -  Add column from example: Created a new column for product names (e.g., Products Prod 1, Prod 2, etc.).
      **Replace values:**
         - Replaced credit card status values with 'Owned' (1) or 'Not Owned' (0).
         - Replaced IsActiveMember values with 'Active' (1) or 'Inactive' (0).

     - Added Additional  columns:
         - Created new columns for Age Bins, Credit Scores, and Account Balance categories.
           
            **Age_Bins:**
           
            ![image](https://github.com/user-attachments/assets/3c0fc892-a9c8-441e-9d8a-a1fceacb3180)
           
           **Credit_Score_Groups:**
           
           ![image](https://github.com/user-attachments/assets/523274e8-1a94-4c4d-b459-af4edd203726)
           
           **Balance_Bins:**
           
           ![image](https://github.com/user-attachments/assets/0b2789ee-af2c-4972-8c7b-f19eae14a241)
     
      - Defined measures:
          - In the report section, created measures for:<br/>
            - Number of customers (Customers)<br/>
            - Number of Customers lost (Churned)<br/>
            - Churned Rate<br/>
            ![image](https://github.com/user-attachments/assets/e0661c39-b7f3-4586-9222-cd21ae83b84a)

 **Synopsis**:<br/>
    - 📈 Successfully completed a comprehensive customer churn rate analysis project using Power BI Desktop. <br/>
    - 📊 Created various visualizations, including donut charts plots for Customers by  Gender,Status,Products,CreditCard,Geography credit score, country, gender, 
    Line and Clustered charts for (Customer and Churn Rate by Age_bins, Balance_Bins,CreditScore_Group .<br/>
    - 📉 Developed key performance indicators (KPIs) using DAX commands to measure the number of customers, number of customers lost, and churn rate. <br/>
    - 🎛️ Implemented interactive slicers based on various demographics to enhance data exploration. <br/>
    - 🛠️ Cleaned and preprocessed data using Power BI Query for accurate analysis. <br/>
   
   ![Churn_Analysis](https://github.com/user-attachments/assets/e244407a-b9dc-45bd-b6a1-59de826c5e4d)




