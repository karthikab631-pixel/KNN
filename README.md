# K-Nearest Neighbors (KNN) Classification

## Objective
Implement the K-Nearest Neighbors (KNN) algorithm for a classification problem using Scikit-learn.

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
Iris Dataset (built into Scikit-learn)

## Steps Performed
1. Loaded the Iris dataset.
2. Selected the first two features.
3. Split the dataset into training and testing sets.
4. Normalized the features using StandardScaler.
5. Trained a KNeighborsClassifier.
6. Predicted test labels.
7. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
8. Tested different K values.
9. Visualized:
   - Accuracy vs K
   - Decision Boundary

## Result
The KNN classifier achieved approximately **83% accuracy** using K=5.

## Conclusion
KNN is a simple and effective classification algorithm. Feature scaling improves performance, and selecting the correct K value is important for achieving better accuracy.
