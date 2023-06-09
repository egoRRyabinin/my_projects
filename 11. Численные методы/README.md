# Определение стоимости автомобилей

### Цели проекта

- Необходимо построить модель для определения стоимости автомобилей на основании технических характеристик, комплектаций.  
- Метрики оптимизации:  

    1. качество предсказания (RMSE не более 2500)  
    2. скорость предсказания  
    3. время обучения  

### Задачи проекта

1. Подготовка Данных  
    1.1 Изучение данных  
    1.2 Предобработка данных  
    1.3 Кодирование категориальных признаков  
    1.4 Деление на выборки  
2. Обучение моделей  
    2.1 CatBoost  
    2.2 LightGBM  
    2.3 LinearRegression
    2.4 RandomForest  
3. Анализ скорости и качества моделей по метрике RMSE  

### Итоги

- Обучены модели CatBoost, LightGBM, LinearRegression и RandomForest
- Алгоритм градиентного бустинга LightGBM показал лучшие результаты
- Метрика RMSE для LightGBM **1498.11**. Скорость обучения и предсказания **0.76** секунд
- CatBoost продемнстрировал качество на уровне LightGBM, но с меньшим в 13 раз быстродействием

### Используемые библиотеки

- *pandas*
- *numpy*
- *sklearn*
- *lightgbm*
- *catboost*
