# Engine-Life-Prediction-Using-Machine-Learning
This project focuses on developing a machine learning model to predict the Remaining Useful Life (RUL) of jet engines using the NASA CMAPSS dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Joblib

## Instructions
1. Clone the repository.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook or the Python scripts to reproduce the analysis.
4. Load the saved models using `joblib.load('rf_model.pkl')` or `joblib.load('xgb_model.pkl')`.

## Results
- The Random Forest model achieved an MSE of 4829.61.
- The XGBoost model achieved an MSE of 5739.95.

## Future Work
- Hyperparameter tuning could be performed to further improve the models.
- Explore other machine learning algorithms like Support Vector Machines (SVM) or Neural Networks.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
