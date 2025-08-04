# 📌 Task 03 – Decision Tree Classifier (SkillCraft Internship)

This repository presents the implementation of a **Decision Tree classifier** on the [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from the UCI Machine Learning Repository. The task is part of the SkillCraft Data Science Internship.

## 🧠 Objective

Predict whether a customer will subscribe to a term deposit based on demographic and behavioral attributes using a Decision Tree.

## 📁 Dataset

- **Source:** UCI Machine Learning Repository  
- **Rows:** 45,211  
- **Features:** 17 (including categorical and numeric attributes)

## 🔧 Tools Used

- Python  
- Pandas, NumPy  
- scikit-learn  
- Seaborn, Matplotlib  
- imbalanced-learn (SMOTE)

## 🧪 Process

1. **Data Preprocessing**
   - Label encoding of categorical variables
   - Splitting into train/test sets

2. **Model Training**
   - Base Decision Tree
   - Pruned Decision Tree (`max_depth=5`)
   - Decision Tree with SMOTE resampling

3. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - Confusion matrix
   - Feature importance plot
   - Correlation matrix

## 📊 Results

| Model Type         | Accuracy |
|--------------------|----------|
| Base Model         | 87.4%    |
| Pruned Tree        | 89.3%    |
| With SMOTE         | 84.7%    |

## 📈 Visualizations

- Feature Importance Bar Chart  
- Correlation Heatmap  
- Target Class Distribution  

## 📌 Conclusion

The pruned decision tree model provided the best generalization performance. SMOTE helped improve recall for the minority class.

---

### ✅ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/task3-decision-tree

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
