---
title: review
date: 2021-07-21 09:28:34
tags:
---

# Program File List

├── code
│   ├ ── main.py｜程序入口
│   ├ ── Entity.py ｜ 一些与实体类有关的虚类/简单类定义
│   ├ ── FileHelper.py ｜ 文件操作相关
│   ├ ── **Hotspot.py ｜ 热点类 CHotspot**
│   ├ ── **HotspotSelect.py ｜ 热点选取算法**
│   ├ ── Node.py ｜ 传感器节点类 CNode
│   ├ ── Position.py ｜ 节点位置点类 CPosition
│   ├ ── **Simulation.py ｜ 仿真相关**
│   ├ ── SortHelper.py ｜ 排序相关
│   ├ ── Trace.py ｜ 传感器节点轨迹类 CTrace
│   └── **Configuration.py ｜ 用于实现配置参数的定义、初始化**
├── res
│   ├ ── NCSU ｜ 数据集（共35个节点）
└── test ｜ 测试数据集（因为源数据集较大运行时间较长，所以从中挑选了五个节点）
    └── NCSU
        ├ ── 1.trace
        ├ ── 2.trace
        ├ ── 3.trace
        ├ ── 4.trace
        ├ ── 5.trace
        ├ ── range.log
        └── readme.txt

### 研究的问题

Wireless Charger Placement and Power
Allocation for Maximizing Charging Quality  

研究的问题十分场景化，无线传感器网络虽然广泛应用，但是受限于传感器的体积和成本，能源效率不高（电池很容易没电），无线充电技术的突破为解决传感器能源问题提供了新思路。我研究的问题是移动可充电传感器的充电桩部署问题，让这些传感器存活的时间更长，解决这个问题一般需要对于传感器移动的轨迹建模。我的工作首先使用了三周的时间对一篇IEEE transactions on mobile computing的论文进行复现。复现分为两个方面：

1、复现算法

2、利用基于真实世界的数据集构建完整的仿真系统

数据读入、充电桩选择性、模拟
