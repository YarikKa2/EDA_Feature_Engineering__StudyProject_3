# PROJECT-3. EDA + Feature Engineering
Очистка датасета для последующего использования в модели машинного обучени.  <br>
Цель проекта заключается в построении модели, напраленной на предсказание рейтинга отеля. 

## Содержание
- [Технологии](#технологии)
- [Использование](#Использование)
- [Данные](#Данные)
- [Команда проекта](#команда-проекта)

## Технологии
- [Visual Studio Code](https://code.visualstudio.com/)
- [Python 3.9.10](https://www.python.org/downloads/release/python-3910/)



## Использование
Для работы данной программы потребуется импортировать несколько библиотек: <br>
1. Для определения пути до директории <br>
* os (``` import os ```) <br>

2. Для манипуляций с regex <br>
* re (``` import re ```) <br>

3. Для манипуляций с датафреймами <br>
* pandas (``` import pandas as pd ```) <br>
* numpy (``` import numpy as np ```) <br>

4. Для отрисовки инфографики<br>
* seaborn (``` import seaborn as sns ```) <br>
* matplotlib (```from matplotlib import pyplot as plt```) <br>

5. Для статистических оценок и преобразования данных
stats (``` import scipy.stats as stats ```) <br>
RobustScaler (``` from sklearn.preprocessing import RobustScaler ```) <br>
StandardScaler (``` from sklearn.preprocessing import StandardScaler ```) <br>
PowerTransformer (``` from sklearn.preprocessing import PowerTransformer ```) <br>
RandomForestRegressor (``` from sklearn.ensemble import RandomForestRegressor ```) <br>
metrics (``` from sklearn import metrics ```) <br>
  
<br>
Если у вас отсутвует какой либо из вышеперечисленных пакетов, установите его. <br>
В терминале введите ``` pip install 'название_пакета_без_кавычек' ```<br>

## Данные
Данные для анализа доступны по [ссылке](https://drive.google.com/drive/folders/1TtP1K9v5yFMaDtFHeX7sIub3dWDzTxR5?usp=drive_link)  <br>
Для корректной работы кода создайте в корневой директории папку с названием **data_set**

## Команда проекта

[Капущак Ярослав](https://github.com/YarikKa2)

