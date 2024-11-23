<div class="alert alert-success" style="border-color: green;
border-radius: 5px">
    <font size='5' color=993399> <b> Проекты в ходе обучения на Data Science в Яндкс.Практикуме. </b>
<font size="7">??</font>
</div>
        
# Исследовние технологического процесса производства стали - steelmaking (выпускной проект).
Задача оптимизации производственных расходов: уменьшение потребления электроэнергии на этапе обработки стали.
Строится модель машинного обучения, которая должна предсказать температуру сплава в конце процесса обработки стали (задача регресии).
Модель оптимизирует процесс подгрева сплава стали при внесении легирующих добавок и позволяет уменьшить затраты на электроэргию.

Это выпускной проект в котором собраны основные преобретённые навыки.

*Используемые библиотеки:* numpy, pandas, matplotlib, seaborn, ploty, sklearn, lightgbm, catboost, hyperopt, keras
*Используемые инструменты:*
- Анализ и чистка данных (обработка пропусков и выбросов): describe, agg, groupby, apply, query, to_datetime, isnull, fillna, dropna, join, concat, ...;
- Проверка данных на мультиколлениарность: corr (heatmap), variance_inflation_factor (VIF анализ), SelectKBest (F-regression);
- Предобработка данных (разделение на выборки и масштабирование): train_test_split, StandardScaler;
- Построение моделей:
1. Линейная регрессии (LinearRegression);
2. K-ближайших соседей (KNeighborsRegressor);
3. Случайный лес (RandomForestRegressor);
4. Градиентный бустинг (LightGBM, CatBoost);
5. Нейросети (полносвязная сеть (maltylayer perceptron), сверточная сеть (convolution multylayer network), сеть с архитектурой LeNet);
- Кросс-валидация и настройка гиперпараметров (cross_val_score, GridSearchCV, RandomizedSearchCV, hyperopt);
- Анализ значимых признаков (RidgeCV, feature_importances, permutation_importance);
- Упаковка в пайплайн (Pipeline) нескольких шагов, упаковка в пайплайн несколько моделей, использование пайплайн совместно с кросс-валидацией и оптимизацией гиперпараметров.
