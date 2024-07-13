# Airticket-price-forecast

Для прогноза цен на авиабилеты был выбран метод машинного обучения. На основе датасета "Прогноз цен на авиабилеты" (https://www.kaggle.com/competitions/aviachipta-narxini-bashorat-qilish/overview) была создана и обучена модель. Над датасетом был выполнен ряд преобразований для приведения его к обучаемому виду. Были рассмотрены три алгоритма обучения модели: LinearRegression (MSE: 6271.0), RandomForestRegressor (MSE: 1241.0). Исходя из результатов MSE, модель была обучена на RandomForestRegressor, после чего экспортирована для backend-части проекта.
