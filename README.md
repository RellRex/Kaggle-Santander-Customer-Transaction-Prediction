# Kaggle-Santander-Customer-Transaction-Prediction
Kaggle比赛，第一个进了前10%，想分享一下自己的做法，和总结一些大神们的做法。

## count => 0.908
    kernels:https://www.kaggle.com/c/santander-customer-transaction-prediction/discussion/88889#latest-512768
    这步的做法是,将train和“真实”的test数据相结合，统计每个样本中每个特征的值，在所有该特征的取值中出现的次数。比如，对于第一个样本，特征var0的值为8.9255，在该特征所有的取值中出现了8次。
    
  <a href="https://www.kaggle.com/c/santander-customer-transaction-prediction/discussion/87486#latest-511515" taget="打开方式" name="页面锚点名称">链接文字或者图片</a>
