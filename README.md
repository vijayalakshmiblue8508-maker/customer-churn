 **Customer Churn Analysis System**


 **Project Introduction**


Customer churn is a major issue faced by businesses like banking, telecom, and e-commerce.
It occurs when customers stop using a company’s services.
High churn leads to loss of revenue and affects business growth.
Companies collect large amounts of customer data, but manual analysis is difficult.
Due to privacy concerns, real datasets are not always available.

 **This project solves the problem by:


**
Creating synthetic customer data using Faker
Performing data analysis to understand churn behavior


 **Project Objectives**


★ Create a realistic synthetic dataset
★ Simulate real-world customer scenarios
★ Clean and preprocess the data
★ Perform statistical analysis
★ Identify churn patterns and trends
★ Analyze relationships between variables
★ Visualize data using charts
★ Generate insights to reduce churn


 **Dataset Overview**


Total Records: 100,000 customers
Data generated using Faker library


 **Features in Dataset**


Customer_ID → Unique ID
Age → 18 to 70
Gender → Male / Female
Tenure → 0 to 10 years
Balance → 0 to 200,000
CreditScore → 300 to 900
EstimatedSalary → 10,000 to 150,000
NumOfProducts → 1 to 4
IsActiveMember → 0 (No), 1 (Yes)
Churn → 0 (No), 1 (Yes)


 **Technologies Used**


★ Python
★ Pandas
★ NumPy
★ Matplotlib
★ Seaborn (Heatmap)
★ Faker


** Project Workflow**


 1. **Data Generation**


Synthetic data created using Faker
Random values used to mimic real-world data
Includes realistic distributions


 2. **Data Cleaning & Preprocessing**


Removed missing/null values
Checked and corrected data types
Ensured dataset consistency


 3. **Exploratory Data Analysis (EDA)**


Calculated mean, median, standard deviation
Analyzed feature distributions
Detected outliers


 4. **Churn Analysis**


Compared churn vs non-churn customers
Identified high-risk customer groups
Studied impact of features on churn


 5. **Group Analysis**


Age group vs churn
Gender vs churn
Active vs inactive customers
Product usage vs churn


 6. **Relationship Analysis**


Balance vs churn
Credit score vs churn
Tenure vs churn


 7. **Data Visualization**


★ Bar charts
★ Pie charts
★ Histograms
★ Box plots
★ Scatter plots
★ Heatmap


 **Key Findings**


★ Low balance customers churn more
★ Low credit score increases churn risk
★ Inactive users are most likely to churn
★ Customers with more products stay longer
★ High engagement reduces churn
★ Long-term customers are more loyal


** How to Run the Project**


 Step 1: Install Libraries


pip install pandas numpy matplotlib seaborn faker


 Step 2: Run the Project


Google Colab
Jupyter Notebook
VS Code


 Project Structure


Customer-Churn-Analysis/
│
├── churn_analysis.py
├── customer_churn_data.csv
├── README.md
└── visualizations/


 Future Enhancements


★ Apply Machine Learning (Logistic Regression, Random Forest)
★ Build churn prediction model
★ Create dashboards (Power BI / Tableau)
★ Develop web app using Flask / Django



**output screenshots**


<img width="688" height="462" alt="image" src="https://github.com/user-attachments/assets/500c7825-cc5c-4009-898d-b1e72d2de862" />
<img width="695" height="485" alt="image" src="https://github.com/user-attachments/assets/ca120a20-bf63-408f-a808-f3a159b03460" />
<img width="672" height="469" alt="image" src="https://github.com/user-attachments/assets/f0108641-d053-411f-a0a9-022d5adaeb04" />
<img width="694" height="472" alt="image" src="https://github.com/user-attachments/assets/4c6a32dd-76e7-4ad9-81b8-45c63dcc1196" />
<img width="664" height="476" alt="image" src="https://github.com/user-attachments/assets/0aa077b1-373f-4656-b2df-0ae43d64c609" />
<img width="709" height="504" alt="image" src="https://github.com/user-attachments/assets/5352c3d7-3ace-4962-be4a-b3aafd2fb0a3" />
<img width="455" height="438" alt="image" src="https://github.com/user-attachments/assets/f070ae5f-0953-4f3b-b491-d6077eb72115" />
