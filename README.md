# Accurate-Breast-Cancer-Prediction-using-Machine-Learning


### Dataset: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic "Breast Cancer Wisconsin (Diagnostic) Data Set")

#### Attribute Information
- ID number
- Diagnosis (M = malignant, B = benign)
- Ten real-valued features are computed for each cell nucleus:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

### Methodology
Several machine learning models were implemented and evaluated to find the most accurate predictor for breast cancer:

1. Logistic Regression: Achieved the highest accuracy, providing a clear boundary for classification between benign and malignant cases.
2. XGBoost: Delivered high accuracy and robustness, making it a strong candidate for this classification task.
3. Random Forest: Performed well by leveraging ensemble learning, though slightly less accurate than Logistic Regression and XGBoost.
4. Decision Tree: Although straightforward, this model yielded the lowest accuracy among the tested models.


### Results
The models achieved the following accuracies:

**Logistic Regression:** 98.25% 
**XGBoost:** 97.66% 
**Random Forest:** 96.49% 
**Decision Tree: **91.81%

Based on these results, Logistic Regression and XGBoost are recommended as the best models for accurately predicting breast cancer. Logistic Regression has a slight edge in accuracy, while XGBoost offers versatility and robustness, especially for larger datasets or when more complex interactions are involved.


