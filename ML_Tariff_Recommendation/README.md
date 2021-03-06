# Рекомендация тарифов 

## Задача
Некая телеком-компания хочет построить систему, способную по поведению клиентов определять, какой тариф будет подходить каждому конкретному клиенту. Для этого они собрали данные о поведении пользователей двух тарифов("Продвинутый" и "Базовый"): количество использованных пользователями за месяц звонков, минут разговора, сообщений и интернет-трафика. Нужно построить модель классификации, которая будет выбирать подходящий тариф.

Предобработку данных выполнять не нужно, данные уже обработаны.

В процессе выполнения проекта нужно разбить данные на обучающую и тестовую выборки, изучить разные модели машинного обучения, оптимизировать гиперпараметры, проверить модели на тестовой выборке, проверить лучшую модель на адекватность. Используемая метрика - *accuracy*. Задача считается выполненной, если удалось достичь на тестовой выборке *accuracy* 0.75.

## Имеющиеся данные
В нашем распоряжении данные пользователей некой телеком-компании. Каждая строка характеризует поведение одного пользователя за месяц.
- *сalls* — количество звонков
- *minutes* — суммарная длительность звонков в минутах
- *messages* — количество sms-сообщений
- *mb_used* — израсходованный интернет-трафик в Мб
- *is_advanced* — каким тарифом пользовался в течение месяца («Продвинутый» — 1, «Базовый» — 0).

## Используемые библиотеки
*pandas*

*seaborn*

*scikit-learn*
