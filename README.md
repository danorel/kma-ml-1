# kaggle-humanity

## Table of contents
1. [Data experiment: all data pipeline flags off](#experiment1)
2. [Data experiment: all data pipeline flags on](#experiment2)

## Experiments with data pipeline

### 1. All data instruments are turned off: <a id="experiment1"/>
```
USE_FEATURE_EXTRACTION = False
USE_FEATURE_SCALING = False
USE_OUTLIER_DETECTION = False
```
----------------------------------------
**OutputCodeClassifier<br/>**
Average RMSE: 3.052158332470308<br/>
Average accuracy: 20.042462845010615%
----------------------------------------
**GaussianNB<br/>**
Average RMSE: 8.124984708233635<br/>
Average accuracy: 10.414012738853502%
----------------------------------------
**KNeighborsClassifier<br/>**
Average RMSE: 2.8393874262905903<br/>
Average accuracy: 25.923566878980886%
----------------------------------------
**SVC(poly)<br/>**
Average RMSE: 2.921777636134703<br/>
Average accuracy: 25.84925690021232%
----------------------------------------
**SVC(linear)<br/>**
Average RMSE: 2.9800613958596633<br/>
Average accuracy: 24.554140127388536%
----------------------------------------
**LogisticRegression<br/>**
Average RMSE: 2.903073912909693<br/>
Average accuracy: 25.690021231422506%
----------------------------------------
**DecisionTreeClassifier<br/>**
Average RMSE: 2.9559382943441417<br/>
Average accuracy: 20.000000000000004%
----------------------------------------
**Minimum RMSE: 2.8393874262905905%<br/>
Maximum accuracy: 25.923566878980886%**

### 2. All data instruments are turned on: <a id="experiment2"/>
```
USE_FEATURE_EXTRACTION = True
USE_FEATURE_SCALING = True
USE_OUTLIER_DETECTION = True
```

----------------------------------------
**OutputCodeClassifier<br/>**
Average RMSE: 3.3168386776490215<br/>
Average accuracy: 17.1947194719472%
----------------------------------------
**GaussianNB<br/>**
Average RMSE: 2.8520343912989596<br/>
Average accuracy: 18.97689768976898%
----------------------------------------
**KNeighborsClassifier<br/>**
Average RMSE: 2.599180154877789<br/>
Average accuracy: 25.951595159515957%
----------------------------------------
**SVC(poly)<br/>**
Average RMSE: 2.60978010365839<br/>
Average accuracy: 24.807480748074806%
----------------------------------------
**SVC(linear)<br/>**
Average RMSE: 2.718950219544472<br/>
Average accuracy: 20.08800880088009%
----------------------------------------
**LogisticRegression<br/>**
Average RMSE: 2.5927653254698386<br/>
Average accuracy: 24.543454345434547%
----------------------------------------
**DecisionTreeClassifier<br/>**
Average RMSE: 3.1717606747929565<br/>
Average accuracy: 16.886688668866885%
----------------------------------------
**Minimum RMSE: 2.5927653254698384%<br/>
Maximum accuracy: 24.543454345434547%**