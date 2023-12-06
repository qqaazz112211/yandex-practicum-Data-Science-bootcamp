# Проект для «Викишоп»

[Блокнот](https://github.com/qqaazz112211/yandex-practicum-Data-Science-bootcamp/blob/main/machine_learning_for_texts/machine_learning_for_texts.ipynb)

## Описание проекта

Обучить модель для классификации комментариев на позитивные и негативные.

## Библиотеки и инструменты

import pandas as pd  
import numpy as np  
from pymystem3 import Mystem  
import re  
from tqdm import tqdm  
import nltk  
nltk.download('stopwords')  
from nltk.corpus import stopwords as nltk_stopwords  
from sklearn.feature_extraction.text import TfidfVectorizer  
from sklearn.linear_model import LogisticRegression  
from sklearn.model_selection import GridSearchCV  
from sklearn.metrics import f1_score  
from sklearn.model_selection import train_test_split  
from catboost import CatBoostClassifier  
from lightgbm import LGBMClassifier  
from nltk.stem import WordNetLemmatizer   
nltk.download('wordnet')  
from sklearn.tree import DecisionTreeClassifier  
from nltk.corpus import wordnet  
nltk.download('averaged_perceptron_tagger')  

## Вывод

Модель построена и выполняет поставленные задачи
