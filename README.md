# 06_study_methods_202401100300046
# Student Learning Style Classification

This project classifies students based on their preferred learning styles using data from a questionnaire. The learning styles include **Visual**, **Auditory**, and **Kinesthetic**.

---

## 📁 Files

- `student_methods.csv`: Input dataset containing students' learning style scores.
- `confusion_matrix_heatmap.png`: Heatmap visualization of the confusion matrix.
- `Student Classification Report`: Detailed report of methodology, code, and results.

---

## 🚀 How to Run the Project

1. **Install Dependencies**
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
   ```

2. **Run the Script**
   Ensure your working directory contains `student_methods.csv`, then execute:
   ```bash
   python student_classification.py
   ```

3. **View Results**
   - Classification metrics are printed in the terminal.
   - `confusion_matrix_heatmap.png` will be saved in the same directory.

---

## 📊 Dataset Description

- `visual_score`: Score indicating visual learning preference
- `auditory_score`: Score indicating auditory learning preference
- `kinesthetic_score`: Score indicating kinesthetic learning preference
- `learning_style`: Actual label of preferred learning style

---

## 📈 Output Metrics

- **Accuracy:** 0.50
- **Precision:** 0.46
- **Recall:** 0.50
- **F1 Score:** 0.47

---

## 📚 References

- Dataset: Provided by course instructor
- Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib

---

## 👤 Author

- **Name:** Anish Chaudhary  
- **Course:** B.Tech CSE (AI), Section A

