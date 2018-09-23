# Model-Insights

-- 09/20/2018 created



​	Model insight is important. As stated in this [kaggle discussion](https://www.kaggle.com/dansbecker/use-cases-for-model-insights), machine learning is "black box" stuff, in a sense that the data sicentist does not know how to extract the insights.

​	Model insights can be used to:

* Inform the feature engineering. Especially for problem with 100s raw features, the insights from model helps to figure the "golden feature" among all the chaos.
* Help directing data collection. No specific yet, details will be added.
* Inform human decision making and improve persuasiveness. Sometimes the insights can be more valuable than predictions. It is easier to win trust by showing people what fit their general understanding.



1. Feature importance

   [The kernel](https://www.kaggle.com/zehaiwang/permutation-importance/edit) talks about permutation importance, which is fast to caculate and widely used and understood.

   The general approach is to randomly shuffle a single column of data __after__ the model is fitted. Then, perform performance deteriration measures the importance of the variable shuffled. 