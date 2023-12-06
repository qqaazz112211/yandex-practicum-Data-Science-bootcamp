# Промышленность

[Блокнот](https://github.com/qqaazz112211/yandex-practicum-Data-Science-bootcamp/blob/main/final_project_industry/final_project_industry.ipynb)

## Описание проекта

Необходимо построить модель, которая предскажет температуру стали.


## Библиотеки и инструменты

import pandas as pd  
import numpy as mp  
import os  
import matplotlib.pyplot as plt  
import seaborn as sns  
import plotly.express as px  
import seaborn as sns  
import matplotlib.pyplot as plt  
from sklearn.model_selection import train_test_split  
from sklearn.linear_model import LinearRegression  
from sklearn.model_selection import cross_val_score  
from catboost import CatBoostRegressor  
from sklearn.preprocessing import StandardScaler  
import numpy as np  
from sklearn.model_selection import GridSearchCV  
import xgboost  
from sklearn.preprocessing import MinMaxScaler  
from sklearn.metrics import mean_absolute_error  



## Вывод

- В первой части работы был проведен анализ предоставленных данных. Определены аномалии. Построены графики для наглядного представляния. Сделаны промежуточные выводы
- Во второй части проекта проведена подготовка данных для дальнейшего построения модели. Устанены выявленные аномолии на предыдущем этапе, проведено агрегированние данных, подобраны лучшие параменты для модели, определен целевой признак
- Построены 3 модели: LinearRegression, CatBoostRegressor, XGBRegressor. Лучшее значение на тренировочной выборке показала модель CatBoostRegressor
- На базе лучших параметров модели CatBoostRegressor проведено предcказание значений на тестовой выборке
- Получились следующие значения метрики MAE на тестовой выборке - 6.1636481954094045
