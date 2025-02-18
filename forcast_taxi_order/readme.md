# Прогнозирование заказов такси

***Описание проекта:***<br/>
Сервис такси хочет привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов на следующий час. 

***Задача:***<br/>
Спрогнозировать количество заказов такси на следующий час (задача регрессии, метрика качества *RMSE*).


***Используемые библиотеки и инструменты:***<br/>
pandas, numpy, time, datetime, matplotlib, statsmodels (seasonal_decompose, tsaplots), sklearn, catboost, lightgbm, linear_model (LogisticRegression, Ridge), ensemble (RandomForestRegressor), metrics (make_scorer), model_selection (train_test_split, TimeSeriesSplit, cross_val_score, GridSearchCV, RandomizedSearchCV).
____