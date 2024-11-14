# Getting the ML models


1. Configure the Environment

To set up the project environment, run the following commands:
conda install pandas numpy scikit-learn matplotlib seaborn xgboost joblib

if you don't like conda you can use the following PIP command as well:
pip install pandas numpy scikit-learn matplotlib seaborn xgboost joblib

2. Data Processing
The data has been prepared in CSV format and should be preprocessed before training the model. The files used to clean the data are in DataCleaning Folder, but they will not run as the orignal data is not included in the folder, because of their size.
The cleaned data is stored in the Data folder

**Running the models**

- Install required libraries.
- Run weather models (weather_model).
- Run power model (powerconsumption_model).
- Run final_prediction

weather_models contain the Temperature, Humidity and WindSpeed models.
powerconsumption_model contains the power consumption model.
and final_prediction combines the predictions of both models to predict the power consumption.

The model folder should be empty in the beginning and after running the files model would be dumped there to be used by final_prediction later on.
