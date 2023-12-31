# [Предсказание коэффициента восстановления золота](https://github.com/DazzleBlind/Portfolio_Practicum/blob/main/Industry_ML/Industry_ML.ipynb)

## Описание проекта

Построить прототип модели машинного обучение для предсказания коэффициента восстановления золота из золотосодержащей руды. Прототип модели поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


## Описание данных

**Технологический процесс**

- Rougher feed — исходное сырье
- Rougher additions — флотационные реагенты: Xanthate, Sulphate, Depressant
- Xanthate — ксантогенат
- Sulphate — сульфат
- Depressant — депрессант
- Rougher process — флотация
- Rougher tails — отвальные хвосты
- Float banks — флотационная установка
- Cleaner process — очистка
- Rougher Au — черновой концентрат золота
- Final Au — финальный концентрат золота

**Параметры этапов**

- air amount — объём воздуха
- fluid levels — уровень жидкости
- feed size — размер гранул сырья
- feed rate — скорость подачи

**Наименование признаков**

Наименование признаков такое: [этап].[тип_параметра].[название_параметра]

Пример: rougher.input.feed_ag

Значения для блока [этап]:

- rougher — флотация
- primary_cleaner — первичная очистка
- secondary_cleaner — вторичная очистка
- final — финальные характеристики

Значения для блока [тип_параметра]:

- input — параметры сырья
- output — параметры продукта
- state — параметры, характеризующие текущее состояние этапа
- calculation — расчётные характеристики

## Структура проекта

1. Подготовка данных

	- Описание данных
	- Импорт библиотек
	- Чтение файлов и изучение данных
		- Расчёт эффективности обогащения
		- Анализ признаков
	- Предобработка данных

2. Анализ данных

	- Анализ концентрации металлов на различных этапах очистки
	- Анализ размера гранул на обучающей и тестовой выборках
	- Анализ суммарной концентрации всех металлов на разных стадиях

3. Модель

	- Функция для расчета sMAPE
	- Обучение и сравнение моделей
	- Проверка модели на тестовой выборке
	- Проверка модели на адекватность
4. Общий вывод

## Используемые библиотеки и модули
`matplotlib` `numpy` `pandas` `plotly` `seaborn` `sklearn` 

## Контакты

<div id="badges" >
  <a href="https://t.me/Dazzle_dazzle_dazzle">
    <img src="https://img.shields.io/badge/Telegram-deepskyblue?style=for-the-badge&logo=telegram&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/konstantin-sinkevich-39b982265/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
