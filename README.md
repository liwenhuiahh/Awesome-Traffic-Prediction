# Awesome Traffic Prediction

![Awesome--Traffic-v1.0](https://img.shields.io/badge/Awesome--Traffic-v1.0-brightgreen)![](https://img.shields.io/badge/dataset-v0.1-green)![](https://img.shields.io/badge/paper-v0.1-orange)

This repository contains useful resources for traffic prediction, including popular papers, datasets, tutorials, toolkits, and other helpful repositories.

## 0x00 Papers

### Reviews

1. [TITS 2015] Traffic Flow Prediction With Big Data: A Deep Learning Approach [[paper]](https://bookdown.org/amanas/traficomadrid/docs/Traffic%20flow%20prediction%20with%20big%20data%20-%20A%20deep%20learning%20approach.pdf)
2. [KDD 2020] Deep Learning for Spatio-Temporal Data Mining: A Survey [[paper]](https://ieeexplore.ieee.org/abstract/document/9204396/)
3. [Information Fusion 2020] Urban flow prediction from spatiotemporal data using machine learning: A survey [[paper]](https://www.sciencedirect.com/science/article/pii/S1566253519303094)
4. [Arxiv 2020] Deep Learning on Traffic Prediction: Methods, Analysis and Future Directions [[paper]](https://arxiv.org/abs/2004.08555)

### Deep Learning Based Traffic Prediction Methods

##### 2015

1. [NIPS 2015] Convolutional LSTM Network: A Machine Learning Approach for Precipitation Nowcasting [[paper]](https://papers.nips.cc/paper/2015/file/07563a3fe3bbe7e3ba84431ad9d055af-Paper.pdf)

##### 2016

1. [Sigspatial 2016] DNN-Based Prediction Model for Spatio-Temporal Data [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/09/DeepST-SIGSPATIAL2016.pdf) [[code]](https://arxiv.org/pdf/1610.00081.pdf)

##### 2017

1. [AAAI 2017] Deep Spatio-Temporal Residual Networks for Citywide Crowd Flows Prediction [[paper]](https://arxiv.org/pdf/1610.00081.pdf)
2. [*ISPRS* 2017] Road2Vec: Measuring Traffic Interactions in Urban Road System from Massive Travel Routes [[paper]](https://www.mdpi.com/2220-9964/6/11/321)
3. [Arxiv 2017] DeepTransport: Learning Spatial-Temporal Dependency for Traffic Condition Forecasting [[paper]](https://arxiv.org/pdf/1709.09585.pdf)

##### 2018

1. [TITS 2019] T-GCN: A Temporal Graph Convolutional Network for Traffic Prediction [[paper]](https://arxiv.org/pdf/1811.05320v3.pdf) [[code]](https://github.com/lehaifeng/T-GCN)
2. [TKDE 2018] Flow prediction in spatio-temporal networks based on multitask deep learning [[paper]](https://ieeexplore.ieee.org/abstract/document/8606218/)
3. [TITS 2018] Missing Value Imputation for Traffic-Related Time Series Data Based on a Multi-View Learning Method [[paper]](https://ieeexplore.ieee.org/abstract/document/8478191)
4. [IJCAI 2018] Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting [[paper]](https://www.ijcai.org/Proceedings/2018/0505.pdf) [[code]](https://paperswithcode.com/paper/spatio-temporal-graph-convolutional-networks) [[review]](https://openreview.net/forum?id=SkNeyVzOWB)
5. [IJCAI 2018] LC-RNN: A Deep Learning Model for Traffic Speed Prediction [[paper]](https://www.ijcai.org/Proceedings/2018/482)
6. [ICLR 2018] Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting [[paper]](https://arxiv.org/abs/1707.01926) [[code-official-tf]](https://github.com/liyaguang/DCRNN) [[code-pytorch]](https://github.com/xlwang233/pytorch-DCRNN) [[review]](https://openreview.net/forum?id=SJiHXGWAZ) [[data]](https://drive.google.com/drive/folders/10FOTa6HXPqX8Pf5WRoRwcFnW9BrNZEIX?usp=drive_open)
7. [KDD 2018] *Hetero*-*ConvLSTM: A Deep Learning Approach to Traffic Accident Prediction on Heterogeneous Spatio*-Temporal Data [[paper]](https://www.kdd.org/kdd2018/accepted-papers/view/hetero-convlstm-a-deep-learning-approach-to-traffic-accident-prediction-on-)
8. [CS224W 2018] Efficient Traffic Forecasting With Graph Embedding [[paper]](http://snap.stanford.edu/class/cs224w-2018/reports/CS224W-2018-42.pdf) [[code]](https://github.com/syin3/cs224w-traffic)
9. [CVPR 2018] **[Social GAN: Socially Acceptable Trajectories with Generative Adversarial Networks](https://arxiv.org/abs/1803.10892)** [[paper]](https://ieeexplore.ieee.org/document/8578338) [[code]](https://github.com/agrimgupta92/sgan)
10. [AAAI 2018] **Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction** [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11836)[[code]](https://github.com/huaxiuyao/DMVST-Net) [[data]](https://outreach.didichuxing.com/appEn-vue/Personal) 
11. ……

##### 2019

1. [TITS 2019] TrafficGAN: Network-Scale Deep Traffic Prediction With Generative Adversarial Nets [[paper]](https://ieeexplore.ieee.org/document/8935152)
2. [TITS 2019] Contextualized Spatial–Temporal Network for Taxi Origin-Destination Demand Prediction [[paper]](https://ieeexplore.ieee.org/abstract/document/8720246) [[code]](https://github.com/liulingbo918/CSTN)
3. [TITS 2019] *Deep Spatial-Temporal 3D Convolutional Neural Networks for Traffic Data Forecasting* [[paper]](https://ieeexplore.ieee.org/document/8684259)
4. [IJCAI 2019] Graph WaveNet for Deep Spatial-Temporal Graph Modeling [[paper]](https://www.ijcai.org/Proceedings/2019/0264.pdf) [[code]](https://github.com/nnzhan/Graph-WaveNet)
5. [IJCAI 2019] GSTNet: Global Spatial-Temporal Network for Traffic Flow Prediction [[paper]](https://www.aminer.cn/pub/5d4d46fb3a55acff992fdb8a/gstnet-global-spatial-temporal-network-for-traffic-flow-prediction?s=social)
6. [AAAI 2019] Revisiting Spatial-Temporal Similarity: A Deep Learning Framework for Traffic Prediction [[paper]](https://arxiv.org/pdf/1803.01254v2.pdf) [[code]](https://github.com/tangxianfeng/STDN)
7. [AAAI 2019] DeepSTN+: Context-aware Spatial-Temporal Neural Network for Crowd Flow Prediction in Metropolis [[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/3892) [[code]](https://github.com/FIBLAB/DeepSTN)
8. [AAAI 2019] **Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting** [[paper]](https://aaai.org/ojs/index.php/AAAI/article/view/3881) [[code-pytorch]](https://github.com/guoshnBJTU/ASTGCN-r-pytorch)
9. [WWWC 2019] Learning from Multiple Cities: A Meta-Learning Approach for Spatial-Temporal Prediction [[paper]](https://dl.acm.org/doi/abs/10.1145/3308558.3313577)
10. [IWPHM 2019] Spatio-Temporal Clustering of Traffic Data with Deep Embedded Clustering [[paper]](https://dl.acm.org/doi/abs/10.1145/3356995.3364537)
11. [ICCV 2019] STGAT: Modeling Spatial-Temporal Interactions for Human Trajectory Prediction [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.html) [[code]](https://github.com/huang-xx/STGAT)
12. [KDD 2019] Urban Traffic Prediction from Spatio-Temporal Data Using Deep Meta Learning [[paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3330884)[[code]](https://github.com/panzheyi/ST-MetaNet)
13. [ICIKM 2019] Matrix Factorization for Spatio-Temporal Neural Networks with Applications to Urban Flow Prediction [[paper]](https://dl.acm.org/doi/abs/10.1145/3357384.3357832)
14. [TKDE 2019] Flow prediction in spatio-temporal networks based on multitask deep learning [[paper]](https://ieeexplore.ieee.org/document/8606218)
15. [IJGIS 2019] Traffic speed prediction for intelligent transportation system based on a deep feature fusion model [[paper]](https://www.tandfonline.com/doi/abs/10.1080/15472450.2019.1583965?journalCode=gits20)
16. [Access 2019] Spatial-Temporal Graph Attention Networks: A Deep Learning Approach for Traffic Forecasting [[paper]](https://ieeexplore.ieee.org/document/8903252)
17. [Arxiv 2019] *Forecaster: A graph transformer for forecasting spatial and time dependent data* [[paper]]()
18. [Arxiv 2019] *Temporal fusion transformers for interpretable multi-horizon time series forecasting*. [[paper]](https://arxiv.org/abs/1912.09363)
19. ……

##### 2020

1. [Arxiv 2020] Spatial-Temporal Transformer Networks for Traffic Flow Forecasting [[paper]](https://arxiv.org/abs/2001.02908) [[code-not-official]](https://github.com/wubin5/STTN)
2. [Arxiv 2020] Transfer Learning with Graph Neural Networks for Short-Term Highway Traffic Forecasting [[paper]](https://arxiv.org/abs/2004.08038) [[code]](https://github.com/tanwimallick/TL-DCRNN)
3. [Arxiv 2020] Bayesian Spatio-Temporal Graph Convolutional Network for Traffic Forecasting [[paper]](https://www.researchgate.net/publication/344678512_Bayesian_Spatio-Temporal_Graph_Convolutional_Network_for_Traffic_Forecasting)
4. [TGIS 2020] Traffic transformer: Capturing the continuity and periodicity of time series for traffic forecasting [[paper]](https://onlinelibrary.wiley.com/doi/abs/10.1111/tgis.12644)
5. [ICTON 2020] Traffic Prediction in Optical Networks Using Graph Convolutional Generative Adversarial Networks [[paper]](https://ieeexplore.ieee.org/document/9203477)
6. [AAAI 2020] Spatio-Temporal Graph Structure Learning for Traffic Forecasting [[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5470) [[SOTA]](https://paperswithcode.com/paper/spatio-temporal-graph-structure-learning-for)
7. [AAAI 2020] Learning Geo-Contextual Embeddings for Commuting Flow Prediction [[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/5425)
8. [AAAI 2020] Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5438) [[code]](https://github.com/Davidham3/STSGCN)
9. [Access 2020] STGAT: Spatial-Temporal Graph Attention Networks for Traffic Flow Forecasting [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9146162)
10. [Sensor 2020] City-Wide Traffic Flow Forecasting Using a Deep Convolutional Neural Network [[paper]](https://www.mdpi.com/1424-8220/20/2/421)
11. [Mobile Computing 2020] BuildSenSys: Reusing Building Sensing Data for Traffic Prediction with Cross-domain Learning [[paper]](https://ieeexplore.ieee.org/abstract/document/9018140)
12. [TKDE 2020] Spatio-Temporal Meta Learning for Urban Traffic Prediction [[paper]](https://ieeexplore.ieee.org/document/9096591)
13. [WC 2020] What is the Human Mobility in a New City: Transfer Mobility Knowledge Across Cities [[paper]](http://urban-computing.com/pdf/www1208tianfu.pdf)
14. [TITS 2020] Traffic Graph Convolutional Recurrent Neural Network: A Deep Learning Framework for Network-Scale Traffic Learning and Forecasting [[paper]](https://ieeexplore.ieee.org/document/8917706) [[code]](https://github.com/zhiyongc/Graph_Convolutional_LSTM)
15. [NIPS 2020] Adaptive Graph Convolutional Recurrent Network for Traffic Forecasting [[code]](https://github.com/LeiBAI/AGCRN) [[code]](https://github.com/LeiBAI/AGCRN)
16. [AAAI 2020] **GMAN: A Graph Multi-Attention Network for Traffic Prediction** [[paper]](https://arxiv.org/abs/1911.08415) [[code]](https://github.com/zhengchuanpan/GMAN)
17. [KDD 2020] ConSTGAT: Contextual Spatial-Temporal Graph Attention Network for Travel Time Estimation at Baidu Maps [[paper]](https://www.kdd.org/kdd2020/accepted-papers/view/constgat-contextual-spatial-temporal-graph-attention-network-for-travel-tim)
18. [KDD 2020] Preserving Dynamic Attention for Long-Term Spatial-Temporal Prediction [[paper]](https://arxiv.org/abs/2006.08849)
19. [TITS 2020] Temporal Multi-Graph Convolutional Network for Traffic Flow Prediction [[paper]](https://ieeexplore.ieee.org/document/9098104)
20. [TITS 2020] A Spatial-Temporal Attention Approach for Traffic Prediction [[paper]](https://www.researchgate.net/publication/340567373_A_Spatial-Temporal_Attention_Approach_for_Traffic_Prediction)
21. [TITS 2020] Traffic Flow Imputation Using Parallel Data and Generative Adversarial Networks [[paper]](https://ieeexplore.ieee.org/document/8699108)
22. [WWW 2020] Traffic Flow Prediction via Spatial Temporal Graph Neural Network [[paper]](https://dl.acm.org/doi/abs/10.1145/3366423.3380186)
23. [IJGIS 2020] **Graph attention temporal convolutional network for traffic speed forecasting on road networks** [[paper]](https://www.tandfonline.com/doi/abs/10.1080/21680566.2020.1822765?journalCode=ttrb20)
24. [Arxiv 2020] ST-GRAT: A Novel Spatio-temporal Graph Attention Network for Accurately Forecasting Dynamically Changing Road Speed [[paper]](https://arxiv.org/abs/1911.13181)
25. [IF 2020] **Spatial Temporal Incidence Dynamic Graph Neural Networks for Traffic Flow Forecasting** [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0020025520300451?via%3Dihub)
26. [ICDM 2020] TSSRGCN: Temporal Spectral Spatial Retrieval Graph Convolutional Network  for Traffic Flow Forecasting [[paper]](https://ieeexplore.ieee.org/document/9338393)
27. ……

#### 2021

1. Spatial-Temporal Fusion Graph Neural Networks for Traffic Flow Forecasting [[paper]](https://arxiv.org/abs/2012.09641) [[code]](https://github.com/MengzhangLI/STFGNN)
2. [TITS 2021] Spatial‐temporal attention wavenet: A deep learning framework for traffic prediction considering spatial‐temporal dependencies [[paper]](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/itr2.12044) [[code]](https://paperswithcode.com/paper/spatial-temporal-attention-wavenet-a-deep#code)
3. [Arxiv 2021] Time Series is a Special Sequence: Forecasting with Sample Convolution and Interaction [[paper]](https://arxiv.org/pdf/2106.09305v2.pdf) [[code]](https://paperswithcode.com/paper/time-series-is-a-special-sequence-forecasting#code)
4. [KDD 2021] Dynamic Graph Convolutional Recurrent Network for Traffic Prediction: Benchmark and Solution [[paper]](https://dl.acm.org/doi/10.1145/3532611) [[code]](https://github.com/tsinghua-fib-lab/Traffic-Benchmark)
5. ……

#### 2022

1. [TITS 2022] 2F-TP:Learning Flexible Spatiotemporal Dependency for Flexible Traffic Prediction. [[paper]](https://ieeexplore.ieee.org/abstract/document/9703274/)

### Statistic Based Traffic Prediction Methods

#### 2018

1. [TITS 2018] Probabilistic Data Fusion for Short-Term Traffic Prediction With Semiparametric Density Ratio Model [[paper]](https://ieeexplore.ieee.org/document/8479367)

#### 2019

1. [TRPET 2019] A generalized Bayesian traffic model [[paper]](https://www.sciencedirect.com/science/article/pii/S0968090X18318199)

### Time Series Forecasting

1. [Context-aware Forecasting for Multivariate Stationary Time-series](https://openreview.net/pdf?id=B1xHUiC5tm)
2. [Arxiv 2020] Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting [[paper]](https://arxiv.org/pdf/2012.07436.pdf) [[code]](https://github.com/zhouhaoyi/Informer2020)

## 0x01 Tutorial

### Textbook

1. [Urban Computing](https://mitpress.mit.edu/books/urban-computing)
2. [Multimodal Analytics for Next-Generation Big Data Technologies and Applications](https://www.springer.com/gp/book/9783319975979)
3. ……

### Blogs

1. [Traffic prediction with advanced Graph Neural Networks](https://deepmind.com/blog/article/traffic-prediction-with-advanced-graph-neural-networks)
2. ……

## 0x02 DataSource

### Datasets

#### Traffic Dataset in Non-China Region

1. [Cityscapes](https://www.cityscapes-dataset.com/login/)

2. [New York City](https://www.kaggle.com/c/nyc-taxi-trip-duration/overview)

3. [NYC Bike](https://www.citibikenyc.com/system-data)

4. [NYC Taxi](https://www.kaggle.com/c/nyc-taxi-trip-duration)

5. [Train Station Dataset](http://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html)

6. [Apolloscape](http://apolloscape.auto/trajectory.html)
   
   该轨迹数据集由基于摄像头的图像、激光雷达扫描的点云和人工标注的轨迹组成。该数据集是在中国北京各种光照条件和交通密度下收集的。更具体地说，它包含了高度复杂的交通流，混合了车辆、乘客和行人。

7. [data.world.traffic](https://data.world/datasets/traffic)

8. [PEMS-SF Dataset From UCI](https://archive.ics.uci.edu/ml/datasets/PEMS-SF)
   
   每个属性都描述了测量站在一天中的某个时间戳记录的捕获器位置的占用率测量值（在0和1之间）。每个测站的ID在 stations_list文本文件中给出。更多关于每个测量站的位置(GPS, 公路, 方向)的信息请参考PEMS网站。每条记录有963个（站点）x144个（时间戳）=138.672个属性。

9. [Seattle Inductive Loop Detector Dataset](https://github.com/zhiyongc/Seattle-Loop-Data)

10. [Road location and traffic data](https://www.data.qld.gov.au/dataset/road-location-and-traffic-data)

11. [INRIX – Driving Intelligence](https://datarade.ai/data-providers/inrix/profile)
    
    收费数据

12. [Los Angeles (METR-LA)](datasets/METR.md)

13. ……

#### Traffic Dataset in China

1. [百度开放数据](https://ai.baidu.com/broad/download?dataset=traffic)

2. [滴滴盖亚计划]()
   
   西安市脱敏路况预测数据，包括路网拓扑、道路属性、历史和实时车流等信息

3. [HZJTD](http://www.hzjtydzs.com/index2.html)
   
   杭州综合交通研究中心收集的数据，包括杭州主城区202条道路的交通状况、速度、拥堵指数。

4. 

#### Commute flow

1. [Longitudinal Employer-Household Dynamics](https://lehd.ces.census.gov/data/)
2. ……

#### Point of Interest/Land use

1. [PLUTO](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page)
   
   以CSV文件格式提供广泛的土地使用和地理数据。PLUTO文件包含七十多个来自城市机构维护的数据的字段。

2. ……

### Trajectory

### ETA

1. [深圳网约车行程轨迹数据-SIGSPATISL 2021 GISCUP 预估到达时间数据集](https://outreach.didichuxing.com/app-vue/DatasetProjectDetail?id=1028)

### Website

1. [Welcome to PeMS](http://pems.dot.ca.gov)
2. ……

## 0x03 Toolkits

1. [Open Source Routing Machine](http://project-osrm.org)
2. [PyG Temporal](https://pytorch-geometric-temporal.readthedocs.io/en/latest/)
3. [LibCity](https://libcity.ai)

## 0x04 Conferences & Journals

1. ACM SIGSPATIAL SpatialDI
2. [IEEE Transactions on Intelligent Transportation Systems](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979)
3. [Association for the Advancement of Artificial Intelligence](https://www.aaai.org)

## 0x05 Research Group

### Company

1. http://urban-computing.com/yuzheng
2. [DeepMind](https://deepmind.com/about/deepmind-for-google)
3. ……

### College

1. [北京交通大学 万怀宇老师团队](http://faculty.bjtu.edu.cn/8793/)
   
   主要研究方向为**数据挖掘**与**信息抽取**，具体研究兴趣包括**时空数据挖掘**、**社交网络挖掘**、**文本信息抽取**、**知识图谱应用**等

## 0x06 Related Repositories

1. [paper with code](https://paperswithcode.com/task/traffic-prediction)

2. https://github.com/topics/traffic-prediction

3. [Awesome-Trajectory-Prediction](https://github.com/xuehaouwa/Awesome-Trajectory-Prediction)

4. [traffic_prediction]([traffic_prediction](https://github.com/aprbw/traffic_prediction))

5. [transdim](https://github.com/xinychen/transdim)
   
   本项目的战略目标是为时空交通数据的拟合和预测任务创建准确和高效的解决方案。

6. [城市数据派](https://www.udparty.com/index.php/lists/cases?page=0&keyword=交通)

7. [Multivariate Time Series Forecasting](https://paperswithcode.com/task/multivariate-time-series-forecasting/latest)

8. [deep-learning-time-series](https://github.com/Alro10/deep-learning-time-series)

9. [GNN paper](https://github.com/thunlp/GNNPapers#traffic-network)

10. [Discovering millions of datasets on the web](https://blog.google/products/search/discovering-millions-datasets-web/)

11. [LibCity](https://libcity.ai)
    汇总交通预测算法、数据，统一评价体系的开源实验平台
    An open-source research platform for intergrating several algorithms, data, and evalution metrics for traffic prediction.

12. [GNN4Traffic](https://github.com/jwwthu/GNN4Traffic)

13. [交通轨迹数据、工具、论文汇总](https://zhuanlan.zhihu.com/p/119425995)

14. ……

## Contribution

To make contributions on this repo, visit [here](./CONTRIBUTION.md)
