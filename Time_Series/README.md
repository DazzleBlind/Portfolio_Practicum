# [Модель для определения рыночной стоимости автомобиля](https://nbviewer.jupyter.org/github/agnesepoikane/Practicum-by-Yandex-Data-Scientist/blob/main/06_numerical_methods/06_project.ipynb)


## Описание проекта

Нужно построить модель, которая спрогнозирует количество заказов такси на следующий час.

Требование: значение метрики *RMSE* на тестовой выборке должно быть не больше 48.

## Описание данных

**Признаки:**

  - Время 

**Целевой признак:**

	- num_orders (количество заказов)

## Структура проекта

1. Подготовка данных
	- Импорт библиотек
	- Чтение файла и изучение данных
	- Resample по 1 часу
	- Формирование данных для обучения
  - Анализ данных  
2. Обучение моделей
	- LightGBM
	- DecisionTreeRegressor
	- CatBoost
3. Тестирование моделей
4. Анализ моделей
5. Вывод по проекту
    
## Используемые библиотеки и модули
`catboost` `lightgbm` `plotly` `matplotlib` `numpy` `pandas` `seaborn` `sklearn` 

## Контакты

<div id="badges" >
  <a href="https://t.me/Dazzle_dazzle_dazzle">
    <img src="https://img.shields.io/badge/Telegram-deepskyblue?style=for-the-badge&logo=telegram&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/konstantin-sinkevich-39b982265/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
