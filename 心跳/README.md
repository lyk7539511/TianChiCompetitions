# 零基础入门数据挖掘-心跳信号分类预测

## 赛题介绍

    赛题以心电图心跳信号数据为背景，要求选手根据心电图感应数据预测心跳信号所属类别，其中心跳信号对应正常病例以及受不同心律不齐和心肌梗塞影响的病例，这是一个多分类的问题。

## 数据介绍

    数据集分为两部分：train.csv、testA.csv 

### train.csv

    三列，分别为:id,heartbeat_signals.label
    heartbeat_signals:具体的心跳数据
    label:四个类别

### testA.csv

    两列:id,heartbeat_signals
    heartbeat_signals:具体的心跳数据

## 提交标准

    submit.csv，五列:id,label_0,label_1,label_2,label_3
- 使用one-hot编码

## 代码介绍

### 代码流程

#### 1、导入第三方包

    pandas,numpy,matplotlib,lightgbm,xgboost,catboost,sklearn,tqdm

- 推荐使用[conda](https://docs.conda.io/en/latest/index.html)

#### 2、读取数据

- 使用 pandas.read_csv()

#### 3、数据预处理

- 降低内存占用
- 划分训练集和验证集

#### 4、训练/测试数据准备

#### 5、模型训练

#### 6、模型测试
