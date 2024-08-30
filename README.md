# Gradient Boosting from Scratch with NumPy

This project implements a Gradient Boosting algorithm from scratch using only NumPy. The primary objective is to provide a detailed, step-by-step guide on how gradient boosting works under the hood, without relying on external machine learning libraries for the core algorithm. This implementation serves educational purposes, offering insights into the mechanics of gradient boosting.

## Project Structure

The implementation is presented in a Jupyter notebook, which is organized into the following sections:

1. **Data Preparation**:
   - The project uses the Boston housing dataset, loaded and preprocessed using pandas and NumPy.
   - The dataset is split into training and testing sets.

2. **Decision Tree Regressor**:
   - A simple decision tree regressor is implemented as the base learner.
   - Initial implementations start with a stub and evolve to predict using mean values as a baseline.

3. **Evaluation Metrics**:
   - Mean Squared Error (MSE) is used to evaluate the performance of the predictions.

4. **Gradient Boosting Algorithm**:
   - The notebook details the construction of the gradient boosting algorithm, building upon the decision tree regressor.
   - The algorithm iteratively fits new trees to the residuals of the previous trees, reducing errors incrementally.

5. **Visualization**:
   - A custom plotting function is used to visualize the predicted values versus the actual values, allowing for a clear assessment of model performance.

## How to Use

### Prerequisites

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (for data handling purposes, not for gradient boosting)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/gradient-boosting-numpy.git
   cd gradient-boosting-numpy
   ```

2. Install the required Python packages:

   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Gradient Boosting.ipynb` and run the cells sequentially to follow along with the implementation.

## Key Features

- **Step-by-Step Implementation**: Each component of gradient boosting is implemented incrementally, making it easy to follow and understand.
- **No External ML Libraries**: The core algorithm relies solely on NumPy, providing a clear view of the inner workings of gradient boosting.
- **Visualizations**: The notebook includes functions for plotting predictions against actual values to visually assess model performance.

## Learning Outcomes

By following this project, you will gain:

- A deep understanding of how gradient boosting works.
- Experience implementing machine learning algorithms from scratch using NumPy.
- Insights into model evaluation and iterative improvement of predictive models.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to submit a pull request.
