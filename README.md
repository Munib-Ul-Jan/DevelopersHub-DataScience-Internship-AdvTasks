# DevelopersHub-DataScience-Internship-AdvTasks
This repository contains internship tasks assigned as the 2nd Task of Data Science internship at DevelopersHub

## Tasks Summary

### Task 2: Customer Segmentation

**-> Objective:**
Segment customers into distinct groups based on demographic and financial features to identify target audiences for credit risk.

**-> Approach:**

* Dataset: `TrainData_1.csv` (also used in Task 4).
* Data Preprocessing:

  * Handled missing values.
  * Label encoding for categorical variables.
  * Normalization for numerical features.
* Exploratory Data Analysis (EDA):

  * Box plots and count plots to examine feature distributions and outliers.
* Applied **KMeans Clustering**:

  * Chose optimal `k` using the Elbow Method.
  * Clustered customers based on features like income, credit amount, and employment status.

**-> Results & Insights:**

* Clear segmentation of customers into low-risk and high-risk financial behavior clusters.
* Employment status and marital status were significant in cluster formation.
* Visualization revealed distinct cluster groups, aiding in personalized financial product offerings.

---

### Task 4: Loan Default Risk Prediction

**-> Objective:**
Predict the probability of a customer defaulting on a loan based on historical application data.

**-> Approach:**

* Dataset: `TrainData_1.csv` and `TestData_1.csv`.
* Data Preprocessing:

  * Imputed missing values.
  * Converted categorical variables using label encoding.
* Models Applied:

  * **Logistic Regression**
  * **Random Forest Classifier**
* Evaluation:

  * Accuracy, Confusion Matrix, Precision, Recall, F1-Score.

**-> Results & Insights:**

* Random Forest performed better than Logistic Regression with improved recall and F1-score.
* Significant predictors:

  * **Credit Amount** (relative to income),
  * **Age**,
  * **Employment Status**,
  * **Annuity** and **Marital Status**.
* Unemployed or single individuals were at higher risk of default.

---

### Task 5: Business Dashboard (Interactive Visualization)

**-> Objective:**
Build an interactive business intelligence dashboard for stakeholders to analyze customer, loan, and risk data effectively.

**-> Approach:**

* Tool Used: `Plotly` + `Dash` (or visual libraries inside Jupyter Notebook).
* Dataset: Aggregated loan and customer demographic data.
* Dashboard Components:

  * Interactive bar charts for default rates by employment/marital status.
  * Pie charts showing distribution of approved vs rejected loans.
  * Time series or grouped bar plots for income vs credit amount vs risk.
  * Filters for user to select by region, gender, or other demographic features.

**-> Results & Insights:**

* Decision-makers can visually analyze high-risk customer segments.
* Dynamic filters enabled focused insight into specific customer demographics.
* Supports data-driven strategy in loan approval and risk assessment.

---

### Tools & Libraries Used:

* **Python**: Pandas, NumPy, Scikit-learn
* **Visualization**: Seaborn, Matplotlib, Plotly
* **Modeling**: Logistic Regression, Decision Tree, Random Forest, KMeans
* **Dashboards**: Plotly Dash / Interactive Notebook Visuals
* **Environment**: Jupyter Notebook

---

Let me know if you'd like this exported as a `.md` file or tailored to a specific audience (e.g., HR, business analysts, technical reviewers).
