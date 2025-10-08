# 📊 K-Means Clustering for Forming Heterogeneous Learning Groups

This project aims to apply the K-Means Clustering algorithm to form heterogeneous student learning groups based on characteristics such as personality (BFI), self-efficacy (GSE), and academic motivation (MSLQ). This approach is expected to improve learning outcomes through the **Collaborative Learning model**.

---

## ✨ Features
- Preprocess student data from questionnaire results.
- Use the **K-Means Clustering** algorithm to help create heterogeneous groups.
- Visualize clustering results in graphs.
- Save clustering outputs to **Excel** and **CSV**.

---

## 📂 Project Structure
- ├── data/
- │ ├── Class A.csv # Class A data (questionnaire + scores)
- │ ├── Class B.csv # Class B data (questionnaire + scores)
- │ ├── clustered_student_class A # Clustered A data
- │ └── clustered_student_class B # Clustered B data
- ├── src/
- │ ├── Student_Grouping_Class_A.ipynb # Main script of Class A
- │ └── Student_Grouping_Class_B.ipynb # Main script of Class B
- ├── results/
- │ ├── Analysis of Cluster A.png
- │ ├── Analysis of Cluster B.png
- │ ├── Class & Cluster Analysis.xlxs # Analysis of clustering results
- │ ├── Cluster of Class A.png # Visualization of Class A results
- │ ├── Cluster of Class B.png # Visualization of Class B results
- │ ├── Silhouette Eval - Class A.png
- │ └── Silhouette Eval - Class B.png
- ├── requirements.txt # List of dependencies
- └── README.md # Documentation
