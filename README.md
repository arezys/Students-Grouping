# 📊 K-Means Clustering for Forming Heterogeneous Learning Groups

This project aims to apply the K-Means Clustering algorithm to form heterogeneous student learning groups based on characteristics such as personality (BFI), self-efficacy (GSE), and academic motivation (MSLQ).
This approach is expected to improve learning outcomes through the **Collaborative Learning model**.

---

## ✨ Features
- Preprocess student data from questionnaire results.
- Use the **K-Means Clustering** algorithm to help create heterogeneous groups.
- Visualize clustering results in graphs.
- Save clustering outputs to **Excel** or **CSV**.

---

## 📂 Project Structure
- ├── data/
- │ ├── students.xlsx # Raw student data (questionnaire + scores)
- │ └── clustered_results.csv # Clustering output
- ├── src/
- │ ├── main.py # Main script to run clustering
- │ ├── preprocessing.py # Data preprocessing script
- │ └── utils.py # Utility functions
- ├── results/
- │ ├── cluster_plot.png # Visualization of clustering results
- │ └── report.xlsx # Final report of group formation
- ├── requirements.txt # List of dependencies
- └── README.md # Documentation
