# Car Price Prediction / Прогнозирование цен на автомобили

## Overview / Обзор

This project is a machine learning pipeline for predicting used car prices based on advertisement data. It includes data exploration, feature engineering, and model training steps.

Этот проект представляет собой конвейер машинного обучения для прогнозирования цен на подержанные автомобили на основе данных объявлений. Он включает этапы исследования данных, создания признаков и обучения моделей.

---

## Contents / Содержание

- `data/raw/` — исходные данные (CSV с объявлениями)
- `data/processed/` — подготовленные данные для обучения моделей
- `notebooks/` — Jupyter notebooks:
  - `01_eda.ipynb` — разведочный анализ (EDA)
  - `02_feature_engineering.ipynb` — очистка данных и создание признаков
  - `03_modeling.ipynb` — обучение и сравнение моделей
- `models/` — (опционально) сохранённые модели
- `requirements.txt` — зависимости проекта

---

## Quick Start / Быстрый старт

1. Создайте и активируйте виртуальное окружение (рекомендуется):
   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS / Linux
   source .venv/bin/activate
   ```

2. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

3. Запустите ноутбуки по порядку:
   - `notebooks/01_eda.ipynb`
   - `notebooks/02_feature_engineering.ipynb`
   - `notebooks/03_modeling.ipynb`

---

## Data / Данные

- `data/raw/all_car_adverts.csv` — исходный датасет с объявлениями о продаже автомобилей.
- `data/processed/cars_processed.csv` — очищенные и преобразованные данные, готовые для обучения модели.

---

## Notes / Примечания

- В ноутбуках используются библиотеки `pandas`, `numpy`, `matplotlib`, `seaborn` и `scikit-learn`.
- Если данные меняются, рекомендуем повторно запустить шаги очистки и подготовку признаков.

---

## License / Лицензия

(Добавьте здесь информацию о лицензии, если требуется.)
