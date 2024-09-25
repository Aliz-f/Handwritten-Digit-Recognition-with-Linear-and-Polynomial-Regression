# Handwritten Digit Recognition with Linear and Polynomial Regression

This project revisits the handwritten digit recognition problem, focusing on separating digit 1 from all other digits using intensity and symmetry as input features. The study applies linear regression and a third-order polynomial transformation for binary classification.

## Experiment Overview
The tasks involve:
1. **Linear Regression Classification**: 
   - Use linear regression to compute weights (`w`) and approximate binary classification (`w^T x ≈ y = ±1`).
   - Compute `sign(w^T x)` and report the in-sample error (Ein) and out-of-sample error (Eout).
   
2. **Third-Order Polynomial Transform**:
   - Apply a third-order polynomial transformation (`Φ3`) to obtain a different representation of the data.
   - Repeat the classification process and compare the performance with the linear model.

3. **Comparative Analysis**:
   - Compare Ein and Eout values for both the linear model and the third-order polynomial model.
   - Visualize the classifier boundaries for both models, replicating the style from the "Nonlinear Transformation and Logistic Regression" chapter.

## Results
- Visualization of classifier boundaries for the linear and third-order polynomial models.
- Comparison of Ein and Eout for both models.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Required libraries: `numpy`, `matplotlib`, `scikit-learn`

## How to Run
1. Clone the repository: `git clone https://github.com/Aliz-f/Handwritten-Digit-Recognition-with-Linear-and-Polynomial-Regression`
2. Install the required libraries: `pip install numpy matplotlib scikit-learn`
3. Open the Jupyter Notebook

## License
This project is licensed under the MIT License.
