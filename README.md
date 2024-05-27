# Project Title

This project is a machine learning model for predicting customer churn. The model is trained on a dataset contained in `Churn_Modelling.csv` and the training process is documented in the Jupyter notebook `customer_churn_prediction.ipynb`. The final model is stored in `final_XGB_model.pkl` and can be run using the Streamlit app in `app.py`.

## Project Structure

The project has the following structure:

```
.
├── data/
│   ├── Churn_Modelling.csv
│   ├── customer_churn_prediction.ipynb
│   └── final_XGB_model.pkl
└── app.py
```

### `data/Churn_Modelling.csv`

This CSV file contains the data used for training the machine learning model. It includes various features related to customer behavior and whether or not the customer churned.

### `data/customer_churn_prediction.ipynb`

This Jupyter notebook contains the code used for training the machine learning model. It includes data exploration, preprocessing, model training, and evaluation steps.

### `data/final_XGB_model.pkl`

This is a pickle file that stores the final trained machine learning model. This model can be loaded and used to make predictions on new data.

### `app.py`

This is a Streamlit app that provides a user interface for running the machine learning model. It loads the model from `final_XGB_model.pkl` and allows the user to input new data for prediction.

## Getting Started

To get started with this project, clone the repository and install the required Python packages. You can then run the Streamlit app with the following command:

```bash
streamlit run app.py
```

This will start the app and you can access it in your web browser at `http://localhost:8501`.

## Requirements

This project requires Python 3.9 or later and the following Python packages:

- ```pandas==1.5.3```
- ```numpy==1.26.4```
- ```scikit-learn==1.4.2```
- ```xgboost==2.0.3```
- ```streamlit==1.35.0```

You can install these packages with pip:

```bash
pip install -r requirements.txt
```

## License

This project is licensed under the terms of the MIT license.