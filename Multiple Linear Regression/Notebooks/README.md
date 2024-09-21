
## Notebooks

### 1. Exploratory Data Analysis (`EDA.ipynb`)

This notebook covers the exploratory data analysis (EDA) of the e-commerce customer dataset. Key activities include:
- Loading and inspecting the dataset.
- Visualizing relationships between different features and the target variable (Yearly Amount Spent).
- Checking for correlations and summarizing the dataset.
- Identifying the strongest predictor variables.

#### Key Visualizations:
- Pair plots for various features vs. `Yearly Amount Spent`.
- Correlation heatmaps and scatter plots to observe relationships between predictors.

#### Summary:
- **Length of Membership** has the strongest correlation with yearly spending.

### 2. Model Training (`model_training.ipynb`)

In this notebook, a linear regression model is built to predict customer yearly spending based on the selected features. The steps include:
- Preparing the dataset by splitting it into training and testing sets.
- Training the linear regression model.
- Evaluating the model's performance by comparing predicted values with actual values.

#### Key Steps:
- Train-test split (70% training, 30% testing).
- Fitting a linear regression model on `Avg. Session Length`, `Time on App`, `Time on Website`, and `Length of Membership`.
- Visualizing predicted vs. actual values.

#### Model Evaluation:
- Scatter plots and joint plots to compare predicted and actual values.
- Residual analysis to check the model’s fit.

## How to Run the Project

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- The following Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

### Steps to Run

1. Clone the repository and navigate to the `E-Commerce` directory:
   ```bash
   git clone https://github.com/Alpha-Mintamir/Linear-Regression
   cd Notebooks/E-Commerce
