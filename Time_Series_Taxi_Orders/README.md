# Прогнозирование заказов такси

## Задача
Вы работаете в компании такси. Ваши коллеги собрали исторические данные о заказах такси за последние 6 месяцев. Перед вами стоит задача - создать модель машинного обучения, способную предсказывать количество заказов такси на следующий час. Это необходимо для привлечания оптимального количества водителей в любой момент времени в зависимости от загрузки. 

Целевая метрика - RMSE. Задача считается выполненной, если ее значение не превышает 48.

В процессе выполнения проекта необходимо:
1. Загрузить данные и выполнить их ресемплирование по одному часу.
2. Проанализировать имеющийся временной ряд.
3. Разделить данные на обучающую и тестовую выборки. Размер тестовой выборки - 10%.
4. Обучить разные модели и найти оптимальные гиперпараметры.
5. Проверить данные на тестовой выборке и сделать выводы.

## Данные
В нашем распоряжении данные с 1 марта по 31 августа 2018 года. Количество заказов находится в столбце *num_orders*, дата и время в индексах.

## Используемые библиотеки
*pandas*

*numpy*

*matplotlib*

*statsmodels*

*scipy*

*sklearn*

*lightgbm*

*catboost*