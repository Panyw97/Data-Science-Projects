# Notes

## Data Preprocessing

1. 已将‘visitStartTime’, 'geoNetwork.metro', 'geoNetwork.latitude', 'geoNetwork.longitude', 'geoNetwork.networkDomain', 'geoNetwork.networkLocation', 'totals.pageviews', 'totals.newVisits', 'trafficSource.keyword', 'trafficSource.adwordsClickInfo.criteriaParameters',  'trafficSource.adwordsClickInfo.gclId', 'trafficSource.campaignCode'
几列drop掉

2. 已将‘visitStartTime’转换为'year', 'month', 'day', 'hour', 'min', 'sec'，具体使用还需讨论

3. 处理后的部分变量存在只有**‘not available in demo dataset’**的值，是否保留还需讨论


## Model List

目前考虑尝试Keras, XGBoost, LightGBM这三个ML Framework。

* Keras：深度学习模型
* XGBoost：Gradient Boosting
* LightGBM：Gradient Boosting



## Model Construction



## Model Improvement



