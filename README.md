# UAV-based Unsupervised Domain Adaptation for Road Extraction
### IEEE Geoscience and Remote Sensing Letters

## Abstract
Despite advances in Deep Learning (DL) for road extraction, this task remains challenging. Domain shifts in data distribution hinder the inference of pre-trained models to new areas, leading to a drop in classification accuracy. Additionally, DL-based models require a large amount of labeled training data to achieve a robust performance. To overcome these challenges, this letter proposes an Unsupervised Domain Adaptation (UDA) approach leveraging the Domain Adversarial Neural Network (DANN) strategy applied to Unmanned Aerial Vehicle (UAV) imagery. While most existing approaches rely on satellite imagery, they may not generalize well to UAV data, as very high-resolution images with fine-grained road details introduce additional domain adaptation challenges. Thus, we integrate our approach with three architectures to analyze the domain alignment using UAV imagery: DeepLabv3+, ResU-Net, and Att-ResU-Net, the latter incorporating attention-enhanced skip connections. Experimental results demonstrate that UDA effectively deals with domain shift, improving road extraction performance by 1.79-6.07% on F1-Score and 2.12-7.85% on IoU when tested on the target domain without labeled training data. Among the evaluated architectures, Att-ResU-Net achieves the highest UDA performance. The qualitative analysis further illustrates how architectural differences impact UDA for UAV-based road extraction.

![](figures/dann_method.jpg)


