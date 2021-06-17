Курсовой проект "Машинное обучение в бизнесе"

Stack:

ML: sklearn, pandas, numpy
API: flask
Данные с kaggle - https://www.kaggle.com/pinakimishrads/fake-news-classifier-data

Задача: предсказать является ли новость фейком или нет(поле label). 
Тип - Бинарная классификация

Признаки:

- title
- text

Преобразования признаков: tfidf

Модель: GradientBoostingClassifier

### Описание шагов
```
- Step_1 - загрузка данных, сбор Pipeline и обучение модели;
- Step_2 - проверка работоспособности и нашего Pipeline;
- Step_3 - Запрос к сервису;
- run_server.py - наш сервис, который запускаем
```

### Запуск 
```
 $ conda create -n venv python=3.7
 $ conda activate venv 
 $ pip install -r requirements.txt
 $ python run_server.py