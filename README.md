# 🍷 Wine Dataset - Dimension Reduction using PCA

## 📌 Project Overview
This project demonstrates dimensionality reduction on the classic Wine dataset using **Principal Component Analysis (PCA)**. The goal is to reduce the number of features while preserving the underlying patterns in the data, making it easier to visualize and analyze.

## 🧪 Dataset
- **Source:** UCI Machine Learning Repository
- **Attributes:** 13 chemical analysis features (e.g., Alcohol, Malic acid, Ash, etc.)
- **Target:** Customer Segment (Three types of wine classes)

## ⚙️ What This Notebook Does
1. Loads the Wine dataset from a CSV file
2. Performs basic data inspection
3. Standardizes the features
4. Applies PCA to reduce 13 features to 2 principal components
5. Visualizes the data in 2D space

## 🔍 Why PCA?
Principal Component Analysis transforms high-dimensional data into a lower-dimensional form by identifying directions (principal components) along which the variance is maximized. It's particularly useful for:

- Removing multicollinearity
- Improving visualization
- Speeding up training for ML models

## 📊 Output Visualization
The PCA plot above illustrates how well the three wine classes are separated in the reduced 2D space.

![a3d06b94-4e14-467f-a523-76a66ae4ac8f](https://github.com/user-attachments/assets/7524b78b-7a87-492b-9921-bdcce534bbe5)


## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
```
2. Navigate to the folder and install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook "Dimension Reduction.ipynb"
```

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 🙌 Acknowledgements
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine)

---

Feel free to fork the repo and experiment with other dimension reduction techniques like **LDA**, **t-SNE**, or **UMAP**!

