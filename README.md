# Iris Flower Classification using K-Nearest Neighbors (KNN)

This project demonstrates the classification of Iris flower species using the **K-Nearest Neighbors (KNN)** algorithm. The Iris dataset, a well-known clean dataset, is used for training and evaluating the model.

## Project Steps:
1. **Dataset**:
   - Loaded the Iris dataset from `sklearn.datasets`.
   - Features include sepal and petal length/width.
   - Target classes: `Setosa`, `Versicolor`, `Virginica`.

2. **Data Analysis**:
   - Analyzed feature correlations using a heatmap.
   - Split the dataset into classes (0: Setosa, 1: Versicolor, 2: Virginica).

3. **Feature Selection**:
   - Used all features (`sepal length`, `sepal width`, `petal length`, `petal width`).

4. **Data Splitting**:
   - Split the data into training (80%) and testing (20%) sets.

5. **Model Training**:
   - Trained the KNN model with `n_neighbors=3` and achieved **100% accuracy**.
   - Tested with `n_neighbors=15`, achieving **96.67% accuracy**.

## Results:
- **KNN Accuracy (n_neighbors=3)**: 100%  
- **KNN Accuracy (n_neighbors=15)**: 96.67%  

## Key Insights:
- The Iris dataset is simple and well-separated, making it suitable for high-accuracy classification with KNN.
- Adjusting the number of neighbors impacts model performance.

Feel free to provide feedback or suggestions for improvement. You can reach me at Email: mfauzanfauzan123@gmail.com and: [Linkedin](https://www.linkedin.com/in/muhammadfauzandsml/)
