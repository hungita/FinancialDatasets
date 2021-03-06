﻿# FinancialDatasets
SmoothNLP 金融文本数据集(公开) | Public Financial Datasets for NLP Researches 

[**API接口服务**](https://github.com/smoothnlp/smoothnlp_api)

## 数据一览
> 由于github存储有限, 如需**全量**数据集, 请**联系**: contact@smoothnlp.com

| 数据名称  | 数据字段 | 样本量 | 总量 |  下载链接 |
| ----- |  ------ | ----- | ----- | ----- |
| 企业工商信息 | `名称`,`公司名称`,`公司介绍`,`工商`,`地址`,`工商注册id`,`成立时间`,`法人代表`,`注册资金`,`统一信用代码`,`网址` | 1万 | 50万 - (上市及中小型企业) |[下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E5%B7%A5%E5%95%86%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10K.xlsx) | 
| 金融讯息新闻 | `title-新闻标题`,`content-新闻内容`,`pub_ts-发稿日期` | 2万 | 210万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E4%B8%93%E6%A0%8F%E8%B5%84%E8%AE%AF%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10k.xlsx) |
| 专栏资讯 | `title-新闻标题`,`content-新闻内容`,`pub_ts-发稿日期` | 1万 | 58万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E4%B8%93%E6%A0%8F%E8%B5%84%E8%AE%AF%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC10k.xlsx) |
| 投资机构信息 | `机构名称`,`介绍`,`行业`,`规模`,`轮次`| 1K | 3万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E6%8A%95%E8%B5%84%E7%BB%93%E6%9E%84%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC1k.xlsx) |
| 投资事件 | `事件资讯`,`投资方`,`融资方`,`融资事件`,`轮次`,`金额` | 2K | 7万 | [下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP%E6%8A%95%E8%B5%84%E4%BA%8B%E4%BB%B6%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A0%B7%E6%9C%AC2k.xlsx) |
|36氪新闻| `title-新闻标题`,`content-新闻内容`,`url-网址` |1万|11万|[下载](https://github.com/smoothnlp/FinancialDatasets/blob/master/data/SmoothNLP36kr新闻数据集10k.xlsx)

## 推荐研究方向
* Embedding (Word2Vec, Bert, 等)
* 实体识别 - NER
* 无监督聚类: 基于企业描述信息, 进行竞品聚类
* 企业行业分类
* 标题总结 - Text Summary
* 序列分类 - Sequence Classification

## 数据展示
#### 投资机构
![机构](/demo/%E6%8A%95%E8%B5%84%E6%9C%BA%E6%9E%84demo.png)
#### 投资事件
![投资事件](/demo/%E6%8A%95%E8%B5%84%E4%BA%8B%E4%BB%B6demo.png)

#### 企业工商信息
![工商](/demo/%E5%B7%A5%E5%95%86%E6%95%B0%E6%8D%AEdemo.png)
##### 金融资讯新闻
![新闻](/demo/%E9%87%91%E8%9E%8D%E6%96%B0%E9%97%BBdemo.png)
##### 专栏资讯
![专栏](/demo/%E4%B8%93%E6%A0%8F%E8%B5%84%E8%AE%AFdemo.png)
##### 36氪新闻
![36氪](https://github.com/smoothnlp/FinancialDatasets/blob/master/demo/36kr新闻demo.PNG)



