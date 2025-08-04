# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This repository contains my submission for **Task 1** of the AI & ML Internship Program — focused on data cleaning and preprocessing using the Titanic dataset.

---

## 📌 Task Objective

Clean and prepare a real-world dataset by:
- Handling missing data
- Encoding categorical variables
- Scaling numerical features
- Detecting and removing outliers

---

## 🗂️ Files in This Repo

| File Name           | Description                                  |
|---------------------|----------------------------------------------|
| `task1.ipynb`       | Google Colab notebook with full code         |
| `cleaned_titanic.csv` | (Optional) Final cleaned dataset after preprocessing |
| `README.md`         | Documentation (this file)                    |

---

## 📊 Dataset

- **Name**: Titanic Dataset
- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Used a version from: `https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv`

---

## 🔧 Steps Performed

### 1. Import & Explore
- Loaded dataset and checked for missing values, datatypes.

### 2. Handle Missing Values
- `Age`: filled with mean
- `Embarked`: filled with mode
- `Cabin`: dropped due to too many nulls

### 3. Encode Categorical Features
- `Sex`: label encoded (0 = female, 1 = male)
- `Embarked`: one-hot encoded (with `drop_first=True`)

### 4. Scale Numerical Features
- Standardized `Age` and `Fare` using `StandardScaler`

### 5. Detect & Remove Outliers
- Visualized `Fare` outliers using boxplot
- Removed extreme values using IQR method

---

## 💻 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn.preprocessing`

---

## 🚀 How to Run

1. Open the notebook `task1.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Mount Google Drive and load the dataset (or use the link-based CSV)
3. Run all cells sequentially

---

## 📤 Submission

Submitted via: [Internship Task 1 Google Form](https://forms.gle/8Gm83s53KbyXs3Ne9)

---


- **Name**: Kavvampally Akhila
- **GitHub**: https://github.com/settings/appearance
