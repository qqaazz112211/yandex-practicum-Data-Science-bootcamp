# Определение стоимости автомобилей

[Блокнот](https://github.com/qqaazz112211/yandex-practicum-Data-Science-bootcamp/blob/main/numerical_methods/numerical_methods.ipynb)

## Описание проекта

Построение модели для определения стоимости автомобиля.

## Библиотеки и инструменты

import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import seaborn as sns  
import plotly.express as px  
from sklearn.preprocessing import OrdinalEncoder  
from sklearn.model_selection import train_test_split  
from sklearn.model_selection import cross_val_score  
from sklearn.linear_model import LinearRegression  
from sklearn.metrics import mean_squared_error  
from sklearn.metrics import r2_score  
from sklearn.preprocessing import StandardScaler  
from sklearn.tree import DecisionTreeRegressor  
from catboost import CatBoostRegressor  
from sklearn.linear_model import Lasso  
from lightgbm import LGBMRegressor  
from pandas_profiling import ProfileReport  
import plotly.express as px  
from category_encoders.binary import BinaryEncoder
from sklearn.model_selection import GridSearchCV  
from sklearn.metrics import mean_squared_error  

## Вывод

Модель построена и выполняет поставленные задачи
