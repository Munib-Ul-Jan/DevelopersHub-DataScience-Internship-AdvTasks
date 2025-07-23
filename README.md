# DevelopersHub-DataScience-Internship-AdvTasks
This repository contains internship tasks assigned as the 2nd Task of Data Science internship at DevelopersHub

## Task 2: Customer Segmentation

**Objective:**
Cluster customers based on spending habits and propose targeted strategies for each segment.

**Dataset:**

* **Mall Customers Dataset** from Kaggle
* Features: CustomerID, Gender, Age, Annual Income (k\$), Spending Score (1–100)

**Approach:**

* Performed data cleaning and feature scaling.
* Conducted exploratory analysis using distributions, scatter plots, and correlation heatmaps.
* Used KMeans Clustering to segment customers.
* Determined optimal number of clusters using the Elbow Method and Silhouette Score.
* Visualized clusters using 2D and 3D scatter plots.

**Outcome:**
Customers were segmented into distinct groups based on their income and spending scores. These clusters help identify high-value and low-engagement customers, allowing personalized marketing strategies.

---

## Task 4: Loan Default Risk Prediction

**Objective:**
Predict the risk of loan default using customer demographic and financial features.

**Dataset:**

* `Loan_Default_Sample.csv`

**Approach:**

* Handled missing values and encoded categorical variables.
* Explored data using count plots and histograms.
* Trained two models: Logistic Regression and Random Forest Classifier.
* Evaluated models using accuracy, precision, recall, and confusion matrix.

**Outcome:**
Random Forest achieved better performance, especially in identifying defaulters. Important features included credit amount, employment status, annuity amount, and marital status. The model helps in pre-screening high-risk applicants.

---

## Task 5: Business Dashboard

**Objective:**
Create an interactive dashboard to visualize loan data and identify risk trends across demographic groups.

**Dataset:**

* `Global_Superstore.csv` 

**Approach:**

* Used Plotly and Dash within a Jupyter Notebook.
* Dashboard components include:

  * Pie charts for loan status distribution.
  * Bar charts for loan approval by gender and marital status.
  * Count plots for employment-based risk groups.
  * Interactive widgets for dynamic filtering.

**Outcome:**
The dashboard provides stakeholders with a visual tool to analyze customer profiles and risk levels. It aids in monitoring loan approval trends and identifying high-risk customer segments based on selected filters.

---

## Technologies Used

Category      | Tools                             
Data Handling | Pandas, NumPy                     
Visualization | Matplotlib, Seaborn, Plotly       
Modeling      | Scikit-learn (LogReg, RF, KMeans) 
Dashboard     | Plotly Dash                       
Environment   | Jupyter Notebook                  
