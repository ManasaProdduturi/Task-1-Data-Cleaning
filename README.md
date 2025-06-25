# Task-1-Data-Cleaning
Titanic Dataset - Data cleaning, handling nulls, encoding, feature scaling.
This project focuses on cleaning and preprocessing the Titanic dataset to prepare it for machine learning and analysis.

---

# Objective

Clean raw data by:
- Handling missing values
- Dropping unusable features
- Preparing the data for encoding and scaling

---

# Tools Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib / Seaborn (for visuals)
- Jupyter Notebook

---

# Files in This Repository

| File Name                    | Description                                  |
|-----------------------------|----------------------------------------------|
| `Titanic-Dataset.csv`       | Original raw Titanic dataset                 |
| `titanic_cleaned.csv`       | Dataset after cleaning                       |
| `titanic-dataset.ipynb`     | Notebook with full cleaning code and output  |
| `before-cleaning-dataset.png` | Null values in raw dataset (screenshot)     |
| `after-cleaning-dataset.png`  | Null values removed (screenshot)            |
| `README.md`                 | This documentation file                      |

---

# Cleaning Steps Performed

- Loaded dataset and explored null values
- Replaced missing `Age` with median
- Replaced missing `Embarked` with mode
- Dropped `Cabin` due to excessive missing values
- Verified that all missing values were handled

---

# Before vs After

# Before Cleaning
![before-cleaning-dataset](https://github.com/user-attachments/assets/5fbb270e-1f99-4337-97d3-1f5cd4fcb06c)


# After Cleaning
![after-cleaning-dataset](https://github.com/user-attachments/assets/8ead78cf-9df0-4f76-b3e4-5dda4c64b714)

---

# What I Learned

- Importance of handling missing data before ML
- How to clean categorical and numerical features
- Using `.fillna()` effectively for imputation
- The role of visual validation via `.isnull().sum()`

---

#![Uploading after-cleaning-dataset.png…]()
 Next Steps (Not Included Here)

- Encode categorical features (`Sex`, `Embarked`)
- Normalize numeric features (`Age`, `Fare`)
- Outlier detection with boxplots
- Train ML models (Logistic Regression, Random Forest, etc.)

---

Feel free to fork this project or suggest improvements.
