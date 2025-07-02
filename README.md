# Weather Prediction Model

This repository contains weather prediction datasets based on the European Climate Assessment & Dataset (ECA&D) from 18 European cities (2000-2010).

## Files

- `weather_prediction_dataset.csv`: Features like temperature, humidity, wind speed, cloud cover, etc.
- `weather_prediction_bbq_labels.csv`: Labels for prediction.

## Data Source

Data originally from [ECA&D](http://www.ecad.eu).

## How to use

Load the data in Python:

```python
import pandas as pd
data = pd.read_csv('weather_prediction_dataset.csv')
labels = pd.read_csv('weather_prediction_bbq_labels.csv')
