# Heart-Failure-Prediction
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide. This dataset contains 12 features that can be used to predict mortality by heart failure. 
心血管疾病 (CVD) 是全球第一大死因，估计每年夺走 1790 万人的生命，占全球所有死亡人数的 31%。 5 例 CVD 死亡中有 4 例死于心脏病发作和中风，其中三分之一的死亡过早发生在 70 岁以下的人群中。 心力衰竭是由 CVD 引起的常见事件，该数据集包含 11 个可用于预测可能的心脏病的特征。
患有心血管疾病或处于高心血管风险（由于存在一种或多种风险因素，如高血压、糖尿病、高脂血症或已经确定的疾病）的人需要早期检测和管理，其中机器学习模型可以提供很大帮助。
该数据集是通过组合已经独立可用但之前未组合的不同数据集创建的。 在这个数据集中，5 个心脏数据集结合了 11 个共同特征，这使其成为迄今为止可用于研究目的的最大心脏病数据集。 用于其管理的五个数据集是：

克利夫兰：303 次观察
匈牙利：294 次观察
瑞士：123 次观察
弗吉尼亚州：200 次观察
Stalog（心脏）数据集：270 次观察
总计：1190 次观察
重复：272 次观察
(以上为谷歌翻译机翻)
在本次项目中，我利用python的numpy, pandas, matplotlib, seaborn, sklearn, catboost等包，对12个可能造成心脏病的因素进行了可视化分析，并且利用sklearn, pycaret, catboost 等包，综合比较了gbc,rf,et等模型，最终选择了精度最高的catboost，并利用训练好的catboost模型实现了一个有图形化界面的心脏病预测程序。

运行环境：
Python 3.11.1
import plotly.express as px
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
Import sklearn
Import pycaret
Import catboost
