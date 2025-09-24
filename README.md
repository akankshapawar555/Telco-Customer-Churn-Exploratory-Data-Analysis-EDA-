 # 📊 Telco Customer Churn – Exploratory Data Analysis (EDA)
 
 # 📌 Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset.The goal is to clean the data, explore customer behavior, and uncover key insights that explain why customers leave a telecom company.

 # 🎯 Objectives
  - Data Import & Cleaning
  - Data Preprocessing
  - Statistical Analysis
  - Data Visualization

 # 🛠️ Tools & Libraries
   - Python
   - Pandas (Data handling)
   - Matplotlib / Seaborn (Visualization)

# 📂 Dataset
  - Telco Customer Churn dataset (7,043 rows, 21 columns)
  - Key columns:
    - gender
    - tenure  (Customer’s length of stay (months))
    - MonthlyCharges  (Current monthly bill)
    - TotalCharges  (Total money paid by the customer)
    - Churn   (Target column (Yes = left, No = stayed))

# 📊 Key Analysis Areas

# 📈 Customer Tenure & Charges Distribution
# 📌 Insight:
  - Most customers leave early (low tenure).
  - Monthly charges mostly range between $20–$100.
  - Total charges are skewed many low-paying customers and few high-paying long-term ones.

    <img width="889" height="489" alt="image" src="https://github.com/user-attachments/assets/a59268ce-39bd-42b6-bc7a-d5c2efd43bd8" />

# 🚪 Overall Churn Count
# 📌 Insight:
  - About 26% customers churned.
  - Majority of customers stay, but churn is still a concern.

    <img width="633" height="449" alt="image" src="https://github.com/user-attachments/assets/f5cfcb45-bfab-46b6-a5c6-89f967801627" />

# 👨‍👩‍👧 Churn by Gender
# 📌 Insight:
  - Male and Female customers churn at almost the same rate which means gender does not strongly affect the churn.

    <img width="611" height="446" alt="image" src="https://github.com/user-attachments/assets/a7a319ba-90c2-4fa0-b276-83a914260709" />

# 💰 Monthly Charges vs Churn
# 📌 Insight:
  - Customers with higher monthly bills are more likely to churn.
  - Price sensitivity is a key factor.

    <img width="619" height="463" alt="image" src="https://github.com/user-attachments/assets/8deb5960-210b-461d-92be-02326f8ba3bd" />

# 📃 Churn by Contract Type
# 📌 Insight:
  - Customers who choose Month-to-month contracts have the highest churn rate.
  - The customer who go for 1-year or 2-year contracts are more loyal.

    <img width="616" height="453" alt="image" src="https://github.com/user-attachments/assets/0d00413f-85ce-44c2-ab7b-36bb9599b407" />

# 🔥 Correlation Heatmap
# 📌 Insight:
  - Strong positive correlation between Tenure and TotalCharges longer stay = higher total payment.
  - MonthlyCharges moderately correlated with TotalCharges.

    <img width="651" height="540" alt="image" src="https://github.com/user-attachments/assets/e61810d4-11ee-4001-a241-fa0f801d87fb" />


# ⚠️ Business Problems Identified
| Problem                            | Insight                                                       |
| ---------------------------------- | ------------------------------------------------------------- |
| **High Month-to-Month Churn**      | Flexible contracts see more churn compared to long-term deals |
| **Price Sensitivity**              | Higher monthly charges lead to higher churn rates             |
| **Short Tenure Customers Leaving** | Many customers quit within the first year                     |
| **Gender Not a Factor**            | Gender doesn’t significantly affect churn                     |



# ✅ Recommendations
  - Promote long-term contracts with discounts to lock in customers.
  - Offer loyalty rewards or lower pricing tiers to reduce high-bill churn.
  - Improve onboarding & first-year experience to retain short-tenure customers.
  - Focus retention strategies on contract and pricing, not gender.

# 📌 Project Status

  - ✅ Completed – Beginner-friendly EDA with insights.
  - 🔜 Future Work – Could add Machine Learning models for churn prediction.

# 📧 Contact

For any feedback or collaboration opportunities:
Author: Akansha Pawar
Email: pawaraakanksha210@gmail.com

⭐ If you found this project insightful, consider starring this repository!



 
 
 
