# kaggle-humanity

## Table of contents
1. [Best configuration](#best_config)
2. [Best model](#best_model)
3. [Other experimental models](#other_models)

### 1. Best configuration <a id="best_config"/>

```
USE_FEATURE_DROP = False
USE_FEATURE_ENGINEERING = False
USE_FEATURE_SCALING = False
USE_FEATURE_POLYNOMIAL = False
USE_OUTLIER_DETECTION = True
```

### 2. Best model <a id="best_model"/>

**GradientBoostingRegressor**
```text
RMSE=1.8376145929369048
accuracy=23.67549668874172%
```

```
USE_FEATURE_DROP = False
USE_FEATURE_ENGINEERING = False
USE_FEATURE_SCALING = False
USE_OUTLIER_DETECTION = True
USE_FEATURE_POLYNOMIAL = False
```

### 3. Other experimental models <a id="other_models"/>

```text
----------------------------------------
AdaBoostRegressor
Average RMSE: 2.321849771811477
Average accuracy: 25.398437091730834%
----------------------------------------
GradientBoostingRegressor
Average RMSE: 1.8713595504391913
Average accuracy: 51.84697703616161%
----------------------------------------
RandomForestRegressor
Average RMSE: 1.9139742254290497
Average accuracy: 49.72607132638211%
----------------------------------------
DecisionTreeRegressor
Average RMSE: 2.591505330181916
Average accuracy: 5.748209635917422%
----------------------------------------
KNeighborsRegressor
Average RMSE: 1.954786958463795
Average accuracy: 48.13132264781077%
----------------------------------------
SVR with linear kernel
Average RMSE: 1.9971005473001322
Average accuracy: 45.00286028092048%
----------------------------------------
LinearRegression
Average RMSE: 1.968712222385368
Average accuracy: 47.85118889166549%
----------------------------------------
Ridge
Average RMSE: 1.9577490791604637
Average accuracy: 46.92694281850472%
----------------------------------------
Lasso
Average RMSE: 2.715542705506666
Average accuracy: -1.3070946129097871%
----------------------------------------
```

The best model from model selection process is **GradientBoostingRegressor**
```text
Minimum RMSE: 1.8713595504391913
Maximum accuracy: 51.84697703616161%
```