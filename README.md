
## 📊 Customer Churn Analysis Dashboard

### 📝 Overview

This repository hosts the **Customer Churn Analysis Dashboard**, a data visualization project built using **Tableau**. The dashboard is designed to help businesses understand the factors contributing to customer churn (the rate at which customers stop doing business with a company) and identify key segments that are most at risk.

The analysis provides actionable insights into customer behavior across various dimensions, including gender, contract type, tenure, internet service, and senior citizen status.

-----

### 🌐 Live Interactive Dashboard

Click the link below to view and interact with the full Customer Churn Analysis Dashboard on Tableau Public. This provides the best experience for exploring the data and utilizing all the interactive filters and tooltips.

👉 https://public.tableau.com/views/CustomerChurnAnalysisDashboard_/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

-----


### 💾 Data Source

The analysis is based on a simulated or anonymized **telecom customer dataset**.
* **Source:** [Telecom Customer Churn Dataset from Kaggle]
* **Link:** [https://www.kaggle.com/code/danishmubashar/telco-customer-churn-99-acc]

  * **Key Data Fields:**
      * `Gender`
      * `Senior Citizen`
      * `Tenure (in months)`
      * `Contract Type`
      * `Internet Service`
      * `Payment Method`
      * `Monthly Charges`
      * `Churn` (Target variable: Yes/No)

-----

### 🔍 Key Analysis Highlights

The dashboard visualizes churn rates across several critical dimensions. Key findings summarized in the visualizations include:

  * **Contract Type Impact:** Customers on a **Month-to-month** contract show significantly higher churn rates compared to those with **One year** or **Two year** contracts.
  * **Internet Service Influence:** Customers with **Fiber optic** internet service have the highest churn rate.
  * **Tenure Group Analysis:** The highest churn rate is observed in the **0-12 month** tenure group.
  * **Payment Method Risk:** The **Electronic check** payment method is highly correlated with churn.
  * **Senior Citizen Status:** A higher percentage of **Senior Citizens** churn compared to non-senior citizens.
  * **Monthly Charges Distribution:** The average tenure is lower for customers who have churned, and their Monthly Charges distribution appears different from those who haven't.

-----

### 💻 Technology & Tools

  * **Primary Tool:** **Tableau Desktop** (for data connection, preparation, visualization design, and dashboard creation).
  * **Programming Language (Optional):** None for the dashboard itself, but if any data cleaning/preprocessing was done (e.g., Python/R), mention it here.
  * **Dataset:** CSV/Excel file used for input.

-----

### 🖼️ Dashboard Components

The final dashboard consists of multiple interconnected visualizations:

1.  **Summary KPIs:** Overall Churn Rate, Total Customers, Churned Customers, etc. (Top metrics)
2.  **Churn by Gender (Bar Chart):** Compares churn rates between male and female customers.
3.  **Churn by Contract Type (Bar Chart):** Shows the high impact of month-to-month contracts on churn.
4.  **Monthly Charges Distribution (Box Plot):** Compares the distribution of monthly charges and tenure for churned vs. non-churned customers.
5.  **Churn by Tenure Group (Bar Chart):** Highlights churn risk based on the duration of the customer relationship.
6.  **Payment Method Heatmap:** Visualizes which payment methods are most associated with a churn value of `1.000` (Yes).
7.  **Churn by Internet Service (Bar Chart):** Compares churn based on DSL, Fiber Optic, and no internet service.
8.  **Churn by Tenure Bands (Bar Chart):** More granular look at churn rates across specific tenure years (0-1 year, 1-2 years, etc.).
9.  **Senior Citizen Churn (Donut/Pie Chart):** Visual comparison of churn rates for senior citizens vs. non-senior citizens.

-----

### 🚀 Usage and Deployment

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/tejalubale26/Customer-Churn-Analysis-Tableau-Dashboard]
    ```
2.  **Access the Dashboard:** The main file is the Tableau Workbook (`.twb` or `.twbx` file), which can be opened using **Tableau Desktop** or **Tableau Reader** (if saved as a `.twbx`).
3.  **Explore the Insights:** Interact with the dashboard to filter and drill down into the data to explore the relationships between customer attributes and churn.
