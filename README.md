# Rain Prediction on Australian Weather Dataset
This project aims to predict rain in Australia using a machine learning model trained on a dataset containing historical weather data. The dataset provides various atmospheric features such as temperature, humidity, wind speed, and rainfall observations, among others. The model analyzes these features and determines whether it will rain on a given day.

## Dataset
The Australian Weather Dataset used in this project is a collection of historical weather observations from numerous weather stations across Australia. The dataset consists of the following attributes:

Date: The date of the weather observation.
Location: The location of the weather station.
MinTemp: The minimum temperature recorded on that day.
MaxTemp: The maximum temperature recorded on that day.
Rainfall: The amount of rainfall recorded on that day.
WindGustDir: The direction of the strongest gust of wind.
WindGustSpeed: The speed (in km/h) of the strongest gust of wind.
WindDir9am: The direction of the wind at 9 am.
WindDir3pm: The direction of the wind at 3 pm.
WindSpeed9am: The speed (in km/h) of the wind at 9 am.
WindSpeed3pm: The speed (in km/h) of the wind at 3 pm.
Humidity9am: The humidity (in percentage) at 9 am.
Humidity3pm: The humidity (in percentage) at 3 pm.
Pressure9am: The atmospheric pressure (in hpa) at 9 am.
Pressure3pm: The atmospheric pressure (in hpa) at 3 pm.
Cloud9am: The fraction of sky obscured by cloud at 9 am.
Cloud3pm: The fraction of sky obscured by cloud at 3 pm.
Temp9am: The temperature (in degrees Celsius) at 9 am.
Temp3pm: The temperature (in degrees Celsius) at 3 pm.
RainToday: Whether there was rainfall on that day (Yes or No).
The dataset is available in CSV format and is provided separately. It is recommended to download and place the dataset file (weather_dataset.csv) in the project directory before running the code.

## Dependencies
This project requires the following dependencies:

Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook (optional, for running the provided example notebook)
You can install the required packages using pip, with the following command:

## Copy code
pip install pandas numpy scikit-learn matplotlib jupyter
Usage
## To use this project, follow these steps:

Clone the repository to your local machine or download and extract the ZIP file.
Place the weather_dataset.csv file in the project directory.
Open the project in a Python development environment or Jupyter Notebook.
Run the rain_prediction.py script or open and run the provided example Jupyter Notebook.
The script or notebook will load the dataset, preprocess the data, train a machine learning model, and evaluate its performance. It will then prompt you to enter the input features for a specific date and location to predict whether it will rain on that day.

Feel free to modify the code or experiment with different machine learning algorithms to further enhance the rain prediction model.

License
This project is licensed under the MIT License. Please see the LICENSE file for more details.

Acknowledgments
The Australian Weather Dataset used in this project is sourced from Kaggle.
