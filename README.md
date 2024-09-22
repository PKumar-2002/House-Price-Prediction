# House Price Prediction

## Project Overview
This project focuses on predicting house prices using various machine learning techniques. The goal is to provide accurate predictions based on different features such as the number of bedrooms, location, size, and more.

## Features
- **Data Preprocessing**: Handling missing data, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Visualization of key trends and patterns in the dataset.
- **Model Training**: Various machine learning models implemented, including:
  - Linear Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- **Evaluation**: Comparing model performance using metrics such as RMSE (Root Mean Square Error), R2 Score, etc.
  
## Dependencies
Make sure to have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Dataset
The dataset used in this project contains various features like the size of the house, the number of bedrooms, bathrooms, etc., and the target variable is the price of the house.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house_price_prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house_price_prediction
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook House_price_Prediction.ipynb
   ```
4. Run the cells in the notebook to train the models and evaluate their performance.

## Results
The best-performing model in this project was the **Random Forest Regressor** with an R2 score of 0.85 and an RMSE of 24,500.

## Future Work
- **Model Optimization**: Fine-tuning hyperparameters using GridSearchCV or RandomizedSearchCV.
- **Incorporating More Features**: Using external data such as neighborhood crime rates, school ratings, etc.
- **Deploying the Model**: Using Flask or Django to create a web interface for users to input data and get price predictions.

## Contributors
- [Padmanavan Kumar](https://github.com/PKumar-2002)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
