📌 Objective

Implement and understand the KNN algorithm for classification problems, explore different values of K, evaluate model performance, and visualize decision boundaries.

🛠 Tools & Libraries

Python

Pandas — Data handling

NumPy — Numerical operations

Matplotlib & Seaborn — Visualization

Scikit-learn — KNN model, evaluation metrics, preprocessing

📂 Dataset

Iris Dataset (from sklearn.datasets)

Features: sepal length, sepal width, petal length, petal width

Target: Species (setosa, versicolor, virginica)

🚀 Steps Implemented

1. Load Dataset — Iris dataset from sklearn

2. Feature Normalization — StandardScaler to scale features

3. Train-Test Split — 80% training, 20% testing

4. Experiment with K — Checked accuracy for K = 1 to K = 15

5. Train Final Model — Used best K from experiments

6. Evaluate Model — Accuracy, confusion matrix, classification report

7. Visualize Decision Boundaries — Plotted boundaries for first two features

📊 Results

* Best K: Found from accuracy vs K plot

* Accuracy: ~96% (may vary slightly depending on split)

Observations:

* Too small K → High variance (overfitting)

* Too large K → High bias (underfitting)

* Normalization is critical for KNN performance

📷 Visuals

Accuracy vs K plot

Confusion matrix heatmap

Decision boundary plot for first two features
