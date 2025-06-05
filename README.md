# K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Objective
To understand and implement KNN for a multiclass classification problem using the famous Iris dataset.

## 📊 Dataset
- **Name:** Iris.csv
- **Target:** `Species` (Setosa, Versicolor, Virginica)
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width

## 🛠 Tools & Libraries
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 📈 Methodology
1. Loaded and explored the dataset.
2. Normalized features using `StandardScaler`.
3. Performed train-test split.
4. Trained KNN classifier with different K values.
5. Evaluated using Accuracy, Confusion Matrix, and Classification Report.
6. Plotted Accuracy vs K to find the optimal number of neighbors.

## ✅ Results
- Best accuracy achieved with **K = X**.
- Final classification metrics and confusion matrix shown in the script.

## 📁 Files Included
- `KNN_Classifier_Iris.ipynb`: Main Jupyter notebook with explanations and output.
- `Iris.csv`: Original dataset.
- `knn_accuracy_plot.png`: Accuracy plot.

## 📌 How to Run
```bash
pip install pandas scikit-learn matplotlib seaborn
python KNN_Classifier_Iris.py
