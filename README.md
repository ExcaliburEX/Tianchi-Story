# 天池的一些竞赛与想法👩‍💻
---
![](https://img.shields.io/badge/build-passing-green)
![](https://img.shields.io/badge/version-up--to--date-blue)
![](https://img.shields.io/badge/coverage-100%25-orange)
![](https://img.shields.io/badge/chat-666%20online-yellowgreen)
![](https://img.shields.io/badge/stars-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-brightgreen)
[![Follow me on Twitter](https://img.shields.io/static/v1.svg?label=Follow%20%40Excaliburjp&message=🤙&color=red&logo=twitter&style=social)](https://twitter.com/Excaliburjp) 
![Copyright](https://img.shields.io/static/v1.svg?label=My%20cool%20project%20©️%20&message=%202020%20Name&labelColor=informational&color=033450) 
[![Add to Chrome](https://img.shields.io/static/v1.svg?label=Add%20to&message=Chrome%20🧘)](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd) 

---


# 全文大导航

- [二手车成交价格预测](https://github.com/ExcaliburEX/Tianchi-Story#二手车成交价格预测)
  - [1️⃣ 赛题理解✍️](https://github.com/ExcaliburEX/Tianchi-Story#1%EF%B8%8F%E2%83%A3-%E8%B5%9B%E9%A2%98%E7%90%86%E8%A7%A3%EF%B8%8F)
    - [1️⃣.1️⃣ 赛题重述](https://github.com/ExcaliburEX/Tianchi-Story#1%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E8%B5%9B%E9%A2%98%E9%87%8D%E8%BF%B0)
    - [1️⃣.2️⃣ 数据集概述](https://github.com/ExcaliburEX/Tianchi-Story#1%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A6%82%E8%BF%B0)
    - [1️⃣.3️⃣ 预测结果评价指标⚒️](https://github.com/ExcaliburEX/Tianchi-Story#1%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A3-%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E8%AF%84%E4%BB%B7%E6%8C%87%E6%A0%87%EF%B8%8F)
  - [2️⃣ 数据分析EDA](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90eda)
    - [2️⃣.1️⃣ 数据总览](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E6%80%BB%E8%A7%88)
      - [2️⃣.1️⃣.1️⃣ 数据载入](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E5%90%84%E7%A7%8D%E8%AE%A1%E7%AE%97%E5%8C%85%E7%9A%84%E5%AF%BC%E5%85%A5)
      - [2️⃣.1️⃣.2️⃣ 数据的基本形态](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E7%9A%84%E5%9F%BA%E6%9C%AC%E5%BD%A2%E6%80%81)
    - [2️⃣.2️⃣ 数据的缺失情况📌](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E7%9A%84%E7%BC%BA%E5%A4%B1%E6%83%85%E5%86%B5)
    - [2️⃣.3️⃣ 数据的异常情况☢️](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E7%9A%84%E5%BC%82%E5%B8%B8%E6%83%85%E5%86%B5%EF%B8%8F)
    - [2️⃣.4️⃣ 待预测的真实值的分布情况📈](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A34%EF%B8%8F%E2%83%A3-%E5%BE%85%E9%A2%84%E6%B5%8B%E7%9A%84%E7%9C%9F%E5%AE%9E%E5%80%BC%E7%9A%84%E5%88%86%E5%B8%83%E6%83%85%E5%86%B5)
    - [2️⃣.5️⃣ 数据特征相关性的分析🎎](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E7%89%B9%E5%BE%81%E7%9B%B8%E5%85%B3%E6%80%A7%E7%9A%84%E5%88%86%E6%9E%90)
      - [2️⃣.5️⃣.1️⃣ `numric`特征的相关性分析](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-numric%E7%89%B9%E5%BE%81%E7%9A%84%E7%9B%B8%E5%85%B3%E6%80%A7%E5%88%86%E6%9E%90)
      - [2️⃣.5️⃣.2️⃣ `pandas_profiling`生成数据报告📕](https://github.com/ExcaliburEX/Tianchi-Story#2%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-pandas_profiling%E7%94%9F%E6%88%90%E6%95%B0%E6%8D%AE%E6%8A%A5%E5%91%8A)
    - [3️⃣ 结语✏️](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A3-%E7%BB%93%E8%AF%AD%EF%B8%8F)
  - 特征工程
  - 建模与调参
  - 模型结果融合


# [二手车成交价格预测](https://tianchi.aliyun.com/competition/entrance/231784/introduction)


惊闻4.13日江苏省高校将要启动开学模式，我自岿然不动。山中何事？松花酿酒，春水煎茶，如是而已。
<!-- more -->


# 1️⃣ 赛题理解✍️

## 1️⃣.1️⃣ 赛题重述
    
&emsp;&emsp;这是一道来自于天池的新手练习题目，用`数据分析`、`机器学习`等手段进行 [二手车售卖价格预测](https://tianchi.aliyun.com/competition/entrance/231784/information) 的回归问题。赛题本身的思路清晰明了，即对给定的数据集进行分析探讨，然后设计模型运用数据进行训练，测试模型，最终给出选手的预测结果。

## 1️⃣.2️⃣ 数据集概述
&emsp;&emsp;赛题官方给出了来自Ebay Kleinanzeigen的二手车交易记录，总数据量超过**40w**，包含**31列**变量信息，其中**15列**为匿名变量，即`v0`至`v15`。并从中抽取**15万条**作为训练集，**5万**条作为测试集A，**5万**条作为测试集B，同时对`name`、`model`、`brand`和`regionCode`等信息进行脱敏。具体的数据表如下图：

<div class="table-wrapper" style = "center"><table style = "center">
<thead>
<tr style = "center">
<th><strong>Field</strong></th>
<th><strong>Description</strong></th>
</tr>
</thead>
<tbody style = "center">
<tr style = "center">
<td >SaleID</td>
<td>交易ID，唯一编码</td>
</tr>
<tr>
<td>name</td>
<td>汽车交易名称，已脱敏</td>
</tr>
<tr>
<td>regDate</td>
<td>汽车注册日期，例如20160101，2016年01月01日</td>
</tr>
<tr>
<td>model</td>
<td>车型编码，已脱敏</td>
</tr>
<tr>
<td>brand</td>
<td>汽车品牌，已脱敏</td>
</tr>
<tr>
<td>bodyType</td>
<td>车身类型：豪华轿车：0，微型车：1，厢型车：2，大巴车：3，敞篷车：4，双门汽车：5，商务车：6，搅拌车：7</td>
</tr>
<tr>
<td>fuelType</td>
<td>燃油类型：汽油：0，柴油：1，液化石油气：2，天然气：3，混合动力：4，其他：5，电动：6</td>
</tr>
<tr>
<td>gearbox</td>
<td>变速箱：手动：0，自动：1</td>
</tr>
<tr>
<td>power</td>
<td>发动机功率：范围 [ 0,  600 ]</td>
</tr>
<tr>
<td>kilometer</td>
<td>汽车已行驶公里，单位万km</td>
</tr>
<tr>
<td>notRepairedDamage</td>
<td>汽车有尚未修复的损坏：是：0，否：1</td>
</tr>
<tr>
<td>regionCode</td>
<td>地区编码，已脱敏</td>
</tr>
<tr>
<td>seller</td>
<td>销售方：个体：0，非个体：1</td>
</tr>
<tr>
<td>offerType</td>
<td>报价类型：提供：0，请求：1</td>
</tr>
<tr>
<td>creatDate</td>
<td>汽车上线时间，即开始售卖时间</td>
</tr>
<tr>
<td>price</td>
<td>二手车交易价格（预测目标）</td>
</tr>
<tr>
<td>v系列特征</td>
<td>匿名特征，包含v0-14在内15个匿名特征</td>
</tr>
</tbody>
</table>
</div>

### 思考💭💡
- 指标重要性
    - 数据集里面包含的很多维度的数据，对于人来说第一眼看上去就会产生直观的感觉，哪些指标对售价的影响大，哪些指标对售价的影响小，特别是对于一个长期从事二手车交易的人来说，更是如此。例如 `kilometer`(汽车已行驶公里)肯定是对于成交价格的影响是巨大的。但是如何让我设计的模型认知到这些先验知识是个棘手的问题，但我想这应该时一个很旧的问题，只是我还没有足够的知识去通晓它解决的肌理。确实，对于机器来说，这些数据只是一列列的向量，所以首要解决的就是向量的重要性。
- 简单思维
    - 简单地假设（我相信所有人都会想到的easy思路🤪），所有的变量跟预测目标成交价格是simple的线性关系，列一个包含31个自变量的线性函数，用批量梯度下降法拟合出31个自变量系数，然后用正则化解决过拟合问题。
        
        ---
        它的假设函数是这样的：
        <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24h_%7B%5Ctheta%7D%28x%29%3D%5Ctheta%5E%7BT%7D%20X%3D%5Ctheta_%7B0%7D&plus;%5Ctheta_%7B1%7D%20x_%7B1%7D&plus;%5Ctheta_%7B2%7D%20x_%7B2%7D&plus;%5Cldots&plus;%5Ctheta_%7B31%7D%20x_%7B31%7D%24%24"  />
        
        它的带有正则化的代价函数是这样的：

        <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24J%28%5Ctheta%29%3D%5Cfrac%7B1%7D%7B62%7D%20%5Csum_%7Bi%3D1%7D%5E%7B31%7D%5Cleft%5B%5Cleft%28%5Cleft%28h_%7B%5Ctheta%7D%5Cleft%28x%5E%7B%28i%29%7D%5Cright%29-y%5E%7B%28i%29%7D%5Cright%29%5E%7B2%7D&plus;%5Clambda%20%5Csum_%7Bj%3D1%7D%5E%7B31%7D%20%5Ctheta_%7Bj%7D%5E%7B2%7D%5Cright%29%5Cright%5D%24%24"  />
          
        ---
        
## 1️⃣.3️⃣ 预测结果评价指标⚒️
---
&emsp;&emsp;赛题的预测评估指标为$MAE(Mean Absolute Error)$


<img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24M%20A%20E%3D%5Cfrac%7B%5Csum%5Climits_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%7Cy_%7Bi%7D-%5Chat%7By%7D_%7Bi%7D%5Cright%7C%7D%7Bn%7D%24%24"  />

---

&emsp;&emsp;可以看出，指标就一个，没有很多维度的评价框架，不那么劝退。🤔

# 2️⃣ 数据分析EDA📊
> - EDA的价值主要在于熟悉数据集，了解数据集，对数据集进行验证来确定所获得数据集可以用于接下来的机器学习或者深度学习使用。
> - 当了解了数据集之后我们下一步就是要去了解变量间的相互关系以及变量与预测值之间的存在关系。
> - 引导数据科学从业者进行数据处理以及特征工程的步骤,使数据集的结构和特征集让接下来的预测问题更加可靠。
> - 完成对于数据的探索性分析，并对于数据进行一些图表或者文字总结并打卡。

&emsp;&emsp;当然这一步也要就解决我在 1️⃣.2️⃣ 中提出的第一个思考，能否通过探索性分析，发掘指标之间的关系，从而为模型内联性地定义出各指标的对成交价格的强弱相关性。但是EDA分析涉及的范围太大，可视化的东西很多，但是如果在后续的分析中不进行运用就是多余的工作，所以只需要挑选最重要的几个因素进行分析，具体如下：

- 数据总览，即`describe()`统计量以及`info()`数据类型
- 缺失值以及异常值检测
- 分析待预测的真实值的分布
- 特征之间的相关性分析

## 2️⃣.1️⃣ 数据总览

### 2️⃣.1️⃣.1️⃣ 数据载入


```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns # seabon是一个做可视化非常nice的包，它的别名sns是约定俗成的的东西，还有一段很有意思的故事
import missingno as msno # 用来检测缺失值
```


```python
Train_data = pd.read_csv('used_car_train_20200313.csv', sep=' ')
Test_data = pd.read_csv('used_car_testA_20200313.csv', sep=' ')
```

### 2️⃣.1️⃣.2️⃣ 数据的基本形态
- 训练集的长相


```python
Train_data.head()
Train_data.tail()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>SaleID</th>
      <th>name</th>
      <th>regDate</th>
      <th>model</th>
      <th>brand</th>
      <th>bodyType</th>
      <th>fuelType</th>
      <th>gearbox</th>
      <th>power</th>
      <th>kilometer</th>
      <th>...</th>
      <th>v_5</th>
      <th>v_6</th>
      <th>v_7</th>
      <th>v_8</th>
      <th>v_9</th>
      <th>v_10</th>
      <th>v_11</th>
      <th>v_12</th>
      <th>v_13</th>
      <th>v_14</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>149995</td>
      <td>149995</td>
      <td>163978</td>
      <td>20000607</td>
      <td>121.0</td>
      <td>10</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>163</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.280264</td>
      <td>0.000310</td>
      <td>0.048441</td>
      <td>0.071158</td>
      <td>0.019174</td>
      <td>1.988114</td>
      <td>-2.983973</td>
      <td>0.589167</td>
      <td>-1.304370</td>
      <td>-0.302592</td>
    </tr>
    <tr>
      <td>149996</td>
      <td>149996</td>
      <td>184535</td>
      <td>20091102</td>
      <td>116.0</td>
      <td>11</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>125</td>
      <td>10.0</td>
      <td>...</td>
      <td>0.253217</td>
      <td>0.000777</td>
      <td>0.084079</td>
      <td>0.099681</td>
      <td>0.079371</td>
      <td>1.839166</td>
      <td>-2.774615</td>
      <td>2.553994</td>
      <td>0.924196</td>
      <td>-0.272160</td>
    </tr>
    <tr>
      <td>149997</td>
      <td>149997</td>
      <td>147587</td>
      <td>20101003</td>
      <td>60.0</td>
      <td>11</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>90</td>
      <td>6.0</td>
      <td>...</td>
      <td>0.233353</td>
      <td>0.000705</td>
      <td>0.118872</td>
      <td>0.100118</td>
      <td>0.097914</td>
      <td>2.439812</td>
      <td>-1.630677</td>
      <td>2.290197</td>
      <td>1.891922</td>
      <td>0.414931</td>
    </tr>
    <tr>
      <td>149998</td>
      <td>149998</td>
      <td>45907</td>
      <td>20060312</td>
      <td>34.0</td>
      <td>10</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>156</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.256369</td>
      <td>0.000252</td>
      <td>0.081479</td>
      <td>0.083558</td>
      <td>0.081498</td>
      <td>2.075380</td>
      <td>-2.633719</td>
      <td>1.414937</td>
      <td>0.431981</td>
      <td>-1.659014</td>
    </tr>
    <tr>
      <td>149999</td>
      <td>149999</td>
      <td>177672</td>
      <td>19990204</td>
      <td>19.0</td>
      <td>28</td>
      <td>6.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>193</td>
      <td>12.5</td>
      <td>...</td>
      <td>0.284475</td>
      <td>0.000000</td>
      <td>0.040072</td>
      <td>0.062543</td>
      <td>0.025819</td>
      <td>1.978453</td>
      <td>-3.179913</td>
      <td>0.031724</td>
      <td>-1.483350</td>
      <td>-0.342674</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 31 columns</p>
</div>




```python
Train_data.shape
```




    (150000, 31)



- 测试集的长相


```python
Test_data.head()
Test_data.tail()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>SaleID</th>
      <th>name</th>
      <th>regDate</th>
      <th>model</th>
      <th>brand</th>
      <th>bodyType</th>
      <th>fuelType</th>
      <th>gearbox</th>
      <th>power</th>
      <th>kilometer</th>
      <th>...</th>
      <th>v_5</th>
      <th>v_6</th>
      <th>v_7</th>
      <th>v_8</th>
      <th>v_9</th>
      <th>v_10</th>
      <th>v_11</th>
      <th>v_12</th>
      <th>v_13</th>
      <th>v_14</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>49995</td>
      <td>199995</td>
      <td>20903</td>
      <td>19960503</td>
      <td>4.0</td>
      <td>4</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>116</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.284664</td>
      <td>0.130044</td>
      <td>0.049833</td>
      <td>0.028807</td>
      <td>0.004616</td>
      <td>-5.978511</td>
      <td>1.303174</td>
      <td>-1.207191</td>
      <td>-1.981240</td>
      <td>-0.357695</td>
    </tr>
    <tr>
      <td>49996</td>
      <td>199996</td>
      <td>708</td>
      <td>19991011</td>
      <td>0.0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>75</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.268101</td>
      <td>0.108095</td>
      <td>0.066039</td>
      <td>0.025468</td>
      <td>0.025971</td>
      <td>-3.913825</td>
      <td>1.759524</td>
      <td>-2.075658</td>
      <td>-1.154847</td>
      <td>0.169073</td>
    </tr>
    <tr>
      <td>49997</td>
      <td>199997</td>
      <td>6693</td>
      <td>20040412</td>
      <td>49.0</td>
      <td>1</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>224</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.269432</td>
      <td>0.105724</td>
      <td>0.117652</td>
      <td>0.057479</td>
      <td>0.015669</td>
      <td>-4.639065</td>
      <td>0.654713</td>
      <td>1.137756</td>
      <td>-1.390531</td>
      <td>0.254420</td>
    </tr>
    <tr>
      <td>49998</td>
      <td>199998</td>
      <td>96900</td>
      <td>20020008</td>
      <td>27.0</td>
      <td>1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>334</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.261152</td>
      <td>0.000490</td>
      <td>0.137366</td>
      <td>0.086216</td>
      <td>0.051383</td>
      <td>1.833504</td>
      <td>-2.828687</td>
      <td>2.465630</td>
      <td>-0.911682</td>
      <td>-2.057353</td>
    </tr>
    <tr>
      <td>49999</td>
      <td>199999</td>
      <td>193384</td>
      <td>20041109</td>
      <td>166.0</td>
      <td>6</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>68</td>
      <td>9.0</td>
      <td>...</td>
      <td>0.228730</td>
      <td>0.000300</td>
      <td>0.103534</td>
      <td>0.080625</td>
      <td>0.124264</td>
      <td>2.914571</td>
      <td>-1.135270</td>
      <td>0.547628</td>
      <td>2.094057</td>
      <td>-1.552150</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 30 columns</p>
</div>




```python
Test_data.shape
```




    (50000, 30)



1. 可以看出，数据的分散程度很大，有整型，有浮点，有正数，有负数，还有日期，当然可以当成是字符串。另外如果数据都换算成数值的话，数据间差距特别大，有些成千上万，有些几分几厘，这样在预测时就难以避免地会忽视某些值的作用，所以需要对其进行归一化。
2. `shape`的运用是也十分重要，对数据的大小要心中有数

- 用`describe()`来对数据进行基本统计量的分析，关于`describe()`的基本参数如下（且其默认只对数值型数据进行分析，如果有字符串，时间序列等的数据，会减少统计的项目）：
    - `count`：一列的元素个数；
    - `mean`：一列数据的平均值；
    - `std`：一列数据的均方差；（方差的算术平方根，反映一个数据集的离散程度：越大，数据间的差异越大，数据集中数据的离散程度越高；越小，数据间的大小差异越小，数据集中的数据离散程度越低）
    - `min`：一列数据中的最小值；
    - `max`：一列数中的最大值；
    - `25%`：一列数据中，前 25% 的数据的平均值；
    - `50%`：一列数据中，前 50% 的数据的平均值；
    - `75%`：一列数据中，前 75% 的数据的平均值；
- 用`info()`来查看数据类型，并主要查看是否有异常数据


```python
Train_data.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>SaleID</th>
      <th>name</th>
      <th>regDate</th>
      <th>model</th>
      <th>brand</th>
      <th>bodyType</th>
      <th>fuelType</th>
      <th>gearbox</th>
      <th>power</th>
      <th>kilometer</th>
      <th>...</th>
      <th>v_5</th>
      <th>v_6</th>
      <th>v_7</th>
      <th>v_8</th>
      <th>v_9</th>
      <th>v_10</th>
      <th>v_11</th>
      <th>v_12</th>
      <th>v_13</th>
      <th>v_14</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>count</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>1.500000e+05</td>
      <td>149999.000000</td>
      <td>150000.000000</td>
      <td>145494.000000</td>
      <td>141320.000000</td>
      <td>144019.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>...</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
      <td>150000.000000</td>
    </tr>
    <tr>
      <td>mean</td>
      <td>74999.500000</td>
      <td>68349.172873</td>
      <td>2.003417e+07</td>
      <td>47.129021</td>
      <td>8.052733</td>
      <td>1.792369</td>
      <td>0.375842</td>
      <td>0.224943</td>
      <td>119.316547</td>
      <td>12.597160</td>
      <td>...</td>
      <td>0.248204</td>
      <td>0.044923</td>
      <td>0.124692</td>
      <td>0.058144</td>
      <td>0.061996</td>
      <td>-0.001000</td>
      <td>0.009035</td>
      <td>0.004813</td>
      <td>0.000313</td>
      <td>-0.000688</td>
    </tr>
    <tr>
      <td>std</td>
      <td>43301.414527</td>
      <td>61103.875095</td>
      <td>5.364988e+04</td>
      <td>49.536040</td>
      <td>7.864956</td>
      <td>1.760640</td>
      <td>0.548677</td>
      <td>0.417546</td>
      <td>177.168419</td>
      <td>3.919576</td>
      <td>...</td>
      <td>0.045804</td>
      <td>0.051743</td>
      <td>0.201410</td>
      <td>0.029186</td>
      <td>0.035692</td>
      <td>3.772386</td>
      <td>3.286071</td>
      <td>2.517478</td>
      <td>1.288988</td>
      <td>1.038685</td>
    </tr>
    <tr>
      <td>min</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.991000e+07</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.500000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>-9.168192</td>
      <td>-5.558207</td>
      <td>-9.639552</td>
      <td>-4.153899</td>
      <td>-6.546556</td>
    </tr>
    <tr>
      <td>25%</td>
      <td>37499.750000</td>
      <td>11156.000000</td>
      <td>1.999091e+07</td>
      <td>10.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>75.000000</td>
      <td>12.500000</td>
      <td>...</td>
      <td>0.243615</td>
      <td>0.000038</td>
      <td>0.062474</td>
      <td>0.035334</td>
      <td>0.033930</td>
      <td>-3.722303</td>
      <td>-1.951543</td>
      <td>-1.871846</td>
      <td>-1.057789</td>
      <td>-0.437034</td>
    </tr>
    <tr>
      <td>50%</td>
      <td>74999.500000</td>
      <td>51638.000000</td>
      <td>2.003091e+07</td>
      <td>30.000000</td>
      <td>6.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>110.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.257798</td>
      <td>0.000812</td>
      <td>0.095866</td>
      <td>0.057014</td>
      <td>0.058484</td>
      <td>1.624076</td>
      <td>-0.358053</td>
      <td>-0.130753</td>
      <td>-0.036245</td>
      <td>0.141246</td>
    </tr>
    <tr>
      <td>75%</td>
      <td>112499.250000</td>
      <td>118841.250000</td>
      <td>2.007111e+07</td>
      <td>66.000000</td>
      <td>13.000000</td>
      <td>3.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>150.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.265297</td>
      <td>0.102009</td>
      <td>0.125243</td>
      <td>0.079382</td>
      <td>0.087491</td>
      <td>2.844357</td>
      <td>1.255022</td>
      <td>1.776933</td>
      <td>0.942813</td>
      <td>0.680378</td>
    </tr>
    <tr>
      <td>max</td>
      <td>149999.000000</td>
      <td>196812.000000</td>
      <td>2.015121e+07</td>
      <td>247.000000</td>
      <td>39.000000</td>
      <td>7.000000</td>
      <td>6.000000</td>
      <td>1.000000</td>
      <td>19312.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.291838</td>
      <td>0.151420</td>
      <td>1.404936</td>
      <td>0.160791</td>
      <td>0.222787</td>
      <td>12.357011</td>
      <td>18.819042</td>
      <td>13.847792</td>
      <td>11.147669</td>
      <td>8.658418</td>
    </tr>
  </tbody>
</table>
<p>8 rows × 30 columns</p>
</div>




```python
Test_data.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>SaleID</th>
      <th>name</th>
      <th>regDate</th>
      <th>model</th>
      <th>brand</th>
      <th>bodyType</th>
      <th>fuelType</th>
      <th>gearbox</th>
      <th>power</th>
      <th>kilometer</th>
      <th>...</th>
      <th>v_5</th>
      <th>v_6</th>
      <th>v_7</th>
      <th>v_8</th>
      <th>v_9</th>
      <th>v_10</th>
      <th>v_11</th>
      <th>v_12</th>
      <th>v_13</th>
      <th>v_14</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>count</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>5.000000e+04</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>48587.000000</td>
      <td>47107.000000</td>
      <td>48090.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>...</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
      <td>50000.000000</td>
    </tr>
    <tr>
      <td>mean</td>
      <td>174999.500000</td>
      <td>68542.223280</td>
      <td>2.003393e+07</td>
      <td>46.844520</td>
      <td>8.056240</td>
      <td>1.782185</td>
      <td>0.373405</td>
      <td>0.224350</td>
      <td>119.883620</td>
      <td>12.595580</td>
      <td>...</td>
      <td>0.248669</td>
      <td>0.045021</td>
      <td>0.122744</td>
      <td>0.057997</td>
      <td>0.062000</td>
      <td>-0.017855</td>
      <td>-0.013742</td>
      <td>-0.013554</td>
      <td>-0.003147</td>
      <td>0.001516</td>
    </tr>
    <tr>
      <td>std</td>
      <td>14433.901067</td>
      <td>61052.808133</td>
      <td>5.368870e+04</td>
      <td>49.469548</td>
      <td>7.819477</td>
      <td>1.760736</td>
      <td>0.546442</td>
      <td>0.417158</td>
      <td>185.097387</td>
      <td>3.908979</td>
      <td>...</td>
      <td>0.044601</td>
      <td>0.051766</td>
      <td>0.195972</td>
      <td>0.029211</td>
      <td>0.035653</td>
      <td>3.747985</td>
      <td>3.231258</td>
      <td>2.515962</td>
      <td>1.286597</td>
      <td>1.027360</td>
    </tr>
    <tr>
      <td>min</td>
      <td>150000.000000</td>
      <td>0.000000</td>
      <td>1.991000e+07</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.500000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>-9.160049</td>
      <td>-5.411964</td>
      <td>-8.916949</td>
      <td>-4.123333</td>
      <td>-6.112667</td>
    </tr>
    <tr>
      <td>25%</td>
      <td>162499.750000</td>
      <td>11203.500000</td>
      <td>1.999091e+07</td>
      <td>10.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>75.000000</td>
      <td>12.500000</td>
      <td>...</td>
      <td>0.243762</td>
      <td>0.000044</td>
      <td>0.062644</td>
      <td>0.035084</td>
      <td>0.033714</td>
      <td>-3.700121</td>
      <td>-1.971325</td>
      <td>-1.876703</td>
      <td>-1.060428</td>
      <td>-0.437920</td>
    </tr>
    <tr>
      <td>50%</td>
      <td>174999.500000</td>
      <td>52248.500000</td>
      <td>2.003091e+07</td>
      <td>29.000000</td>
      <td>6.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>109.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.257877</td>
      <td>0.000815</td>
      <td>0.095828</td>
      <td>0.057084</td>
      <td>0.058764</td>
      <td>1.613212</td>
      <td>-0.355843</td>
      <td>-0.142779</td>
      <td>-0.035956</td>
      <td>0.138799</td>
    </tr>
    <tr>
      <td>75%</td>
      <td>187499.250000</td>
      <td>118856.500000</td>
      <td>2.007110e+07</td>
      <td>65.000000</td>
      <td>13.000000</td>
      <td>3.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>150.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.265328</td>
      <td>0.102025</td>
      <td>0.125438</td>
      <td>0.079077</td>
      <td>0.087489</td>
      <td>2.832708</td>
      <td>1.262914</td>
      <td>1.764335</td>
      <td>0.941469</td>
      <td>0.681163</td>
    </tr>
    <tr>
      <td>max</td>
      <td>199999.000000</td>
      <td>196805.000000</td>
      <td>2.015121e+07</td>
      <td>246.000000</td>
      <td>39.000000</td>
      <td>7.000000</td>
      <td>6.000000</td>
      <td>1.000000</td>
      <td>20000.000000</td>
      <td>15.000000</td>
      <td>...</td>
      <td>0.291618</td>
      <td>0.153265</td>
      <td>1.358813</td>
      <td>0.156355</td>
      <td>0.214775</td>
      <td>12.338872</td>
      <td>18.856218</td>
      <td>12.950498</td>
      <td>5.913273</td>
      <td>2.624622</td>
    </tr>
  </tbody>
</table>
<p>8 rows × 29 columns</p>
</div>




```python
Train_data.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 150000 entries, 0 to 149999
    Data columns (total 31 columns):
    SaleID               150000 non-null int64
    name                 150000 non-null int64
    regDate              150000 non-null int64
    model                149999 non-null float64
    brand                150000 non-null int64
    bodyType             145494 non-null float64
    fuelType             141320 non-null float64
    gearbox              144019 non-null float64
    power                150000 non-null int64
    kilometer            150000 non-null float64
    notRepairedDamage    150000 non-null object
    regionCode           150000 non-null int64
    seller               150000 non-null int64
    offerType            150000 non-null int64
    creatDate            150000 non-null int64
    price                150000 non-null int64
    v_0                  150000 non-null float64
    v_1                  150000 non-null float64
    v_2                  150000 non-null float64
    v_3                  150000 non-null float64
    v_4                  150000 non-null float64
    v_5                  150000 non-null float64
    v_6                  150000 non-null float64
    v_7                  150000 non-null float64
    v_8                  150000 non-null float64
    v_9                  150000 non-null float64
    v_10                 150000 non-null float64
    v_11                 150000 non-null float64
    v_12                 150000 non-null float64
    v_13                 150000 non-null float64
    v_14                 150000 non-null float64
    dtypes: float64(20), int64(10), object(1)
    memory usage: 35.5+ MB
    


```python
Test_data.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 50000 entries, 0 to 49999
    Data columns (total 30 columns):
    SaleID               50000 non-null int64
    name                 50000 non-null int64
    regDate              50000 non-null int64
    model                50000 non-null float64
    brand                50000 non-null int64
    bodyType             48587 non-null float64
    fuelType             47107 non-null float64
    gearbox              48090 non-null float64
    power                50000 non-null int64
    kilometer            50000 non-null float64
    notRepairedDamage    50000 non-null object
    regionCode           50000 non-null int64
    seller               50000 non-null int64
    offerType            50000 non-null int64
    creatDate            50000 non-null int64
    v_0                  50000 non-null float64
    v_1                  50000 non-null float64
    v_2                  50000 non-null float64
    v_3                  50000 non-null float64
    v_4                  50000 non-null float64
    v_5                  50000 non-null float64
    v_6                  50000 non-null float64
    v_7                  50000 non-null float64
    v_8                  50000 non-null float64
    v_9                  50000 non-null float64
    v_10                 50000 non-null float64
    v_11                 50000 non-null float64
    v_12                 50000 non-null float64
    v_13                 50000 non-null float64
    v_14                 50000 non-null float64
    dtypes: float64(20), int64(9), object(1)
    memory usage: 11.4+ MB
    

从上面的统计量与信息来看，没有什么特别之处，就数据类型来说`notRepairedDamage`的类型是`object`是个另类，后续要进行特殊处理。

## 2️⃣.2️⃣ 数据的缺失情况📌
&emsp;&emsp;`pandas`内置了`isnull()`可以用来判断是否有缺失值，它会对空值和NA进行判断然后返回`True`或`False`。


```python
Train_data.isnull().sum()
```




    SaleID                  0
    name                    0
    regDate                 0
    model                   1
    brand                   0
    bodyType             4506
    fuelType             8680
    gearbox              5981
    power                   0
    kilometer               0
    notRepairedDamage       0
    regionCode              0
    seller                  0
    offerType               0
    creatDate               0
    price                   0
    v_0                     0
    v_1                     0
    v_2                     0
    v_3                     0
    v_4                     0
    v_5                     0
    v_6                     0
    v_7                     0
    v_8                     0
    v_9                     0
    v_10                    0
    v_11                    0
    v_12                    0
    v_13                    0
    v_14                    0
    dtype: int64




```python
Test_data.isnull().sum()
```




    SaleID                  0
    name                    0
    regDate                 0
    model                   0
    brand                   0
    bodyType             1413
    fuelType             2893
    gearbox              1910
    power                   0
    kilometer               0
    notRepairedDamage       0
    regionCode              0
    seller                  0
    offerType               0
    creatDate               0
    v_0                     0
    v_1                     0
    v_2                     0
    v_3                     0
    v_4                     0
    v_5                     0
    v_6                     0
    v_7                     0
    v_8                     0
    v_9                     0
    v_10                    0
    v_11                    0
    v_12                    0
    v_13                    0
    v_14                    0
    dtype: int64



- 可以看出缺失的数据值主要集中在`bodyType`，`fuelType`，`gearbox`，这三个特征中。训练集中`model`缺失了一个值，但是无伤大雅。至于如何填充，亦或是删除这些数据，需要后期在选用模型时再做考虑。
- 同时我们也可以通过`missingno`库查看缺省值的其他属性。
    - 矩阵图`matrix`
    - 柱状图`bar`
    - 热力图`heatmap`
    - 树状图`dendrogram`

**缺省热力图**

&emsp;&emsp;热力图表示两个特征之间的缺失相关性，即一个变量的存在或不存在如何强烈影响的另一个的存在。如果`x`和`y`的热度值是1，则代表当`x`缺失时，`y`也百分之百缺失。如果`x`和`y`的热度相关性为-1，说明`x`缺失的值，那么`y`没有缺失；而`x`没有缺失时，`y`为缺失。至于 矩阵图，与柱状图没有查看的必要，我们可以用缺省热力图观察一下情况：




```python
msno.heatmap(Train_data.sample(10000))
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1c62d5c07f0>



![训练集相关性热力图](https://img-blog.csdnimg.cn/2020032202134617.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)



```python
msno.heatmap(Test_data.sample(10000))
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1c62de62d30>



![测试集相关性热力图](https://img-blog.csdnimg.cn/202003220214118.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


**树状图**

&emsp;&emsp;树形图使用层次聚类算法通过它们的无效性相关性（根据二进制距离测量）将变量彼此相加。在树的每个步骤，基于哪个组合最小化剩余簇的距离来分割变量。变量集越单调，它们的总距离越接近零，并且它们的平均距离（y轴）越接近零。


```python
msno.dendrogram(Train_data.sample(10000))
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1c62de92390>




![训练集聚类图](https://img-blog.csdnimg.cn/2020032202142868.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


```python
msno.dendrogram(Test_data.sample(10000))
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1c62d7df400>



![测试集聚类图](https://img-blog.csdnimg.cn/20200322021441792.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

由上面的热力图以及聚类图可以看出，各个缺失值之间的相关性并不明显。

## 2️⃣.3️⃣ 数据的异常情况☢️
&emsp;&emsp;因为之前发现`notRepairedDamage`的类型是`object`是个另类，所以看一下它的具体情况。



```python
Train_data['notRepairedDamage'].value_counts()
```




    0.0    111361
    -       24324
    1.0     14315
    Name: notRepairedDamage, dtype: int64




```python
Test_data['notRepairedDamage'].value_counts()
```




    0.0    37249
    -       8031
    1.0     4720
    Name: notRepairedDamage, dtype: int64



发现有'-'的存在，这可以算是`NaN`的一种，所以可以将其替换为`NaN`


```python
Train_data['notRepairedDamage'].replace('-', np.nan, inplace=True)
Test_data['notRepairedDamage'].replace('-', np.nan, inplace=True)
```

## 2️⃣.4️⃣ 待预测的真实值的分布情况📈
&emsp;&emsp;我们先来看看价格预测值的分布情况


```python
Train_data['price']

```




    0         1850
    1         3600
    2         6222
    3         2400
    4         5200
              ... 
    149995    5900
    149996    9500
    149997    7500
    149998    4999
    149999    4700
    Name: price, Length: 150000, dtype: int64




```python
Train_data['price'].value_counts()
```




    500      2337
    1500     2158
    1200     1922
    1000     1850
    2500     1821
             ... 
    25321       1
    8886        1
    8801        1
    37920       1
    8188        1
    Name: price, Length: 3763, dtype: int64



嗯哼，平淡无奇，接下来最重要的是要看一下历史成交价格的**偏度（Skewness）**与**峰度（Kurtosis）**，此外自然界最优美的分布式正态分布，所以也要看一下待预测的价格分布是否满足正态分布。
再解释一下**偏度**与**峰度**，一般会拿偏度和峰度来看数据的分布形态，而且一般会跟正态分布做比较，我们把正态分布的偏度和峰度都看做零。如果算到偏度峰度不为0，即表明变量存在左偏右偏，或者是高顶平顶。

- **偏度（Skewness）**
是描述数据分布形态的统计量，其描述的是某总体取值分布的对称性，简单来说就是数据的不对称程度。
    - Skewness = 0 ，分布形态与正态分布偏度相同。
    - Skewness > 0 ，正偏差数值较大，为正偏或右偏。长尾巴拖在右边，数据右端有较多的极端值。
    - Skewness < 0 ，负偏差数值较大，为负偏或左偏。长尾巴拖在左边，数据左端有较多的极端值。
    - 数值的绝对值越大，表明数据分布越不对称，偏斜程度大。
    - 计算公式

    <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24%5Cgamma_%7B1%7D%3D%5Cmathrm%7BE%7D%5Cleft%5B%5Cleft%28%5Cfrac%7BX-%5Cmu%7D%7B%5Csigma%7D%5Cright%29%5E%7B3%7D%5Cright%5D%3D%5Cfrac%7B%5Cmu_%7B3%7D%7D%7B%5Csigma%5E%7B3%7D%7D%3D%5Cfrac%7B%5Cmathrm%7BE%7D%5Cleft%5B%28X-%5Cmu%29%5E%7B3%7D%5Cright%5D%7D%7B%5Cleft%28%5Cmathrm%7BE%7D%5Cleft%5B%28X-%5Cmu%29%5E%7B2%7D%5Cright%5D%5Cright%29%5E%7B3%20/%202%7D%7D%3D%5Cfrac%7B%5Ckappa_%7B3%7D%7D%7B%5Ckappa_%7B2%7D%5E%7B3%20/%202%7D%7D%24%24"  />

    
- **峰度（Kurtosis）**
偏度是描述某变量所有取值分布形态陡缓程度的统计量，简单来说就是数据分布顶的尖锐程度。
    - Kurtosis = 0 与正态分布的陡缓程度相同。
    - Kurtosis > 0 比正态分布的高峰更加陡峭——尖顶峰。
    - urtosis<0 比正态分布的高峰来得平台——平顶峰。
    - 计算公式：
    <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24b_%7B1%7D%3D%5Cfrac%7Bm_%7B3%7D%7D%7Bs%5E%7B3%7D%7D%3D%5Cfrac%7B%5Cfrac%7B1%7D%7Bn%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B3%7D%7D%7B%5Csqrt%7B%5Cfrac%7B1%7D%7Bn-1%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B2%7D%7D%7D%3D%5Cfrac%7B%5Cfrac%7B1%7D%7Bn%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B3%7D%7D%7B%5Cleft%5B%5Cfrac%7B1%7D%7Bn-1%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B2%7D%5Cright%5D%5E%7B3%20/%202%7D%7D%24%24"  />

```python
sns.distplot(Train_data['price']);
print("Skewness: %f" % Train_data['price'].skew())
print("Kurtosis: %f" % Train_data['price'].kurt())
```

    Skewness: 3.346487
    Kurtosis: 18.995183
    


![价格分布](https://img-blog.csdnimg.cn/20200322021455210.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

很明显，预测值的数据分布不服从正态分布，偏度与峰度的值都很大，也很符合他们的定义，从图中可以看出，长尾巴拖在右边印证了峰度值很大，峰顶很尖对应了偏度值很大。以我模糊的概率统计知识，这更加像是接近于卡方或者是F分布。所以要对数据本身进行变换。


```python
plt.hist(Train_data['price'], orientation = 'vertical',histtype = 'bar', color ='red')
plt.show()
plt.hist(np.log(Train_data['price']), orientation = 'vertical',histtype = 'bar', color ='red') 
plt.show()
```


![价格直方分布图](https://img-blog.csdnimg.cn/20200322021509345.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)



![log运算后的价格直方图](https://img-blog.csdnimg.cn/20200322021522612.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

由于数据较为集中，这就给预测模型的预测带来比较大的困难，所以可以进行一次`log`运算改善一下分布，有利于后续的预测。

## 2️⃣.5️⃣ 数据特征相关性的分析🎎

### 2️⃣.5️⃣.1️⃣ `numric`特征的相关性分析

&emsp;&emsp;这里主要是为了解决我之前提出的疑问，「如何确定每个指标的重要性」，所以研究每个特征之间的相关性就显得尤为重要。在分析之前需要确定哪些特征是`numeric`型数据，哪些特征是`object`型数据。自动化的方法是
这样的：


```python
# num_feas = Train_data.select_dtypes(include=[np.number])
# obj_feas = Train_data.select_dtypes(include=[np.object])
```

但本题的数据集的label已经标好名称了，而且label是有限的，每个种类是可以理解的，所以还是需要人为标注，例如车型`bodyType`虽然是数值型数据，但其实我们知道它应该是`object`型数据。所以可以这样：



```python
num_feas = ['power', 'kilometer', 'v_0', 'v_1', 'v_2', 'v_3', 'v_4', 'v_5', 'v_6', 'v_7', 'v_8', 'v_9', 'v_10', 'v_11', 'v_12', 'v_13','v_14' ]

obj_feas = ['name', 'model', 'brand', 'bodyType', 'fuelType', 'gearbox', 'notRepairedDamage', 'regionCode',]
```

下面我们将`price`加入`num_feas`，并用`pandas`笼统地分析一下特征之间的相关性，并进行可视化。


```python
num_feas.append('price')
price_numeric = Train_data[num_feas]
correlation = price_numeric.corr()
print(correlation['price'].sort_values(ascending = False),'\n')
```

    price        1.000000
    v_12         0.692823
    v_8          0.685798
    v_0          0.628397
    power        0.219834
    v_5          0.164317
    v_2          0.085322
    v_6          0.068970
    v_1          0.060914
    v_14         0.035911
    v_13        -0.013993
    v_7         -0.053024
    v_4         -0.147085
    v_9         -0.206205
    v_10        -0.246175
    v_11        -0.275320
    kilometer   -0.440519
    v_3         -0.730946
    Name: price, dtype: float64 
    
    


```python
f , ax = plt.subplots(figsize = (8, 8))
plt.title('Correlation of Numeric Features with Price', y = 1, size = 16)
sns.heatmap(correlation, square = True, annot=True, cmap='RdPu', vmax = 0.8) # 参数annot为True时，为每个单元格写入数据值。如果数组具有与数据相同的形状，则使用它来注释热力图而不是原始数据。
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1c63234b400>



![相关度热力图](https://img-blog.csdnimg.cn/20200322021535689.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


作为一个色彩控，`cmap`的可选参数有Accent, Accent_r, Blues, Blues_r, BrBG, BrBG_r, BuGn, BuGn_r, BuPu, BuPu_r, CMRmap, CMRmap_r, Dark2, Dark2_r, GnBu, GnBu_r, Greens, Greens_r, Greys, Greys_r, OrRd, OrRd_r, Oranges, Oranges_r, PRGn, PRGn_r, Paired, Paired_r, Pastel1, Pastel1_r, Pastel2, Pastel2_r, PiYG, PiYG_r, PuBu, PuBuGn, PuBuGn_r, PuBu_r, PuOr, PuOr_r, PuRd, PuRd_r, Purples, Purples_r, RdBu, RdBu_r, RdGy, RdGy_r, RdPu, RdPu_r, RdYlBu, RdYlBu_r, RdYlGn, RdYlGn_r, Reds, Reds_r, Set1, Set1_r, Set2, Set2_r, Set3, Set3_r, Spectral, Spectral_r, Wistia, Wistia_r, YlGn, YlGnBu, YlGnBu_r, YlGn_r, YlOrBr, YlOrBr_r, YlOrRd, YlOrRd_r...其中末尾加r是颜色取反。

关于`seaborn`的`heatmap`可以看这里[seaborn.heatmap的初步学习](https://www.jianshu.com/p/e195a09a8ca9)

言归正传，从热度图中可以看出跟`price`相关性高的几个特征主要包括：`kilometer`,`v3`。与我们的现实经验还是比较吻合的，那个`v3`可能是发动机等汽车重要部件相关的某个参数。


- **峰度与偏度**

&emsp;&emsp;查看各个特征的偏度与峰度，以及数据的分布状况


```python
del price_numeric['price']
#  输出数据的峰度与偏度，这里pandas可以直接调用
for col in num_feas:
    print('{:15}'.format(col), 
          'Skewness: {:05.2f}'.format(Train_data[col].skew()) , 
          '   ' ,
          'Kurtosis: {:06.2f}'.format(Train_data[col].kurt())  
         )

f = pd.melt(Train_data, value_vars = num_feas) # 利用pandas的melt函数将测试集中的num_feas所对应的数据取出来
# FacetGrid是sns库中用来画网格图的函数，其中col_wrap用来控制一行显示图的个数，sharex或者sharey是否共享x,y轴，意味着每个子图是否有自己的横纵坐标。
g = sns.FacetGrid(f, col = "variable",  col_wrap = 6, sharex = False, sharey = False, hue = 'variable', palette = "GnBu_d") # palette的可选参数与上文的cmap类似
g = g.map(sns.distplot, "value")
```

    power           Skewness: 65.86     Kurtosis: 5733.45
    kilometer       Skewness: -1.53     Kurtosis: 001.14
    v_0             Skewness: -1.32     Kurtosis: 003.99
    v_1             Skewness: 00.36     Kurtosis: -01.75
    v_2             Skewness: 04.84     Kurtosis: 023.86
    v_3             Skewness: 00.11     Kurtosis: -00.42
    v_4             Skewness: 00.37     Kurtosis: -00.20
    v_5             Skewness: -4.74     Kurtosis: 022.93
    v_6             Skewness: 00.37     Kurtosis: -01.74
    v_7             Skewness: 05.13     Kurtosis: 025.85
    v_8             Skewness: 00.20     Kurtosis: -00.64
    v_9             Skewness: 00.42     Kurtosis: -00.32
    v_10            Skewness: 00.03     Kurtosis: -00.58
    v_11            Skewness: 03.03     Kurtosis: 012.57
    v_12            Skewness: 00.37     Kurtosis: 000.27
    v_13            Skewness: 00.27     Kurtosis: -00.44
    v_14            Skewness: -1.19     Kurtosis: 002.39
    price           Skewness: 03.35     Kurtosis: 019.00
    


![各特征之间的相关度图](https://img-blog.csdnimg.cn/20200322021549954.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


**各个数值特征之间的相关性**


```python
sns.set()
columns = num_feas
sns.pairplot(Train_data[columns], size = 2 , kind = 'scatter', diag_kind ='kde', palette = "PuBu")
plt.show()
```

    D:\Software\Anaconda\lib\site-packages\seaborn\axisgrid.py:2065: UserWarning: The `size` parameter has been renamed to `height`; pleaes update your code.
      warnings.warn(msg, UserWarning)
    


![价格与各特征之间的相关度图](https://img-blog.csdnimg.cn/20200322021608718.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


可以看出成闭团状的相关图还是很多的，说明相应特征的相关度比较大。

- **`price`与其他变量相关性可视化**

&emsp;&emsp;这里用匿名变量`v0`~`v13`进行分析，使用`seaborn`的`regplot`函数进行相关度回归分析。


```python
Y_train = Train_data['price']
fig, ((ax1, ax2), (ax3, ax4), (ax5, ax6), (ax7, ax8), (ax9, ax10),(ax11, ax12),(ax13,ax14)) = plt.subplots(nrows = 7, ncols=2, figsize=(24, 20))
ax = [ax1, ax2, ax3, ax4, ax5, ax6, ax7, ax8, ax9, ax10, ax11, ax12, ax13, ax14]
for num in range(0,14):
    sns.regplot(x = 'v_' + str(num), y = 'price', data = pd.concat([Y_train, Train_data['v_' + str(num)]],axis = 1), scatter = True, fit_reg = True, ax = ax[num])
```


![价格与其他特征之间的回归分析](https://img-blog.csdnimg.cn/2020032202162299.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


可以看出大部分匿名变量的分布还是比较集中的，当然线性回归的性能确实太弱了。

至于类别特征的回归分析，本身可以参考的意义不大，就暂时省略了。

### 2️⃣.5️⃣.2️⃣ `pandas_profiling`生成数据报告📕
&emsp;&emsp;用`pandas_profiling`生成一个较为全面的可视化和数据报告(较为简单、方便)最终打开html文件即可


```python
import pandas_profiling
file = pandas_profiling.ProfileReport(Train_data)
pfr.to_file("pandas_analysis.html")
```

**长这个样子：**
![profuling1](https://img-blog.csdnimg.cn/20200322022858409.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


![profuling2](https://img-blog.csdnimg.cn/2020032202291526.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

![profuling3](https://img-blog.csdnimg.cn/20200322022922975.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)
具体文件在这里[我的天池](https://tianchi.aliyun.com/mas-notebook/proxy/filemanager/files/example.html)




# 3️⃣ 结语✏️

&emsp;&emsp;至此赛题的赛题理解以及数据分析工作告一段落，总结一下：

- 运用`describe()`和`info()`进行数据基本统计量的描述
- 运用`missingno`库和`pandas.isnull()`来对异常值和缺失值进行可视化察觉以及处理 
- 熟悉偏度（Skewness）与峰度（Kurtosis）的概念，可以用`skeu()`和`kurt()`计算其值
- 在确定预测值的范围与分布后，可以做一些取对数或者开根号的方式缓解数据集中的问题
- 相关性分析时
  - 用`corr()`计算各特征的相关系数
  - 用`seaborn`的`heatmap`画出相关系数的热力图
  - 用`seaborn`的`FacetGrid`和`pairplot`可以分别画出各特征内部之间以及预测值与其他特征之间的数据分布图
  - 也可以用`seaborn`的`regplot`来对预测值与各特征的关系进行回归分析

开始下一步特征工程。




