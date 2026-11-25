# Data Cleaning – Online Retail Dataset

## 📌 Project Overview

This project demonstrates a systematic data cleaning and preprocessing workflow using Python and Pandas. It focuses on identifying and resolving real-world data quality issues to ensure that the dataset is reliable, consistent, and suitable for downstream data analysis and machine learning.

## 🎯 Objectives

- Identify and handle missing values using justified column-specific strategies.
- Detect and remove duplicate records.
- Correct inconsistent data formatting.
- Detect outliers using the Interquartile Range (IQR) method.
- Handle invalid records based on domain knowledge.
- Encode categorical variables appropriately.
- Compare dataset quality before and after cleaning.

## 📊 Dataset

**Dataset Name:** UCI Online Retail Dataset

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

**Original Records:** 541,909

**Number of Attributes:** 8

The dataset contains real-world retail transactions from a UK-based online retail business.

| Attribute | Description |
|---|---|
| InvoiceNo | Transaction identification number |
| StockCode | Product identification code |
| Description | Product description |
| Quantity | Number of units purchased |
| InvoiceDate | Transaction date and time |
| UnitPrice | Price per unit |
| CustomerID | Customer identification number |
| Country | Customer's country |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook
- GitHub

## 🔄 Data Cleaning Workflow

### 1. Initial Data Quality Assessment

- Inspect dataset dimensions and data types.
- Identify missing values and duplicate records.
- Examine descriptive statistics.
- Identify inconsistent and invalid entries.

### 2. Duplicate Handling

Identify and remove duplicate records to reduce redundancy and prevent misleading analytical results.

### 3. Missing Value Treatment

Apply appropriate column-specific missing value handling strategies with documented justifications instead of using a blanket deletion approach.

### 4. Data Formatting

Standardize text fields and ensure consistent data types throughout the dataset.

### 5. Outlier Detection and Treatment

- Apply the Interquartile Range (IQR) method.
- Visualize numerical distributions using box plots.
- Distinguish genuine extreme transactions from invalid records.
- Retain meaningful outliers when justified.
- Exclude transactions outside the positive-value sales analysis scope.

### 6. Categorical Encoding

Apply one-hot encoding to suitable unordered categorical variables to prepare the dataset for downstream analysis.

### 7. Before-and-After Comparison

Evaluate the effectiveness of data cleaning using:

- Dataset dimensions
- Missing value counts
- Duplicate record counts
- Summary statistics
- Data distribution visualizations

## 📂 Repository Structure

- `Data_Cleaning_Online_Retail.ipynb` – Complete data cleaning notebook.
- `README.md` – Project documentation.
- Cleaned dataset CSV – Generated after executing the notebook.

## 🚀 How to Run the Project

1. Download the notebook from this repository.
2. Open Google Colab.
3. Upload `Data_Cleaning_Online_Retail.ipynb`.
4. Select Runtime → Run all.
5. Review the intermediate outputs and visualizations.
6. Export the cleaned dataset.

The notebook automatically loads the source dataset.

## ✅ Expected Outcomes

- Improved data quality and consistency.
- Reduced redundant and invalid records.
- Appropriate treatment of missing values.
- Documented and justified outlier handling.
- Encoded categorical features.
- A structured dataset suitable for further analysis.

## 📚 Learning Outcomes

Through this project, I developed practical skills in real-world data cleaning, exploratory data analysis, statistical outlier detection, categorical encoding, and data preprocessing. I also learned the importance of documenting cleaning decisions to ensure reproducibility and reliability.

## 📝 Conclusion

Data cleaning is a fundamental step in the data science lifecycle. This project demonstrates how systematic preprocessing and justified decision-making can transform raw retail transaction data into a more reliable dataset suitable for meaningful analysis.

## 🔗 References

- [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- [Pandas – Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html)
- [Scikit-learn – Data Preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)
