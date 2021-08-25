# Примеры моих студенческих проектов курса "Специалист по Data Science" Яндекс.Практикума.

Данные проекты были выполнены в ходе обучения на платформе Яндекс.Практикума, профессии "Специалист по Data Science".
Согласно требованиям обучающей платформы запрещено размещать некоторые материалы курса (ссылки, датасеты, полные описания проектов и т.п.).

| Название проекта | Задачи проекта | Описание проекта | Навыки и инструменты | Ссылка на репозиторий |
| :---------------------- | :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| Отток клиентов банка | Анализ оттока клиентов из банка для выбор стратегии (удержание старых клиентов или привлечение новых клиентов). | Из банка стали уходить клиенты каждый месяц. Спрогнозирована вероятность ухода клиента из банка в ближайшее время. Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.59. Дополнительно измерен AUC-ROC, соотнесен с F1-мерой. Обучение с учителем. Работа с несбалансированными данными. | pandas, matplotlib, sklearn | [Ссылка](https://github.com/vkhdk/Yandex_praktikum_DS/tree/main/YP_DS_2_2_bank_clients) |
| Подготовка прототипа модели для металлообрабатывающего предприятия | Разработка модели, предсказывающей коэффициент восстановления золота из золотосодержащей руды. | Компания разрабатывает решения для эффективной работы золотодобывающей отрасли. Построена модель, предсказывающая коэффициент восстановления золота из золотосодержащей руды. Проанализированы данные с параметрами добычи и очистки. Построена и обучена модель, помогающая оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. | pandas, matplotlib, sklearn, scipy, seaborn, GridSearchCV | [Ссылка](https://github.com/vkhdk/Yandex_praktikum_DS/tree/main/YP_DS_2_4_gold_recovery) |
| Прогнозирование заказов такси | Обучить модель для предсказания количества заказов такси на следующий час. | Проанализированы исторические данные о заказах такси в аэропортах. Спрогнозировано количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки. Построена модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно меньше 48. | pandas, matplotlib, sklearn, scipy, seaborn, GridSearchCV, lightgbm, statsmodels | [Ссылка](https://github.com/vkhdk/Yandex_praktikum_DS/tree/main/YP_DS_3_3_time_series) |
| Классификация комментариев | Ускорить модерацию комментариев в сообществе, автоматизировав оценку их токсичности. Обучить модель классифицировать комментарии на позитивные и негативные. | Для запуска нового сервиса интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Обучена модель классифицировать комментарии на позитивные и негативные. Проанализирован набор данных с разметкой о токсичности правок. Построена модель со значением метрики качества F1 не меньше 0.75. К текстам и временным рядам применена техника feature engineering. Векторизированы тексты посредством word2vec, GloVe, FastText.| pandas, nltk, sklearn, scipy, GridSearchCV, lightgbm | [Ссылка](https://github.com/vkhdk/Yandex_praktikum_DS/tree/main/YP_DS_3_4_text_analysis) |