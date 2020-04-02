# 天池的一些竞赛与想法👩‍💻
---
<div align="center">

[![GitHub Issues](https://img.shields.io/github/issues/ExcaliburEX/Tianchi-Story)](https://github.com/ExcaliburEX/Tianchi-Story/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/ycraaron/LuotuoCoin.svg)](https://github.com/ycraaron/LuotuoCoin/pulls)
![forks](https://img.shields.io/github/forks/ExcaliburEX/Tianchi-Story)
![stars](	https://img.shields.io/github/stars/ExcaliburEX/Tianchi-Story)
![repo size](https://img.shields.io/github/repo-size/ExcaliburEX/Tianchi-Story)
[![HitCount](http://hits.dwyl.com/ExcaliburEX/Tianchi-Story.svg)](http://hits.dwyl.com/ExcaliburEX/Tianchi-Story)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fimg.shields.io%2Ftwitter%2Furl%3Fstyle%3Dsocial%26url%3Dhttps%253A%252F%252Ftwitter.com%252FExcaliburjp)
![](https://img.shields.io/badge/build-passing-green)
![](https://img.shields.io/badge/version-up--to--date-blue)
![](https://img.shields.io/badge/coverage-100%25-orange)
![](https://img.shields.io/badge/chat-666%20online-yellowgreen)
![](https://img.shields.io/badge/stars-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-brightgreen)
[![Follow me on Twitter](https://img.shields.io/static/v1.svg?label=Follow%20%40Excaliburjp&message=🤙&color=red&logo=twitter&style=social)](https://twitter.com/Excaliburjp) 
![Copyright](https://img.shields.io/static/v1.svg?label=My%20cool%20project%20©️%20&message=%202020%20Name&labelColor=informational&color=033450) 
[![Add to Chrome](https://img.shields.io/static/v1.svg?label=Add%20to&message=Chrome%20🧘)](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd) 
</div>

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
    - [2️⃣.6️⃣ 结语✏️](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A3-%E7%BB%93%E8%AF%AD%EF%B8%8F)
  - [3️⃣&emsp; 特征工程🃏](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A3-%E7%89%B9%E5%BE%81%E5%B7%A5%E7%A8%8B)
    - [3️⃣.1️⃣&emsp; 前言](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E5%89%8D%E8%A8%80)
      - [3️⃣.1️⃣.1️⃣&emsp; 赛题重述](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E8%B5%9B%E9%A2%98%E9%87%8D%E8%BF%B0)
      - [3️⃣.1️⃣.2️⃣&emsp; 数据集概述](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A6%82%E8%BF%B0)
    - [3️⃣.2️⃣&emsp; 异常缺失值删除](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E5%BC%82%E5%B8%B8%E7%BC%BA%E5%A4%B1%E5%80%BC%E5%88%A0%E9%99%A4)
      - [3️⃣.2️⃣.1️⃣&emsp; 导入库与数据](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E5%AF%BC%E5%85%A5%E5%BA%93%E4%B8%8E%E6%95%B0%E6%8D%AE)
      - [3️⃣.2️⃣.2️⃣&emsp; 异常值删除](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E5%BC%82%E5%B8%B8%E5%80%BC%E5%88%A0%E9%99%A4)
    - [3️⃣.3️⃣&emsp; 树模型的特征构造](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A3-%E6%A0%91%E6%A8%A1%E5%9E%8B%E7%9A%84%E7%89%B9%E5%BE%81%E6%9E%84%E9%80%A0)
      - [3️⃣.3️⃣.1️⃣&emsp; 时间特征构造](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E6%97%B6%E9%97%B4%E7%89%B9%E5%BE%81%E6%9E%84%E9%80%A0)
      - [3️⃣.3️⃣.2️⃣&emsp; 城市信息特征提取](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E5%9F%8E%E5%B8%82%E4%BF%A1%E6%81%AF%E7%89%B9%E5%BE%81%E6%8F%90%E5%8F%96)
      - [3️⃣.3️⃣.3️⃣&emsp; 品牌特征提取](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A3-%E5%93%81%E7%89%8C%E7%89%B9%E5%BE%81%E6%8F%90%E5%8F%96)
    - [3️⃣.4️⃣&emsp; 树模型的数据分桶](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A34%EF%B8%8F%E2%83%A3-%E6%A0%91%E6%A8%A1%E5%9E%8B%E7%9A%84%E6%95%B0%E6%8D%AE%E5%88%86%E6%A1%B6)
    - [3️⃣.5️⃣&emsp; LR与NN模型的特征构造](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A3-lr%E4%B8%8Enn%E6%A8%A1%E5%9E%8B%E7%9A%84%E7%89%B9%E5%BE%81%E6%9E%84%E9%80%A0)
      - [3️⃣.5️⃣.1️⃣&emsp; log与归一化](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-log%E4%B8%8E%E5%BD%92%E4%B8%80%E5%8C%96)
      - [3️⃣.5️⃣.2️⃣&emsp; OneEncoder编码](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A35%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-oneencoder%E7%BC%96%E7%A0%81)
    - [3️⃣.6️⃣&emsp; 特征选择](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A36%EF%B8%8F%E2%83%A3-%E7%89%B9%E5%BE%81%E9%80%89%E6%8B%A9)
      - [3️⃣.6️⃣.1️⃣&emsp; 过滤式(filter)](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A36%EF%B8%8F%E2%83%A31%EF%B8%8F%E2%83%A3-%E8%BF%87%E6%BB%A4%E5%BC%8Ffilter)
      - [3️⃣.6️⃣.2️⃣&emsp; 包裹式(wrapper)](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A36%EF%B8%8F%E2%83%A32%EF%B8%8F%E2%83%A3-%E5%8C%85%E8%A3%B9%E5%BC%8Fwrapper)
      - [3️⃣.6️⃣.3️⃣&emsp; 嵌入式(embedding)](https://github.com/ExcaliburEX/Tianchi-Story#3%EF%B8%8F%E2%83%A36%EF%B8%8F%E2%83%A33%EF%B8%8F%E2%83%A3-%E5%B5%8C%E5%85%A5%E5%BC%8Fembedding)
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
        <p align = "center">
        <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24h_%7B%5Ctheta%7D%28x%29%3D%5Ctheta%5E%7BT%7D%20X%3D%5Ctheta_%7B0%7D&plus;%5Ctheta_%7B1%7D%20x_%7B1%7D&plus;%5Ctheta_%7B2%7D%20x_%7B2%7D&plus;%5Cldots&plus;%5Ctheta_%7B31%7D%20x_%7B31%7D%24%24"  />
        </p>
        
        它的带有正则化的代价函数是这样的：

        <p align = "center">
        <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24J%28%5Ctheta%29%3D%5Cfrac%7B1%7D%7B62%7D%20%5Csum_%7Bi%3D1%7D%5E%7B31%7D%5Cleft%5B%5Cleft%28%5Cleft%28h_%7B%5Ctheta%7D%5Cleft%28x%5E%7B%28i%29%7D%5Cright%29-y%5E%7B%28i%29%7D%5Cright%29%5E%7B2%7D&plus;%5Clambda%20%5Csum_%7Bj%3D1%7D%5E%7B31%7D%20%5Ctheta_%7Bj%7D%5E%7B2%7D%5Cright%29%5Cright%5D%24%24"  />
        </p>
        
        ---
        
## 1️⃣.3️⃣ 预测结果评价指标⚒️
---
&emsp;&emsp;赛题的预测评估指标为MAE(Mean Absolute Error)

<p align = "center">
<img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24M%20A%20E%3D%5Cfrac%7B%5Csum%5Climits_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%7Cy_%7Bi%7D-%5Chat%7By%7D_%7Bi%7D%5Cright%7C%7D%7Bn%7D%24%24"  />
</p>

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
    <p align = "center">
    <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24%5Cgamma_%7B1%7D%3D%5Cmathrm%7BE%7D%5Cleft%5B%5Cleft%28%5Cfrac%7BX-%5Cmu%7D%7B%5Csigma%7D%5Cright%29%5E%7B3%7D%5Cright%5D%3D%5Cfrac%7B%5Cmu_%7B3%7D%7D%7B%5Csigma%5E%7B3%7D%7D%3D%5Cfrac%7B%5Cmathrm%7BE%7D%5Cleft%5B%28X-%5Cmu%29%5E%7B3%7D%5Cright%5D%7D%7B%5Cleft%28%5Cmathrm%7BE%7D%5Cleft%5B%28X-%5Cmu%29%5E%7B2%7D%5Cright%5D%5Cright%29%5E%7B3%20/%202%7D%7D%3D%5Cfrac%7B%5Ckappa_%7B3%7D%7D%7B%5Ckappa_%7B2%7D%5E%7B3%20/%202%7D%7D%24%24"  />
    </p>

    
- **峰度（Kurtosis）**
偏度是描述某变量所有取值分布形态陡缓程度的统计量，简单来说就是数据分布顶的尖锐程度。
    - Kurtosis = 0 与正态分布的陡缓程度相同。
    - Kurtosis > 0 比正态分布的高峰更加陡峭——尖顶峰。
    - urtosis<0 比正态分布的高峰来得平台——平顶峰。
    - 计算公式：
    <p align = "center">
    <img style="display:block; margin:0 auto;" src = "https://latex.codecogs.com/svg.latex?%24%24b_%7B1%7D%3D%5Cfrac%7Bm_%7B3%7D%7D%7Bs%5E%7B3%7D%7D%3D%5Cfrac%7B%5Cfrac%7B1%7D%7Bn%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B3%7D%7D%7B%5Csqrt%7B%5Cfrac%7B1%7D%7Bn-1%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B2%7D%7D%7D%3D%5Cfrac%7B%5Cfrac%7B1%7D%7Bn%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B3%7D%7D%7B%5Cleft%5B%5Cfrac%7B1%7D%7Bn-1%7D%20%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%5Cleft%28x_%7Bi%7D-%5Cbar%7Bx%7D%5Cright%29%5E%7B2%7D%5Cright%5D%5E%7B3%20/%202%7D%7D%24%24"  />
    </p>


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




# 2️⃣.6️⃣ 结语✏️

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






# 3️⃣&emsp; 特征工程🃏

&emsp;&emsp;特征工程，是指用一系列工程化的方式从原始数据中筛选出更好的数据特征，以提升模型的训练效果。业内有一句广为流传的话是：数据和特征决定了机器学习的上限，而模型和算法是在逼近这个上限而已。由此可见，好的数据和特征是模型和算法发挥更大的作用的前提。特征工程通常包括数据预处理、特征选择、降维等环节。如下图所示：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004507865.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)
## 3️⃣.1️⃣&emsp; 前言

&emsp;&emsp;我们经常在处理数据时，会面临以下问题：
- 收集的数据格式不对（如 `SQL` 数据库、`JSON`、`CSV` 等）
- 缺失值和异常值
- 标准化
- 减少数据集中存在的固有噪声（部分存储数据可能已损坏）
- 数据集中的某些功能可能无法收集任何信息以供分析

而减少统计分析期间要使用的特征的数量可能会带来一些好处，例如：
- 提高精度
- 降低过拟合风险
- 加快训练速度
- 改进数据可视化
- 增加我们模型的可解释性

事实上，统计上证明，当执行机器学习任务时，存在针对每个特定任务应该使用的**最佳数量的特征**（图 1）。如果添加的特征比必要的特征**多**，那么我们的模型性能将**下降**（因为添加了噪声）。真正的挑战是找出哪些特征是**最佳的使用特征**（这实际上取决于我们提供的数据量和我们正在努力实现的任务的复杂性）。这就是特征选择技术能够帮到我们的地方！

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402005242590.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

### 3️⃣.1️⃣.1️⃣&emsp; 赛题重述
    
&emsp;&emsp;这是一道来自于天池的新手练习题目，用`数据分析`、`机器学习`等手段进行 [二手车售卖价格预测](https://tianchi.aliyun.com/competition/entrance/231784/information) 的回归问题。赛题本身的思路清晰明了，即对给定的数据集进行分析探讨，然后设计模型运用数据进行训练，测试模型，最终给出选手的预测结果。前面我们已经进行过EDA分析在这里[天池_二手车价格预测_Task1-2_赛题理解与数据分析
](https://blog.csdn.net/ExcaliburUlimited/article/details/105021630)

### 3️⃣.1️⃣.2️⃣&emsp; 数据集概述
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

## 3️⃣.2️⃣&emsp; 异常缺失值删除
### 3️⃣.2️⃣.1️⃣&emsp; 导入库与数据


```python
import pandas as pd
import numpy as np
import matplotlib
import matplotlib.pyplot as plt
import seaborn as sns
from operator import itemgetter

%matplotlib inline
```


```python
train = pd.read_csv('used_car_train_20200313.csv', sep=' ')
test = pd.read_csv('used_car_testA_20200313.csv', sep=' ')
print(train.shape)
print(test.shape)
```

    (150000, 31)
    (50000, 30)
    


```python
train.head()
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
      <td>0</td>
      <td>0</td>
      <td>736</td>
      <td>20040402</td>
      <td>30.0</td>
      <td>6</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>60</td>
      <td>12.5</td>
      <td>...</td>
      <td>0.235676</td>
      <td>0.101988</td>
      <td>0.129549</td>
      <td>0.022816</td>
      <td>0.097462</td>
      <td>-2.881803</td>
      <td>2.804097</td>
      <td>-2.420821</td>
      <td>0.795292</td>
      <td>0.914762</td>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>2262</td>
      <td>20030301</td>
      <td>40.0</td>
      <td>1</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.264777</td>
      <td>0.121004</td>
      <td>0.135731</td>
      <td>0.026597</td>
      <td>0.020582</td>
      <td>-4.900482</td>
      <td>2.096338</td>
      <td>-1.030483</td>
      <td>-1.722674</td>
      <td>0.245522</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
      <td>14874</td>
      <td>20040403</td>
      <td>115.0</td>
      <td>15</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>163</td>
      <td>12.5</td>
      <td>...</td>
      <td>0.251410</td>
      <td>0.114912</td>
      <td>0.165147</td>
      <td>0.062173</td>
      <td>0.027075</td>
      <td>-4.846749</td>
      <td>1.803559</td>
      <td>1.565330</td>
      <td>-0.832687</td>
      <td>-0.229963</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>71865</td>
      <td>19960908</td>
      <td>109.0</td>
      <td>10</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>193</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.274293</td>
      <td>0.110300</td>
      <td>0.121964</td>
      <td>0.033395</td>
      <td>0.000000</td>
      <td>-4.509599</td>
      <td>1.285940</td>
      <td>-0.501868</td>
      <td>-2.438353</td>
      <td>-0.478699</td>
    </tr>
    <tr>
      <td>4</td>
      <td>4</td>
      <td>111080</td>
      <td>20120103</td>
      <td>110.0</td>
      <td>5</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>68</td>
      <td>5.0</td>
      <td>...</td>
      <td>0.228036</td>
      <td>0.073205</td>
      <td>0.091880</td>
      <td>0.078819</td>
      <td>0.121534</td>
      <td>-1.896240</td>
      <td>0.910783</td>
      <td>0.931110</td>
      <td>2.834518</td>
      <td>1.923482</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 31 columns</p>
</div>




```python
train.columns
```




    Index(['SaleID', 'name', 'regDate', 'model', 'brand', 'bodyType', 'fuelType',
           'gearbox', 'power', 'kilometer', 'notRepairedDamage', 'regionCode',
           'seller', 'offerType', 'creatDate', 'price', 'v_0', 'v_1', 'v_2', 'v_3',
           'v_4', 'v_5', 'v_6', 'v_7', 'v_8', 'v_9', 'v_10', 'v_11', 'v_12',
           'v_13', 'v_14'],
          dtype='object')



### 3️⃣.2️⃣.2️⃣&emsp; 异常值删除
&emsp;&emsp;这里可以将箱型图中的超过上下限的那些值作为异常值删除。如下图所示，箱型图中间是一个箱体，也就是粉红色部分，箱体左边，中间，右边分别有一条线，左边是下分位数(Q1)，右边是上四分位数(Q3)，中间是中位数(Median)，上下四分位数之差是四分位距IQR（Interquartile Range，用Q1-1.5*IQR得到下边缘（最小值），Q3+1.5*IQR得到上边缘（最大值）。在上边缘之外的数据就是极大异常值，在下边缘之外的数据就是极小异常值。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004441943.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

搞清楚原理那我们就构造一个实现上述功能的函数吧！


```python
def drop_outliers(data, col_name, scale = 1.5):
    """
    用于清洗异常值，默认用 box_plot（scale=1.5）进行清洗
    :param data: 接收 pandas 数据格式
    :param col_name: pandas 列名
    :param scale: 尺度
    :return:
    """
    data_n = data.copy()
    data_series = data_n[col_name]
    
    IQR = scale * (data_series.quantile(0.75) - data_series.quantile(0.25)) # quantile是pd内置的求四分位的函数
    val_low = data_series.quantile(0.25) - IQR # 下边缘
    val_up = data_series.quantile(0.75) + IQR # 上边缘
    rule_low = (data_series < val_low) # 下边缘的极小异常值的下标列表
    rule_up = (data_series > val_up)   # 上边缘的极大异常值的下标列表
    
    index = np.arange(data_series.shape[0])[rule_low | rule_up] # | 运算就是说只要rule_low和rule_up中只要有一个值为True，就把这个下标取出来
    print(index)
    print("Delete number is: {}".format(len(index)))
    
    data_n = data_n.drop(index) # 删除index对应下标的元素
    data_n.reset_index(drop=True, inplace=True) #下文有介绍
    print("Now column number is: {}".format(data_n.shape[0]))
    
    index_low = np.arange(data_series.shape[0])[rule_low] # 下边缘的异常数据的描述统计量
    outliers = data_series.iloc[index_low]
    print("Description of data less than the lower bound is:")
    print(pd.Series(outliers).describe())
    
    index_up = np.arange(data_series.shape[0])[rule_up] # 上边缘的异常数据的描述统计量
    outliers = data_series.iloc[index_up]
    print("Description of data larger than the upper bound is:")
    print(pd.Series(outliers).describe())
    
    fig, ax = plt.subplots(1, 2, figsize = (10, 7))
    sns.boxplot(y = data[col_name], data = data, palette = "Set1", ax = ax[0])
    sns.boxplot(y = data_n[col_name], data = data_n, palette = "Set1", ax = ax[1])
    return data_n
```

这里`reset_index`可以还原索引，重新变为默认的整型索引 

`DataFrame.reset_index(level=None, drop=False, inplace=False, col_level=0, col_fill=”)`

- `level`：`int`、`str`、`tuple`或`list`，默认无，仅从索引中删除给定级别。默认情况下移除所有级别。控制了具体要还原的那个等级的索引
- `drop`：`drop`为`False`则索引列会被还原为普通列，否则会丢失
- `inplace`：默认为`False`，适当修改`DataFrame`(不要创建新对象)
- `col_level`：`int`或`str`，默认值为0，如果列有多个级别，则确定将标签插入到哪个级别。默认情况下，它将插入到第一级。
- `col_fill`：对象，默认‘’，如果列有多个级别，则确定其他级别的命名方式。如果没有，则重复索引名


```python
drop_outliers(train, 'power', scale=1.5)
```

    [    33     77    104 ... 149967 149981 149984]
    Delete number is: 4878
    Now column number is: 145122
    Description of data less than the lower bound is:
    count    0.0
    mean     NaN
    std      NaN
    min      NaN
    25%      NaN
    50%      NaN
    75%      NaN
    max      NaN
    Name: power, dtype: float64
    Description of data larger than the upper bound is:
    count     4878.000000
    mean       410.132021
    std        884.219933
    min        264.000000
    25%        286.000000
    50%        306.000000
    75%        349.000000
    max      19312.000000
    Name: power, dtype: float64
    




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
      <td>0</td>
      <td>0</td>
      <td>736</td>
      <td>20040402</td>
      <td>30.0</td>
      <td>6</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>60</td>
      <td>12.5</td>
      <td>...</td>
      <td>0.235676</td>
      <td>0.101988</td>
      <td>0.129549</td>
      <td>0.022816</td>
      <td>0.097462</td>
      <td>-2.881803</td>
      <td>2.804097</td>
      <td>-2.420821</td>
      <td>0.795292</td>
      <td>0.914762</td>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>2262</td>
      <td>20030301</td>
      <td>40.0</td>
      <td>1</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.264777</td>
      <td>0.121004</td>
      <td>0.135731</td>
      <td>0.026597</td>
      <td>0.020582</td>
      <td>-4.900482</td>
      <td>2.096338</td>
      <td>-1.030483</td>
      <td>-1.722674</td>
      <td>0.245522</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
      <td>14874</td>
      <td>20040403</td>
      <td>115.0</td>
      <td>15</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>163</td>
      <td>12.5</td>
      <td>...</td>
      <td>0.251410</td>
      <td>0.114912</td>
      <td>0.165147</td>
      <td>0.062173</td>
      <td>0.027075</td>
      <td>-4.846749</td>
      <td>1.803559</td>
      <td>1.565330</td>
      <td>-0.832687</td>
      <td>-0.229963</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
      <td>71865</td>
      <td>19960908</td>
      <td>109.0</td>
      <td>10</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>193</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.274293</td>
      <td>0.110300</td>
      <td>0.121964</td>
      <td>0.033395</td>
      <td>0.000000</td>
      <td>-4.509599</td>
      <td>1.285940</td>
      <td>-0.501868</td>
      <td>-2.438353</td>
      <td>-0.478699</td>
    </tr>
    <tr>
      <td>4</td>
      <td>4</td>
      <td>111080</td>
      <td>20120103</td>
      <td>110.0</td>
      <td>5</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>68</td>
      <td>5.0</td>
      <td>...</td>
      <td>0.228036</td>
      <td>0.073205</td>
      <td>0.091880</td>
      <td>0.078819</td>
      <td>0.121534</td>
      <td>-1.896240</td>
      <td>0.910783</td>
      <td>0.931110</td>
      <td>2.834518</td>
      <td>1.923482</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>145117</td>
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
      <td>145118</td>
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
      <td>145119</td>
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
      <td>145120</td>
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
      <td>145121</td>
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
<p>145122 rows × 31 columns</p>
</div>



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004634297.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


从这张删除异常值前后的箱型图对比可以看出，剔除异常值后，数据的分布就很均匀了。

下面我们就批量对所有的特征进行一次异常数据删除：


```python
def Bach_drop_outliers(data,scale=1.5):
    dataNew = data.copy()

    for fea in data.columns:
        try:
            IQR = scale * (dataNew[fea].quantile(0.75) - dataNew[fea].quantile(0.25)) # quantile是pd内置的求四分位的函数
        except:
            continue
        val_low = dataNew[fea].quantile(0.25) - IQR # 下边缘
        val_up = dataNew[fea].quantile(0.75) + IQR # 上边缘
        rule_low = (dataNew[fea] < val_low) # 下边缘的极小异常值的下标列表
        rule_up = (dataNew[fea] > val_up)   # 上边缘的极大异常值的下标列表
        
        index = np.arange(dataNew[fea].shape[0])[rule_low | rule_up] # | 运算就是说只要rule_low和rule_up中只要有一个值为True，就把这个下标取出来
        print("feature %s deleted number is %d"%(fea, len(index)))
        
        dataNew = dataNew.drop(index)# 删除index对应下标的元素
        dataNew.reset_index(drop=True, inplace=True)
    fig, ax = plt.subplots(5, 6, figsize = (20, 15))
    x = 0
    y = 0
    for fea in dataNew.columns:
        try:
            sns.boxplot(y = dataNew[fea], data =dataNew, palette = "Set2", ax = ax[x][y])
            y+=1
            if y == 6:
                y = 0
                x += 1
        except:
            print(fea)
            y+=1
            if y == 6:
                y = 0
                x += 1
            continue
    return dataNew

train = Bach_drop_outliers(train)
```

    feature SaleID deleted number is 0
    feature name deleted number is 0
    feature regDate deleted number is 0
    feature model deleted number is 9720
    feature brand deleted number is 4032
    feature bodyType deleted number is 5458
    feature fuelType deleted number is 333
    feature gearbox deleted number is 26829
    feature power deleted number is 1506
    feature kilometer deleted number is 15306
    feature regionCode deleted number is 4
    feature seller deleted number is 1
    feature offerType deleted number is 0
    feature creatDate deleted number is 13989
    feature price deleted number is 4527
    feature v_0 deleted number is 2558
    feature v_1 deleted number is 0
    feature v_2 deleted number is 487
    feature v_3 deleted number is 173
    feature v_4 deleted number is 61
    feature v_5 deleted number is 0
    feature v_6 deleted number is 0
    feature v_7 deleted number is 64
    feature v_8 deleted number is 0
    feature v_9 deleted number is 24
    feature v_10 deleted number is 0
    feature v_11 deleted number is 0
    feature v_12 deleted number is 4
    feature v_13 deleted number is 0
    feature v_14 deleted number is 1944
    notRepairedDamage
    v_14
    


![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004549377.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


可以看出，经过箱型图异常值删除后，新数据的箱型图的数据几乎没有异常值了，甚至有些箱型图的数据是一条直线，当然那是因为数据本身就是种类非0即1。

## 3️⃣.3️⃣&emsp; 树模型的特征构造
&emsp;&emsp;训练集和测试集放在一起，方便构造特征


```python
train['train'] = 1
test['train'] = 0
data = pd.concat([train, test], ignore_index=True, sort=False)
data
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
      <th>v_6</th>
      <th>v_7</th>
      <th>v_8</th>
      <th>v_9</th>
      <th>v_10</th>
      <th>v_11</th>
      <th>v_12</th>
      <th>v_13</th>
      <th>v_14</th>
      <th>train</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>2262</td>
      <td>20030301</td>
      <td>40.0</td>
      <td>1</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.121004</td>
      <td>0.135731</td>
      <td>0.026597</td>
      <td>0.020582</td>
      <td>-4.900482</td>
      <td>2.096338</td>
      <td>-1.030483</td>
      <td>-1.722674</td>
      <td>0.245522</td>
      <td>1</td>
    </tr>
    <tr>
      <td>1</td>
      <td>5</td>
      <td>137642</td>
      <td>20090602</td>
      <td>24.0</td>
      <td>10</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>109</td>
      <td>10.0</td>
      <td>...</td>
      <td>0.000518</td>
      <td>0.119838</td>
      <td>0.090922</td>
      <td>0.048769</td>
      <td>1.885526</td>
      <td>-2.721943</td>
      <td>2.457660</td>
      <td>-0.286973</td>
      <td>0.206573</td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>7</td>
      <td>165346</td>
      <td>19990706</td>
      <td>26.0</td>
      <td>14</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>101</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.122943</td>
      <td>0.039839</td>
      <td>0.082413</td>
      <td>3.693829</td>
      <td>-0.245014</td>
      <td>-2.192810</td>
      <td>0.236728</td>
      <td>0.195567</td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>10</td>
      <td>18961</td>
      <td>20050811</td>
      <td>19.0</td>
      <td>9</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>101</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.105385</td>
      <td>0.077271</td>
      <td>0.042445</td>
      <td>0.060794</td>
      <td>-4.206000</td>
      <td>1.060391</td>
      <td>-0.647515</td>
      <td>-0.191194</td>
      <td>0.349187</td>
      <td>1</td>
    </tr>
    <tr>
      <td>4</td>
      <td>13</td>
      <td>8129</td>
      <td>20041110</td>
      <td>65.0</td>
      <td>1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>150</td>
      <td>15.0</td>
      <td>...</td>
      <td>0.106950</td>
      <td>0.134945</td>
      <td>0.050364</td>
      <td>0.051359</td>
      <td>-4.614692</td>
      <td>0.821889</td>
      <td>0.753490</td>
      <td>-0.886425</td>
      <td>-0.341562</td>
      <td>1</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>112975</td>
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
      <td>0.130044</td>
      <td>0.049833</td>
      <td>0.028807</td>
      <td>0.004616</td>
      <td>-5.978511</td>
      <td>1.303174</td>
      <td>-1.207191</td>
      <td>-1.981240</td>
      <td>-0.357695</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112976</td>
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
      <td>0.108095</td>
      <td>0.066039</td>
      <td>0.025468</td>
      <td>0.025971</td>
      <td>-3.913825</td>
      <td>1.759524</td>
      <td>-2.075658</td>
      <td>-1.154847</td>
      <td>0.169073</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112977</td>
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
      <td>0.105724</td>
      <td>0.117652</td>
      <td>0.057479</td>
      <td>0.015669</td>
      <td>-4.639065</td>
      <td>0.654713</td>
      <td>1.137756</td>
      <td>-1.390531</td>
      <td>0.254420</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112978</td>
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
      <td>0.000490</td>
      <td>0.137366</td>
      <td>0.086216</td>
      <td>0.051383</td>
      <td>1.833504</td>
      <td>-2.828687</td>
      <td>2.465630</td>
      <td>-0.911682</td>
      <td>-2.057353</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112979</td>
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
      <td>0.000300</td>
      <td>0.103534</td>
      <td>0.080625</td>
      <td>0.124264</td>
      <td>2.914571</td>
      <td>-1.135270</td>
      <td>0.547628</td>
      <td>2.094057</td>
      <td>-1.552150</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>112980 rows × 32 columns</p>
</div>



### 3️⃣.3️⃣.1️⃣&emsp; 时间特征构造
- 使用时间：`data['creatDate']` - `data['regDate']`，反应汽车使用时间，一般来说价格与使用时间成反比
- 不过要注意，数据里有时间出错的格式，所以我们需要 errors='coerce'


```python
data['used_time'] = (pd.to_datetime(data['creatDate'], format='%Y%m%d', errors='coerce') - 
                            pd.to_datetime(data['regDate'], format='%Y%m%d', errors='coerce')).dt.days
data['used_time']
```




    0         4757.0
    1         2482.0
    2         6108.0
    3         3874.0
    4         4154.0
               ...  
    112975    7261.0
    112976    6014.0
    112977    4345.0
    112978       NaN
    112979    4151.0
    Name: used_time, Length: 112980, dtype: float64



- 看一下空数据，有 7.6k 个样本的时间是有问题的，我们可以选择删除，也可以选择放着。
- 但是这里不建议删除，因为删除缺失数据占总样本量过大，3.8%
- 我们可以先放着，因为如果我们 XGBoost 之类的决策树，其本身就能处理缺失值，所以可以不用管；


```python
data['used_time'].isnull().sum()
```




    8591




```python
data.isnull().sum().sum()
```




    70585



### 3️⃣.3️⃣.2️⃣&emsp; 城市信息特征提取
- 从邮编中提取城市信息，因为是德国的数据，所以参考德国的邮编，相当于加入了先验知识


```python
data['city'] = data['regionCode'].apply(lambda x : str(x)[:-3])
data['city']
```




    0         4
    1         3
    2         4
    3         1
    4         3
             ..
    112975    3
    112976    1
    112977    3
    112978    1
    112979    3
    Name: city, Length: 112980, dtype: object



### 3️⃣.3️⃣.3️⃣&emsp; 品牌特征提取
&emsp;&emsp;计算某品牌的销售统计量，这里要以 train 的数据计算统计量。


```python
train_gb = train.groupby("brand")
all_info = {}
for kind, kind_data in train_gb:
    info = {}
    kind_data = kind_data[kind_data['price'] > 0] # kind_data['price'] > 0 返回的是下标再取一次列表就得到了数据
    info['brand_amount'] = len(kind_data)
    info['brand_price_max'] = kind_data.price.max()
    info['brand_price_median'] = kind_data.price.median()
    info['brand_price_min'] = kind_data.price.min()
    info['brand_price_sum'] = kind_data.price.sum()
    info['brand_price_std'] = kind_data.price.std()
    info['brand_price_average'] = round(kind_data.price.sum() / (len(kind_data) + 1), 2)
    all_info[kind] = info
brand_fe = pd.DataFrame(all_info).T.reset_index().rename(columns={"index": "brand"})
data = data.merge(brand_fe, how='left', on='brand')
data
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
      <th>train</th>
      <th>used_time</th>
      <th>city</th>
      <th>brand_amount</th>
      <th>brand_price_max</th>
      <th>brand_price_median</th>
      <th>brand_price_min</th>
      <th>brand_price_sum</th>
      <th>brand_price_std</th>
      <th>brand_price_average</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>2262</td>
      <td>20030301</td>
      <td>40.0</td>
      <td>1</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>15.0</td>
      <td>...</td>
      <td>1</td>
      <td>4757.0</td>
      <td>4</td>
      <td>4940.0</td>
      <td>9500.0</td>
      <td>2999.0</td>
      <td>149.0</td>
      <td>17934852.0</td>
      <td>2537.956443</td>
      <td>3629.80</td>
    </tr>
    <tr>
      <td>1</td>
      <td>5</td>
      <td>137642</td>
      <td>20090602</td>
      <td>24.0</td>
      <td>10</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>109</td>
      <td>10.0</td>
      <td>...</td>
      <td>1</td>
      <td>2482.0</td>
      <td>3</td>
      <td>3557.0</td>
      <td>9500.0</td>
      <td>2490.0</td>
      <td>200.0</td>
      <td>10936962.0</td>
      <td>2180.881827</td>
      <td>3073.91</td>
    </tr>
    <tr>
      <td>2</td>
      <td>7</td>
      <td>165346</td>
      <td>19990706</td>
      <td>26.0</td>
      <td>14</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>101</td>
      <td>15.0</td>
      <td>...</td>
      <td>1</td>
      <td>6108.0</td>
      <td>4</td>
      <td>8784.0</td>
      <td>9500.0</td>
      <td>1350.0</td>
      <td>13.0</td>
      <td>17445064.0</td>
      <td>1797.704405</td>
      <td>1985.78</td>
    </tr>
    <tr>
      <td>3</td>
      <td>10</td>
      <td>18961</td>
      <td>20050811</td>
      <td>19.0</td>
      <td>9</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>101</td>
      <td>15.0</td>
      <td>...</td>
      <td>1</td>
      <td>3874.0</td>
      <td>1</td>
      <td>4487.0</td>
      <td>9500.0</td>
      <td>1250.0</td>
      <td>55.0</td>
      <td>7867901.0</td>
      <td>1556.621159</td>
      <td>1753.10</td>
    </tr>
    <tr>
      <td>4</td>
      <td>13</td>
      <td>8129</td>
      <td>20041110</td>
      <td>65.0</td>
      <td>1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>150</td>
      <td>15.0</td>
      <td>...</td>
      <td>1</td>
      <td>4154.0</td>
      <td>3</td>
      <td>4940.0</td>
      <td>9500.0</td>
      <td>2999.0</td>
      <td>149.0</td>
      <td>17934852.0</td>
      <td>2537.956443</td>
      <td>3629.80</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>112975</td>
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
      <td>0</td>
      <td>7261.0</td>
      <td>3</td>
      <td>6368.0</td>
      <td>9500.0</td>
      <td>3000.0</td>
      <td>150.0</td>
      <td>24046576.0</td>
      <td>2558.650243</td>
      <td>3775.57</td>
    </tr>
    <tr>
      <td>112976</td>
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
      <td>0</td>
      <td>6014.0</td>
      <td>1</td>
      <td>16371.0</td>
      <td>9500.0</td>
      <td>2150.0</td>
      <td>50.0</td>
      <td>46735356.0</td>
      <td>2276.755156</td>
      <td>2854.59</td>
    </tr>
    <tr>
      <td>112977</td>
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
      <td>0</td>
      <td>4345.0</td>
      <td>3</td>
      <td>4940.0</td>
      <td>9500.0</td>
      <td>2999.0</td>
      <td>149.0</td>
      <td>17934852.0</td>
      <td>2537.956443</td>
      <td>3629.80</td>
    </tr>
    <tr>
      <td>112978</td>
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
      <td>0</td>
      <td>NaN</td>
      <td>1</td>
      <td>4940.0</td>
      <td>9500.0</td>
      <td>2999.0</td>
      <td>149.0</td>
      <td>17934852.0</td>
      <td>2537.956443</td>
      <td>3629.80</td>
    </tr>
    <tr>
      <td>112979</td>
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
      <td>0</td>
      <td>4151.0</td>
      <td>3</td>
      <td>5778.0</td>
      <td>9500.0</td>
      <td>1400.0</td>
      <td>50.0</td>
      <td>11955982.0</td>
      <td>1871.933447</td>
      <td>2068.87</td>
    </tr>
  </tbody>
</table>
<p>112980 rows × 41 columns</p>
</div>




```python
brand_fe
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
      <th>brand</th>
      <th>brand_amount</th>
      <th>brand_price_max</th>
      <th>brand_price_median</th>
      <th>brand_price_min</th>
      <th>brand_price_sum</th>
      <th>brand_price_std</th>
      <th>brand_price_average</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>0</td>
      <td>16371.0</td>
      <td>9500.0</td>
      <td>2150.0</td>
      <td>50.0</td>
      <td>46735356.0</td>
      <td>2276.755156</td>
      <td>2854.59</td>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
      <td>4940.0</td>
      <td>9500.0</td>
      <td>2999.0</td>
      <td>149.0</td>
      <td>17934852.0</td>
      <td>2537.956443</td>
      <td>3629.80</td>
    </tr>
    <tr>
      <td>2</td>
      <td>3</td>
      <td>665.0</td>
      <td>9500.0</td>
      <td>2800.0</td>
      <td>99.0</td>
      <td>2158773.0</td>
      <td>2058.532395</td>
      <td>3241.40</td>
    </tr>
    <tr>
      <td>3</td>
      <td>4</td>
      <td>6368.0</td>
      <td>9500.0</td>
      <td>3000.0</td>
      <td>150.0</td>
      <td>24046576.0</td>
      <td>2558.650243</td>
      <td>3775.57</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
      <td>2842.0</td>
      <td>9500.0</td>
      <td>1850.0</td>
      <td>75.0</td>
      <td>6562224.0</td>
      <td>1738.415572</td>
      <td>2308.20</td>
    </tr>
    <tr>
      <td>5</td>
      <td>6</td>
      <td>5778.0</td>
      <td>9500.0</td>
      <td>1400.0</td>
      <td>50.0</td>
      <td>11955982.0</td>
      <td>1871.933447</td>
      <td>2068.87</td>
    </tr>
    <tr>
      <td>6</td>
      <td>7</td>
      <td>1035.0</td>
      <td>9500.0</td>
      <td>1500.0</td>
      <td>100.0</td>
      <td>2372550.0</td>
      <td>2071.320262</td>
      <td>2290.11</td>
    </tr>
    <tr>
      <td>7</td>
      <td>8</td>
      <td>705.0</td>
      <td>9500.0</td>
      <td>1100.0</td>
      <td>125.0</td>
      <td>1077211.0</td>
      <td>1318.748474</td>
      <td>1525.79</td>
    </tr>
    <tr>
      <td>8</td>
      <td>9</td>
      <td>4487.0</td>
      <td>9500.0</td>
      <td>1250.0</td>
      <td>55.0</td>
      <td>7867901.0</td>
      <td>1556.621159</td>
      <td>1753.10</td>
    </tr>
    <tr>
      <td>9</td>
      <td>10</td>
      <td>3557.0</td>
      <td>9500.0</td>
      <td>2490.0</td>
      <td>200.0</td>
      <td>10936962.0</td>
      <td>2180.881827</td>
      <td>3073.91</td>
    </tr>
    <tr>
      <td>10</td>
      <td>11</td>
      <td>1390.0</td>
      <td>9500.0</td>
      <td>1750.0</td>
      <td>50.0</td>
      <td>3513591.0</td>
      <td>2151.572044</td>
      <td>2525.95</td>
    </tr>
    <tr>
      <td>11</td>
      <td>12</td>
      <td>549.0</td>
      <td>9500.0</td>
      <td>1850.0</td>
      <td>100.0</td>
      <td>1413264.0</td>
      <td>2091.218447</td>
      <td>2569.57</td>
    </tr>
    <tr>
      <td>12</td>
      <td>13</td>
      <td>1689.0</td>
      <td>8950.0</td>
      <td>1250.0</td>
      <td>25.0</td>
      <td>2832005.0</td>
      <td>1363.018568</td>
      <td>1675.74</td>
    </tr>
    <tr>
      <td>13</td>
      <td>14</td>
      <td>8784.0</td>
      <td>9500.0</td>
      <td>1350.0</td>
      <td>13.0</td>
      <td>17445064.0</td>
      <td>1797.704405</td>
      <td>1985.78</td>
    </tr>
    <tr>
      <td>14</td>
      <td>15</td>
      <td>389.0</td>
      <td>9500.0</td>
      <td>5700.0</td>
      <td>1800.0</td>
      <td>2247357.0</td>
      <td>1795.404288</td>
      <td>5762.45</td>
    </tr>
    <tr>
      <td>15</td>
      <td>16</td>
      <td>291.0</td>
      <td>8900.0</td>
      <td>1950.0</td>
      <td>300.0</td>
      <td>636703.0</td>
      <td>1223.490908</td>
      <td>2180.49</td>
    </tr>
    <tr>
      <td>16</td>
      <td>17</td>
      <td>542.0</td>
      <td>9500.0</td>
      <td>1970.0</td>
      <td>150.0</td>
      <td>1444129.0</td>
      <td>2136.402905</td>
      <td>2659.54</td>
    </tr>
    <tr>
      <td>17</td>
      <td>18</td>
      <td>66.0</td>
      <td>8990.0</td>
      <td>1650.0</td>
      <td>150.0</td>
      <td>167360.0</td>
      <td>2514.210817</td>
      <td>2497.91</td>
    </tr>
    <tr>
      <td>18</td>
      <td>19</td>
      <td>341.0</td>
      <td>9100.0</td>
      <td>1200.0</td>
      <td>130.0</td>
      <td>540335.0</td>
      <td>1337.203100</td>
      <td>1579.93</td>
    </tr>
    <tr>
      <td>19</td>
      <td>20</td>
      <td>514.0</td>
      <td>8150.0</td>
      <td>1200.0</td>
      <td>100.0</td>
      <td>818973.0</td>
      <td>1276.623577</td>
      <td>1590.24</td>
    </tr>
    <tr>
      <td>20</td>
      <td>21</td>
      <td>527.0</td>
      <td>8900.0</td>
      <td>1890.0</td>
      <td>99.0</td>
      <td>1285258.0</td>
      <td>1832.524896</td>
      <td>2434.20</td>
    </tr>
    <tr>
      <td>21</td>
      <td>22</td>
      <td>222.0</td>
      <td>9300.0</td>
      <td>1925.0</td>
      <td>190.0</td>
      <td>592296.0</td>
      <td>2118.280894</td>
      <td>2656.04</td>
    </tr>
    <tr>
      <td>22</td>
      <td>23</td>
      <td>68.0</td>
      <td>9500.0</td>
      <td>1194.5</td>
      <td>100.0</td>
      <td>110253.0</td>
      <td>1754.883573</td>
      <td>1597.87</td>
    </tr>
    <tr>
      <td>23</td>
      <td>24</td>
      <td>4.0</td>
      <td>8600.0</td>
      <td>7550.0</td>
      <td>5999.0</td>
      <td>29699.0</td>
      <td>1072.435041</td>
      <td>5939.80</td>
    </tr>
    <tr>
      <td>24</td>
      <td>25</td>
      <td>735.0</td>
      <td>9500.0</td>
      <td>1500.0</td>
      <td>100.0</td>
      <td>1725999.0</td>
      <td>2152.726491</td>
      <td>2345.11</td>
    </tr>
    <tr>
      <td>25</td>
      <td>26</td>
      <td>121.0</td>
      <td>9500.0</td>
      <td>2699.0</td>
      <td>300.0</td>
      <td>417260.0</td>
      <td>2563.586943</td>
      <td>3420.16</td>
    </tr>
  </tbody>
</table>
</div>



## 3️⃣.4️⃣&emsp; 树模型的数据分桶
&emsp;&emsp;数据分箱（也称为离散分箱或分段）是一种数据预处理技术，用于减少次要观察误差的影响，是一种将多个连续值分组为较少数量的“分箱”的方法。例如我们有各个年龄的数据的统计值，可以分成某个段的年龄的值。
1. 离散后稀疏向量内积乘法运算速度更快，计算结果也方便存储，容易扩展；
2. 离散后的特征对异常值更具鲁棒性，如 age>30 为 1 否则为 0，对于年龄为 200 的也不会对模型造成很大的干扰；
3. LR 属于广义线性模型，表达能力有限，经过离散化后，每个变量有单独的权重，这相当于引入了非线性，能够提升模型的表达能力，加大拟合；
4. 离散后特征可以进行特征交叉，提升表达能力，由 M+N 个变量变成 M*N 个变量，进一步引入非线形，提升了表达能力；
5. 特征离散后模型更稳定，如用户年龄区间，不会因为用户年龄长了一岁就变化

下面以`power`为例子，做一次数据分桶


```python
bin = [i*10 for i in range(31)]
data['power_bin'] = pd.cut(data['power'], bin, labels=False)
data[['power_bin', 'power']]
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
      <th>power_bin</th>
      <th>power</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>NaN</td>
      <td>0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>10.0</td>
      <td>109</td>
    </tr>
    <tr>
      <td>2</td>
      <td>10.0</td>
      <td>101</td>
    </tr>
    <tr>
      <td>3</td>
      <td>10.0</td>
      <td>101</td>
    </tr>
    <tr>
      <td>4</td>
      <td>14.0</td>
      <td>150</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>112975</td>
      <td>11.0</td>
      <td>116</td>
    </tr>
    <tr>
      <td>112976</td>
      <td>7.0</td>
      <td>75</td>
    </tr>
    <tr>
      <td>112977</td>
      <td>22.0</td>
      <td>224</td>
    </tr>
    <tr>
      <td>112978</td>
      <td>NaN</td>
      <td>334</td>
    </tr>
    <tr>
      <td>112979</td>
      <td>6.0</td>
      <td>68</td>
    </tr>
  </tbody>
</table>
<p>112980 rows × 2 columns</p>
</div>



可以看出这个分箱的作用就是将同一个区间段的功率值设为同样的值，比如101~109都设置为10.0。
然后就可以删除掉原数据了：


```python
data = data.drop(['creatDate', 'regDate', 'regionCode'], axis=1)
```


```python
print(data.shape)
data.columns
```

    (112980, 39)
    




    Index(['SaleID', 'name', 'model', 'brand', 'bodyType', 'fuelType', 'gearbox',
           'power', 'kilometer', 'notRepairedDamage', 'seller', 'offerType',
           'price', 'v_0', 'v_1', 'v_2', 'v_3', 'v_4', 'v_5', 'v_6', 'v_7', 'v_8',
           'v_9', 'v_10', 'v_11', 'v_12', 'v_13', 'v_14', 'train', 'used_time',
           'city', 'brand_amount', 'brand_price_max', 'brand_price_median',
           'brand_price_min', 'brand_price_sum', 'brand_price_std',
           'brand_price_average', 'power_bin'],
          dtype='object')



至此，可以导出给树模型用的数据


```python
data.to_csv('data_for_tree.csv', index=0)
```

## 3️⃣.5️⃣&emsp; LR与NN模型的特征构造
&emsp;&emsp;上面的步骤就是一次比较完备的特征构造，我们还可以为其他模型构造特征，主要是由于不用模型需要的数据输入是不同的。

### 3️⃣.5️⃣.1️⃣&emsp; log与归一化
观察一下数据分布


```python
data['power'].plot.hist()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x2108b6377b8>


![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004706243.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)



再看看`train`数据集的分布：


```python
train['power'].plot.hist()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x2108b4ed588>



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004719447.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

我们对其取 log，再做归一化


```python
data['power'] = np.log(data['power'] + 1) 
data['power'] = ((data['power'] - np.min(data['power'])) / (np.max(data['power']) - np.min(data['power'])))
data['power'].plot.hist()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x2108abc1438>




![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004913553.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


看看行驶里程的情况，应该是原始数据已经分好了桶


```python
data['kilometer'].plot.hist()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x2108abc1390>




![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004748777.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

归一化


```python
data['kilometer'] = ((data['kilometer'] - np.min(data['kilometer'])) / 
                        (np.max(data['kilometer']) - np.min(data['kilometer'])))
data['kilometer'].plot.hist()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x2108aca0898>


![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004923471.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)




对刚刚构造的统计量进行归一化


```python
def max_min(x):
    return (x - np.min(x)) / (np.max(x) - np.min(x))

data.columns[-10:]
```




    Index(['used_time', 'city', 'brand_amount', 'brand_price_max',
           'brand_price_median', 'brand_price_min', 'brand_price_sum',
           'brand_price_std', 'brand_price_average', 'power_bin'],
          dtype='object')




```python
for i in data.columns[-10:]:
    if np.min(data[i]) != '': # 存在空值的情况
        data[i] = max_min(data[i])
```

### 3️⃣.5️⃣.2️⃣&emsp; OneEncoder编码
&emsp;&emsp;对类别特征进行OneEncoder<br>
在此之前先介绍一下OneEncoder编码:one-hot的基本思想，将离散型特征的每一种取值都看成一种状态，若你的这一特征中有N个不相同的取值，那么我们就可以将该特征抽象成N种不同的状态，one-hot编码保证了每一个取值只会使得一种状态处于“激活态”，也就是说这N种状态中只有一个状态位值为1，其他状态位都是0。举个例子，假设我们以学历为例，我们想要研究的类别为小学、中学、大学、硕士、博士五种类别，我们使用one-hot对其编码就会得到：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004945672.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)

- dummy encoding

哑变量编码直观的解释就是任意的将一个状态位去除。还是拿上面的例子来说，我们用4个状态位就足够反应上述5个类别的信息，也就是我们仅仅使用前四个状态位 [0,0,0,0] 就可以表达博士了。只是因为对于一个我们研究的样本，他已不是小学生、也不是中学生、也不是大学生、又不是研究生，那么我们就可以默认他是博士，是不是。所以，我们用哑变量编码可以将上述5类表示成：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402004956905.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)



```python
data = pd.get_dummies(data, columns=['model', 'brand', 'bodyType', 'fuelType',
                                     'gearbox', 'notRepairedDamage', 'power_bin'])
data
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
      <th>power</th>
      <th>kilometer</th>
      <th>seller</th>
      <th>offerType</th>
      <th>price</th>
      <th>v_0</th>
      <th>v_1</th>
      <th>v_2</th>
      <th>...</th>
      <th>power_bin_0.6896551724137931</th>
      <th>power_bin_0.7241379310344828</th>
      <th>power_bin_0.7586206896551724</th>
      <th>power_bin_0.7931034482758621</th>
      <th>power_bin_0.8275862068965517</th>
      <th>power_bin_0.8620689655172413</th>
      <th>power_bin_0.896551724137931</th>
      <th>power_bin_0.9310344827586207</th>
      <th>power_bin_0.9655172413793104</th>
      <th>power_bin_1.0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>2262</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>3600.0</td>
      <td>45.305273</td>
      <td>5.236112</td>
      <td>0.137925</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>5</td>
      <td>137642</td>
      <td>0.474626</td>
      <td>0.655172</td>
      <td>0</td>
      <td>0</td>
      <td>8000.0</td>
      <td>46.323165</td>
      <td>-3.229285</td>
      <td>0.156615</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>2</td>
      <td>7</td>
      <td>165346</td>
      <td>0.467002</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>1000.0</td>
      <td>42.255586</td>
      <td>-3.167771</td>
      <td>-0.676693</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>3</td>
      <td>10</td>
      <td>18961</td>
      <td>0.467002</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>3100.0</td>
      <td>45.401241</td>
      <td>4.195311</td>
      <td>-0.370513</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>4</td>
      <td>13</td>
      <td>8129</td>
      <td>0.506615</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>3100.0</td>
      <td>46.844574</td>
      <td>4.175332</td>
      <td>0.490609</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>112975</td>
      <td>199995</td>
      <td>20903</td>
      <td>0.480856</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>45.621391</td>
      <td>5.958453</td>
      <td>-0.918571</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112976</td>
      <td>199996</td>
      <td>708</td>
      <td>0.437292</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>43.935162</td>
      <td>4.476841</td>
      <td>-0.841710</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112977</td>
      <td>199997</td>
      <td>6693</td>
      <td>0.546885</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>46.537137</td>
      <td>4.170806</td>
      <td>0.388595</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112978</td>
      <td>199998</td>
      <td>96900</td>
      <td>0.587076</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>46.771359</td>
      <td>-3.296814</td>
      <td>0.243566</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112979</td>
      <td>199999</td>
      <td>193384</td>
      <td>0.427535</td>
      <td>0.586207</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>43.731010</td>
      <td>-3.121867</td>
      <td>0.027348</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>112980 rows × 369 columns</p>
</div>



- 将这份数据输出给LR模型使用


```python
data.to_csv('data_for_lr.csv', index=0)
```

## 3️⃣.6️⃣&emsp; 特征选择
### 3️⃣.6️⃣.1️⃣&emsp; 过滤式(filter)
相关性分析


```python
print(data['power'].corr(data['price'], method='spearman'))
print(data['kilometer'].corr(data['price'], method='spearman'))
print(data['brand_amount'].corr(data['price'], method='spearman'))
print(data['brand_price_average'].corr(data['price'], method='spearman'))
print(data['brand_price_max'].corr(data['price'], method='spearman'))
print(data['brand_price_median'].corr(data['price'], method='spearman'))
```

    0.4698539569820024
    -0.19974282513118508
    0.04085800320025127
    0.3135239590412946
    0.07894119089254827
    0.3138873049004745
    

可以看出`power`，`brand_price_average`，`brand_price_median`与`price`相关性比较高


```python
data_numeric = data[['power', 'kilometer', 'brand_amount', 'brand_price_average', 
                     'brand_price_max', 'brand_price_median']]
correlation = data_numeric.corr()

f , ax = plt.subplots(figsize = (7, 7))
plt.title('Correlation of Numeric Features with Price',y=1,size=30)
sns.heatmap(correlation, square = True, cmap = 'PuBuGn', vmax=0.8)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x21096f60198>




![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402005026878.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)


看不出来啥。😛

### 3️⃣.6️⃣.2️⃣&emsp; 包裹式(wrapper)


```python
!pip install mlxtend
```

    Collecting mlxtend
      Downloading https://files.pythonhosted.org/packages/64/e2/1610a86284029abcad0ac9bc86cb19f9787fe6448ede467188b2a5121bb4/mlxtend-0.17.2-py2.py3-none-any.whl (1.3MB)
    Requirement already satisfied: setuptools in d:\software\anaconda\lib\site-packages (from mlxtend) (40.8.0)
    Requirement already satisfied: pandas>=0.24.2 in d:\software\anaconda\lib\site-packages (from mlxtend) (0.25.1)
    Requirement already satisfied: scipy>=1.2.1 in d:\software\anaconda\lib\site-packages (from mlxtend) (1.2.1)
    Requirement already satisfied: matplotlib>=3.0.0 in d:\software\anaconda\lib\site-packages (from mlxtend) (3.0.3)
    Requirement already satisfied: numpy>=1.16.2 in d:\software\anaconda\lib\site-packages (from mlxtend) (1.16.2)
    Collecting joblib>=0.13.2 (from mlxtend)
      Downloading https://files.pythonhosted.org/packages/28/5c/cf6a2b65a321c4a209efcdf64c2689efae2cb62661f8f6f4bb28547cf1bf/joblib-0.14.1-py2.py3-none-any.whl (294kB)
    Requirement already satisfied: scikit-learn>=0.20.3 in d:\software\anaconda\lib\site-packages (from mlxtend) (0.20.3)
    Requirement already satisfied: pytz>=2017.2 in d:\software\anaconda\lib\site-packages (from pandas>=0.24.2->mlxtend) (2018.9)
    Requirement already satisfied: python-dateutil>=2.6.1 in d:\software\anaconda\lib\site-packages (from pandas>=0.24.2->mlxtend) (2.8.0)
    Requirement already satisfied: cycler>=0.10 in d:\software\anaconda\lib\site-packages (from matplotlib>=3.0.0->mlxtend) (0.10.0)
    Requirement already satisfied: kiwisolver>=1.0.1 in d:\software\anaconda\lib\site-packages (from matplotlib>=3.0.0->mlxtend) (1.0.1)
    Requirement already satisfied: pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.1 in d:\software\anaconda\lib\site-packages (from matplotlib>=3.0.0->mlxtend) (2.3.1)
    Requirement already satisfied: six>=1.5 in d:\software\anaconda\lib\site-packages (from python-dateutil>=2.6.1->pandas>=0.24.2->mlxtend) (1.12.0)
    Installing collected packages: joblib, mlxtend
    Successfully installed joblib-0.14.1 mlxtend-0.17.2
    


```python
x
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
      <th>power</th>
      <th>kilometer</th>
      <th>seller</th>
      <th>offerType</th>
      <th>v_0</th>
      <th>v_1</th>
      <th>v_2</th>
      <th>v_3</th>
      <th>...</th>
      <th>power_bin_0.6896551724137931</th>
      <th>power_bin_0.7241379310344828</th>
      <th>power_bin_0.7586206896551724</th>
      <th>power_bin_0.7931034482758621</th>
      <th>power_bin_0.8275862068965517</th>
      <th>power_bin_0.8620689655172413</th>
      <th>power_bin_0.896551724137931</th>
      <th>power_bin_0.9310344827586207</th>
      <th>power_bin_0.9655172413793104</th>
      <th>power_bin_1.0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>2262</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>45.305273</td>
      <td>5.236112</td>
      <td>0.137925</td>
      <td>1.380657</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>5</td>
      <td>137642</td>
      <td>0.474626</td>
      <td>0.655172</td>
      <td>0</td>
      <td>0</td>
      <td>46.323165</td>
      <td>-3.229285</td>
      <td>0.156615</td>
      <td>-1.727217</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>2</td>
      <td>7</td>
      <td>165346</td>
      <td>0.467002</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>42.255586</td>
      <td>-3.167771</td>
      <td>-0.676693</td>
      <td>1.942673</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>3</td>
      <td>10</td>
      <td>18961</td>
      <td>0.467002</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>45.401241</td>
      <td>4.195311</td>
      <td>-0.370513</td>
      <td>0.444251</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>4</td>
      <td>13</td>
      <td>8129</td>
      <td>0.506615</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>46.844574</td>
      <td>4.175332</td>
      <td>0.490609</td>
      <td>0.085718</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <td>112975</td>
      <td>199995</td>
      <td>20903</td>
      <td>0.480856</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>45.621391</td>
      <td>5.958453</td>
      <td>-0.918571</td>
      <td>0.774826</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112976</td>
      <td>199996</td>
      <td>708</td>
      <td>0.437292</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>43.935162</td>
      <td>4.476841</td>
      <td>-0.841710</td>
      <td>1.328253</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112977</td>
      <td>199997</td>
      <td>6693</td>
      <td>0.546885</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>46.537137</td>
      <td>4.170806</td>
      <td>0.388595</td>
      <td>-0.704689</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112978</td>
      <td>199998</td>
      <td>96900</td>
      <td>0.587076</td>
      <td>1.000000</td>
      <td>0</td>
      <td>0</td>
      <td>46.771359</td>
      <td>-3.296814</td>
      <td>0.243566</td>
      <td>-1.277411</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>112979</td>
      <td>199999</td>
      <td>193384</td>
      <td>0.427535</td>
      <td>0.586207</td>
      <td>0</td>
      <td>0</td>
      <td>43.731010</td>
      <td>-3.121867</td>
      <td>0.027348</td>
      <td>-0.808914</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>112980 rows × 368 columns</p>
</div>




```python
from mlxtend.feature_selection import SequentialFeatureSelector as SFS
from sklearn.linear_model import LinearRegression
sfs = SFS(LinearRegression(),
           k_features=10,
           forward=True,
           floating=False,
           scoring = 'r2',
           cv = 0)
x = data.drop(['price'], axis=1)
x = x.fillna(0)
y = data['price']
x.dropna(axis=0, how='any', inplace=True)
y.dropna(axis=0, how='any', inplace=True)
sfs.fit(x, y)
sfs.k_feature_names_ 
```

画出来，可以看到边际效益


```python
from mlxtend.plotting import plot_sequential_feature_selection as plot_sfs
import matplotlib.pyplot as plt
fig1 = plot_sfs(sfs.get_metric_dict(), kind='std_dev')
plt.grid()
plt.show()
```

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200402005051474.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0V4Y2FsaWJ1clVsaW1pdGVk,size_16,color_FFFFFF,t_70#pic_center)
### 3️⃣.6️⃣.3️⃣&emsp; 嵌入式（embedding）
Lasso 回归和决策树可以完成嵌入式特征选择，大部分情况下都是用嵌入式做特征筛选。

下一步就是建模了。🤔






