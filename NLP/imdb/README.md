## 结果记录

| 网络结构 | 优化算法 | 预处理 | 结果 |
| :---: | :---: | :---: | :---: |
| 单层单向LSTM | Adam:0.001：50 | 正则 | 0.81980 |
| 单层双向LSTM | Adam:0.001：50 | 正则 | 0.82696 |
| Faster-RCNN | 73.2% | 5 fps | 用RPN提取候选框 |
| YOLO | 57.9% | 45 fps | 化为回归问题暴力直接 |
| SSD | 73.9% | 58 fps |  |