---
layout: page
mathjax: true
permalink: /projects/p02/proposal/
---

## 人体行为识别

> 题目确定时间：2015.6.2

### 成员

- 刘瑀 2120141029
- 刘夏冰 2120141028
- 聂卉 2120141031

### 实验目的

根据KTH数据库中的数据，计算出行为模型，并对新视频行为进行分类。实验将会获得一系列的分类准确度，根据准确度进行数据分析。探究本行为识别算法的优势和缺点。

### 问题描述

人体行为识别可应用于监控、视频检索、人机交互等方面。因此在不同的情景中识别出人的行为的方法至关重要。本项目要求设计实现一个人体行为识别的系统。人体行为识别的研究首先从视频序列中提取视频特征，然后根据提取的特征信息计算行为模型，最后根据已有的行为模型完成对新视频的识别。其中特征提取，行为模型，行为识别这三个方面为主要研究方法。

### 数据集

KTH:http://www.nada.kth.se/cvap/actions/

KTH行人数据库包含了6种动作，分别为走，慢跑，跑挥手和鼓掌。每种动作由25个不同的人完成。每个人在完成这些动作时又是在4个不同的场景中完成的，4个场景分别为室外，室内，室外放大，室外且穿不同颜色的衣服。

### 实现

- 编程环境：Matlab
- 主要算法：时空兴趣点，PCA, k-means, SVM等