# Классификация временных рядов

Бинарная классификация временных рядов различной длины при помощи LSTM.
Целевая метрика - ROC AUC = 0.9261

## Файлы

- **final_code.ipynb** - Итоговое решение(скрипт)
- **train_model.ipynb** - Обучение модели и предобработка всех признаков
- **best_model.pth** - веса обученной модели
- **train.parquet** - тренировочный набор данных
- **test.parquet** - тестовый набор данных
- **submission.csv** - итоговые предсказания
- **requirements.txt** - список зависимостей

## Установка

1. Склонируйте репозиторий:

- **git clone https://github.com/White4ndBlack/vk_DS.git**

2. Установите необходимые зависимости:

- **pip install -r requirements.txt**

## Использование

1. train_model.ipynb Содержит предобработку данных и обучение модели LSTM
2. final_code.ipynb Содержит скрипт c обученной моделью






