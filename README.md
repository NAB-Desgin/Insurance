
# 🏥 Insurance Cost Analysis using Machine Learning

## 📌 Project Overview

This project focuses on analyzing an **insurance dataset** to understand the factors that influence **medical insurance charges**. Using data science techniques, the dataset is explored, cleaned, and visualized to uncover patterns related to **age, BMI, smoking habits, gender, and number of children**.

The goal of this project is to demonstrate the **data analysis workflow used in real-world machine learning and data science projects**.

---

## 🎯 Objectives

* Understand the structure of the insurance dataset
* Perform **data cleaning and preprocessing**
* Conduct **exploratory data analysis (EDA)**
* Visualize relationships between variables
* Identify factors affecting **insurance charges**

---

## 📂 Dataset Information

The dataset contains information about individuals and their medical insurance costs.

| Feature  | Description                        |
| -------- | ---------------------------------- |
| age      | Age of the individual              |
| sex      | Gender of the policy holder        |
| bmi      | Body Mass Index                    |
| children | Number of dependents covered       |
| smoker   | Whether the person is a smoker     |
| region   | Residential area of the individual |
| charges  | Medical insurance cost billed      |

---

## 🛠 Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

---

## 📊 Exploratory Data Analysis (EDA)

Several analyses were performed to understand the dataset:

### Data Inspection

* Checking dataset shape
* Viewing column information
* Statistical summary of features
* Identifying missing values

### Data Visualization

Different visualization techniques were used to identify trends and relationships:

* Count plots for gender distribution
* Distribution plots for numerical features
* Comparison of smokers vs non-smokers
* Relationship between **BMI and insurance charges**
* Relationship between **age and insurance charges**

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Creating a copy of the dataset
* Separating numeric and categorical columns
* Verifying column names
* Preparing data for visualization and analysis

---

## 📁 Project Structure

```
Insurance/
│
├── Insurance.ipynb      # Jupyter Notebook containing full analysis
├── insurance.csv        # Dataset used for analysis
└── README.md            # Project documentation
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/NAB-Desgin/Insurance.git
```

### 2️⃣ Navigate to the project folder

```
cd Insurance
```

### 3️⃣ Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

### 4️⃣ Open the notebook

Run the following command:

```
jupyter notebook
```

Then open:

```
Insurance.ipynb
```

---

## 📈 Key Insights

Some insights obtained from the analysis include:

* **Smoking significantly increases insurance charges**
* **Higher BMI often correlates with higher medical costs**
* **Age is a strong factor affecting insurance charges**
* Non-smokers generally have **lower insurance costs compared to smokers**

---

## 🚀 Future Improvements

Possible improvements for this project include:

* Building a **machine learning model to predict insurance charges**
* Performing **feature engineering**
* Deploying the model as a **web application**
* Adding **interactive dashboards**

---

## 👨‍💻 Author

**Nithin A B**

Computer Science & Engineering (Data Science) Student
Passionate about **Data Science, Machine Learning, and AI projects**

---

⭐ If you found this project helpful, feel free to **star the repository**.
