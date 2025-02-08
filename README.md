# UAV-based-Unsupervised-Domain-Adaptation-for-Road-Extraction
## IEEE Geoscience and Remote Sensing Letters

## Abstract
Despite advances in Deep Learning (DL) in the road extraction research topic, this task remains challenging. Domain shifts in data distribution hinder the inference of pre-trained models to new areas, leading to a drop in classification accuracy. Additionally, a mass of labeled training data is a prerequisite to DL-based models. To address these challenges, this letter proposes an Unsupervised Domain Adaptation (UDA) approach leveraging the Domain Adversarial Neural Network (DANN) strategy applied to Unmanned Aerial Vehicles (UAVs) data. Our UDA approach deals with different geographical contexts, very high-resolution UAV images, and potential variations in road network scene complexity. We evaluate the method on DeepLabv3+, ResU-Net, and Att-ResU-Net, which employs an attention mechanism in skip connections. Experimental results demonstrate that UDA enhances road extraction performance by 1.79-6.07% on F1-Score and 2.12-7.85% on IoU when tested on the target domain without labeled training data, with Att- ResU-Net achieving the highest UDA performance. Qualitative results further suggest that, despite domain-specific variations of the roads, the network continues to focus on its features.

![](figures/dann_method.jpg)
