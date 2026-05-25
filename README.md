# GlobalWR-2025
🌍 Global Winter Rapeseed Dataset (GlobalWR-2025)
🌍 全球冬油菜数据集 (GlobalWR-2025)

📖 Overview | 数据集简介

EN:
This repository provides access to the Global Winter Rapeseed Dataset (GlobalWR-2025), a large-scale geospatial dataset designed for crop mapping, agricultural monitoring, and Earth observation research.

This dataset is part of our ongoing Global Spring–Winter Rapeseed Dataset project. Currently, only the winter rapeseed component is publicly available. The full dataset and associated code will be released in future updates.

中文：
本仓库发布 全球冬油菜数据集（GlobalWR-2025），该数据集面向作物制图、农业监测及地球观测研究。

该数据集属于我们正在构建的全球春冬油菜数据集的一部分。目前仅开放冬油菜数据，完整数据集及相关代码将在后续发布。

📦 Dataset Access | 数据访问

EN:
The dataset is hosted on the Google Earth Engine platform:

👉 https://code.earthengine.google.com/?asset=projects/ee-feifeicheng20/assets/GlobalWR-2025

var dataset = ee.Image("projects/ee-feifeicheng20/assets/GlobalWR-2025");

Map.addLayer(dataset, {}, "Global Winter Rapeseed");

中文：
数据集已部署在 Google Earth Engine 平台，可通过以下链接访问：

👉 https://code.earthengine.google.com/?asset=projects/ee-feifeicheng20/assets/GlobalWR-2025

var dataset = ee.Image("projects/ee-feifeicheng20/assets/GlobalWR-2025");

Map.addLayer(dataset, {}, "全球冬油菜");




📖 Citation | 引用方式


🔮 Future Work | 未来工作

EN:

Release full Global Spring–Winter Rapeseed Dataset
Open-source processing and modeling code
Improve spatial coverage and labeling quality

中文：

发布完整全球春冬油菜数据集
开源数据处理与模型代码
提升空间覆盖范围与标注质量
