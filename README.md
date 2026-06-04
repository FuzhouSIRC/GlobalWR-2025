# GlobalWR-2025
🌍 Global Winter Rapeseed Dataset (GlobalWR-2025-V1)

This repository provides access to the Global Winter Rapeseed Dataset (GlobalWR-2025), a large-scale geospatial dataset designed for crop mapping, agricultural monitoring, and Earth observation research. This dataset is part of our ongoing Global Spring–Winter Rapeseed Dataset project. Currently, only the winter rapeseed component is publicly available. The full dataset and associated code will be released in future updates.

📦 Dataset Access | 数据访问

The dataset is hosted on the Google Earth Engine platform:

👉 https://code.earthengine.google.com/?asset=projects/qiu-agriculture/assets/GlobalWR-2025

var dataset = ee.Image("projects/ee-feifeicheng20/assets/GlobalWR-2025");

Map.addLayer(dataset, {}, "Global Winter Rapeseed");


📖 Citation | 引用方式

Feifei Cheng, Yufeng Peng, Bingwen Qiu, Chunting Li, Wenbin Wu, Peng Yang, Bingfang Wu, Viktoria Takacs, Piotr Tryjanowski, Si Wang, Xiuchun Dong, Xuehong Chen,
GlobalWR-2025: The first global 10-meter winter rapeseed dataset developed by knowledge-guided temporal features,
International Journal of Applied Earth Observation and Geoinformation,
Volume 151,
2026,
105365,
ISSN 1569-8432,
https://doi.org/10.1016/j.jag.2026.105365.
(https://www.sciencedirect.com/science/article/pii/S1569843226002815)

🔮 Future Work

Release full Global Spring–Winter Rapeseed Dataset

Open-source processing and modeling code

Improve spatial coverage and labeling quality
