## 项目意义
通过分析人行数据，找出能够用于贷前管理，有效过滤风险客户的特征

## 分析过程
使用公司内部贷款客户的逾期数据，以及其对应的人行数据，经过一系列的数据分析和清洗后，使用catboost建模（bagging），
最后通过catboost输出特征的重要性的平均值，判断哪些特征具有使用价值

## 分析结果
以下是通过模型得到的人行特征重要性：  
![](rpt/feature_importance.png)

