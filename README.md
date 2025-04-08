 **"PRCP-1026 Teaching Assistance"**:

---

# PRCP-1026 Teaching Assistance

## 📚 Project Overview

This project focuses on analyzing and classifying teaching performance evaluations for Teaching Assistants (TAs) at the Statistics Department of the University of Wisconsin-Madison. The dataset comprises evaluations from three regular semesters and two summer semesters, considering various factors that influence TA performance.

---

## 🧾 Problem Statement

To build a data-driven solution that helps assess and understand the impact of different variables on TA performance, potentially aiding in better resource planning and support systems.

---

## 🧠 Attribute Information

1. **Native English Speaker** (binary):  
   `1 = English speaker`, `2 = Non-English speaker`

2. **Course Instructor** (categorical):  
   25 unique instructor IDs

3. **Course** (categorical):  
   26 unique course IDs

4. **Semester** (binary):  
   `1 = Summer`, `2 = Regular`

5. **Class Size** (numerical):  
   Number of students in the class

6. **Class Attribute** (target - categorical):  
   `1 = Low`, `2 = Medium`, `3 = High`

---

## 🛠️ Project Workflow

1. **Importing Libraries**  
2. **Data Loading**  
3. **Duplicate Checks**  
4. **Basic Data Checks**  
5. **Exploratory Data Analysis (EDA)**  
6. **Data Preprocessing**  
   - Encoding categorical variables  
   - Handling missing values (if any)  
7. **Model Building**  
   - Tried various classification models  
   - Model performance comparison  
8. **Evaluation**  
   - Accuracy, Confusion Matrix, etc.

---

## 📊 Key Insights

- Dataset contains 110 rows and 6 columns after cleaning.
- The class attribute is fairly balanced across the three categories.
- Correlations and relationships among features reveal meaningful patterns.

---

## 📦 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and run cells sequentially.

---

## 📁 Dataset

The dataset is assumed to be included in the notebook or available upon request. It is originally from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Teaching+Assistant+Evaluation).

---

Would you like me to generate a `requirements.txt` for this as well?
