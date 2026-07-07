# KNN-Classification-Using-the-Iris-Dataset
This project implements the K-Nearest Neighbors (KNN) classification algorithm using the Iris dataset. The data was normalized, and different K values were tested to find the best performance. The model was evaluated using accuracy and a confusion matrix, and decision boundaries were visualized to understand the classification process.
# K-Nearest Neighbors (KNN) Classification

## Objective

To understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems and evaluate its performance using the Iris dataset.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Dataset Description

The Iris dataset contains 150 samples of iris flowers belonging to three different species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

Features used:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target variable:

* Species

## Steps Performed

### 1. Data Loading

The Iris dataset was loaded using Pandas and unnecessary columns were removed.

### 2. Data Preprocessing

* Features and target variables were separated.
* The dataset was divided into training and testing sets.
* Feature scaling was performed using StandardScaler to normalize the data.

### 3. Model Training

The KNeighborsClassifier from Scikit-learn was used to train the KNN model.

### 4. Hyperparameter Tuning

Different values of K (1 to 20) were tested, and the corresponding accuracy scores were calculated to identify the optimal K value.

### 5. Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 6. Visualization

* Accuracy vs K graph was plotted to analyze the effect of different K values.
* Decision boundaries were visualized using two selected features to understand how KNN classifies data points.

## Results

The KNN classifier successfully classified the Iris flower species with high accuracy. The best K value was selected based on the highest accuracy obtained during experimentation.

## Conclusion

K-Nearest Neighbors is a simple and effective classification algorithm. The performance of the model depends on the choice of K and proper feature scaling. The Iris dataset was classified successfully with high accuracy, demonstrating the effectiveness of the KNN algorithm for classification tasks.
