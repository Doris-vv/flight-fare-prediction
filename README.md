# Flight Fare Prediction
The raw data for this project is only one file. This data represents the information of flight. In this project, we are going to predict the flight fare with machine learning model.

# Data Source
You can download the data from https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

# Procedure
|Process           |Content                                                                   |
|------------------|--------------------------------------------------------------------------|
|Preparation|Import the libraries and load the dataset|
|Preprocessing|Check the missing values, derive numeric features and handle categorical data|
|Feature Selection|Use feature_importances_ and VIF|
|Fit Model|Use random forest，logistic regression， KNeighborsRegressor， decision tree and SVR to predict the price|

# Model Performance
|Model                  |Training score      |r2 score        |MAE               |MSE                |RMSE               |
|-----------------------|--------------------|----------------|------------------|-------------------|-------------------|
|RandomForestRegressor|0.9542220062942047|0.8239901040130895|1182.0976978724748|3496604.673709347|1869.9210340838854|
|LogisticRegression|0.21875|0.25464881507217596|2508.069|14807113.101|3848.001182562188|
|KNeighborsRegressor|0.7196168713774549|0.5880616647777752|1855.9205|8183548.43142|2860.6902019302966|
|DecisionTreeRegressor|0.9763540213205016|0.6608974546280963|1434.471825|6736595.907665972|2595.495310661526|
|SVR|0.001038791488200963|-0.003039112895815599|3571.263964206548|19926329.882756207|4463.891786631505|
