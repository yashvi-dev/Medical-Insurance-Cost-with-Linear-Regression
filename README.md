# **Medical Insurance Cost Prediction using Linear Regression**

This project predicts individual medical insurance charges based on demographic and lifestyle factors using a **Linear Regression** model. It also explores how each feature contributes to the overall insurance cost, providing clear insights into real-world healthcare trends.

---

## **📌 Project Overview**

Health insurance premiums depend on several measurable factors such as age, BMI, smoking habits, and region.
Using this dataset, the goal is to:

* Analyze feature relationships
* Preprocess and encode data
* Build and train a linear regression model
* Evaluate model performance
* Interpret coefficients to understand feature impact

This project demonstrates end-to-end machine learning workflow, from data cleaning to model interpretation.

---

## **📂 Dataset Description**

The dataset contains the following features:

| Feature      | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| **age**      | Age of the primary beneficiary                                                    |
| **sex**      | Gender of the insurance holder (`male`, `female`)                                 |
| **bmi**      | Body Mass Index (kg/m²)                                                           |
| **children** | Number of dependents covered                                                      |
| **smoker**   | Smoking status (`yes`, `no`)                                                      |
| **region**   | Residential region in the US (`northeast`, `southeast`, `southwest`, `northwest`) |
| **charges**  | Actual medical insurance cost (**target variable**)                               |

---

## **🎯 Objectives**

* Understand how each feature influences medical charges
* Apply encoding techniques for categorical variables
* Use normalization/standardization for numerical features
* Train a linear regression model
* Evaluate using **MAE**, **MSE**, **RMSE**, **R² Score**
* Interpret model coefficients for real-life insights

---

## **🛠️ Technologies Used**

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## **📊 Exploratory Data Analysis**

The project includes:

* Distribution plots for numerical features
* Boxplots to detect outliers
* Heatmap for correlation analysis
* Pairplots to visualize relationships

Key observations:

* **Smokers have significantly higher charges**
* **BMI** and **age** show strong positive influence
* Regional differences exist but are smaller in impact

---

## **⚙️ Model Development**

### **1. Data Preprocessing**

* Handling categorical variables using **OneHotEncoding**
* Normalizing numerical features using **MinMaxScaler**
* Splitting dataset into **train** and **test** sets

### **2. Model Training**

A **Linear Regression** model from scikit-learn is trained on the processed data.

### **3. Model Evaluation**

Metrics used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## **📈 Results & Interpretation**

* The model captures clear relationships between features and charges
* **Smoking** is the strongest predictor, contributing the highest positive coefficient
* **Age** and **BMI** significantly increase predicted charges
* Children and region have moderate influence

---

## **▶️ How to Run the Project**

1. Clone the repository:

   ```
   git clone https://github.com/your-username/medical-insurance-lr.git
   ```
2. Navigate to the project:

   ```
   cd medical-insurance-lr
   ```
3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
4. Run the notebook or script to train the model.

---

## **📜 License**

This project is open-source and licensed under the MIT License.

