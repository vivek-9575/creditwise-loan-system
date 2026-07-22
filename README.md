# CreditWise Loan System 🏦💰

An end-to-end machine learning system designed to automate credit risk assessment and evaluate borrower creditworthiness. This project benchmarks multiple classification algorithms to predict loan eligibility and minimize default rates.

## 🚀 Key Pipeline Stages

* **Exploratory Data Analysis (EDA):** Visualizing feature distributions, analyzing correlations, and identifying key drivers of loan defaults.
* **Data Preprocessing:** Cleaning missing data, handling outliers, and ensuring data consistency.
* **Feature Engineering:** Scaling numerical fields and encoding categorical credit variables for optimal model consumption.
* **Model Training & Benchmarking:** Implementing and comparing classic classification workflows.

## 🛠️ Tech Stack & Algorithms

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Models Evaluated:**
  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Naive Bayes

## 📂 Project Structure

```text
├── data/                      # Local dataset folder (Excluded from GitHub via .gitignore)
├── .gitignore                 # Specifies intentionally untracked files to ignore
├── loan_approve.ipynb         # Main Jupyter Notebook containing EDA, preprocessing, and modeling
└── README.md                  # Project documentation
```

## ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd creditwise-loan-system
   ```

2. **Install dependencies:**
   Make sure you have the required libraries installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. **Launch the notebook:**
   ```bash
   jupyter notebook loan_approve.ipynb
   ```
