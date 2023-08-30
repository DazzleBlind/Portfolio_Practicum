# [Классификация комментариев](https://nbviewer.jupyter.org/github/agnesepoikane/Practicum-by-Yandex-Data-Scientist/blob/main/08_ML_for_texts/08_project.ipynb)

## Описание проекта

Цель проекта: создать прототип модели для интернет-магазина, который будет искать токсичные комментарии и отправлять их на модерацию.

Для этого необходимо:

- oбучить модель классифицировать комментарии на позитивные и негативные, используя набор данных с разметкой о токсичности правок.
- постройть модель со значением метрики качества `F1` не меньше `0.75`.


## Описание данных

- text — текст комментария
- toxic — целевой признак

## Структура проекта

1. Подготовка
	- Импорт библиотек
	- Чтение файла и изучение данных
2. Fasttext
	- Подготовка данных
	- Работа с моделью
3. BERT
   - Подготовка данных
   - Создание классов (хэлперов и модели)
   - Работа с моделью
4. Вывод по моделям
5. Вывод по проекту

## Используемые библиотеки и модули
`gensim` `fasttext` `BERT` `PyTorch` `matplotlib` `nltk` `numpy` `pandas` `plotly` `sklearn`

## Контакты

<div id="badges" >
  <a href="https://t.me/Dazzle_dazzle_dazzle">
    <img src="https://img.shields.io/badge/Telegram-deepskyblue?style=for-the-badge&logo=telegram&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/konstantin-sinkevich-39b982265/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
