# Промышленность

[Блокнот](https://github.com/qqaazz112211/yandex-practicum-Data-Science-bootcamp/blob/main/forecasting_cab_orders/forecasting_cab_orders.ipynb)

## Описание проекта

Построить модель предсказания количества заказов такси на следующий час для привлечения больше водителей в период пиковой нагрузки.

## Библиотеки и инструменты

import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import seaborn as sns  
from statsmodels.tsa.seasonal import seasonal_decompose  
from statsmodels.tsa.stattools import adfuller  
from sklearn.model_selection import train_test_split  
from sklearn.ensemble import RandomForestRegressor  
from sklearn.model_selection import GridSearchCV  
from sklearn.metrics import mean_squared_error  
from catboost import CatBoostRegressor  
from lightgbm import LGBMRegressor  
from statsmodels.tsa.seasonal import seasonal_decompose  
from sklearn.preprocessing import StandardScaler  
from sklearn.model_selection import cross_val_score  
from sklearn.linear_model import LinearRegression  
from sklearn.tree import DecisionTreeRegressor  
import plotly.express as px  
from sklearn.model_selection import TimeSeriesSplit  
from tqdm import tqdm



## Вывод

Модель построена и выполняет поставленные задачи
