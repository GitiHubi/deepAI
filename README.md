## Detection of Accounting Anomalies using Deep Autoencoder Neural Networks 

A lab we prepared for NVIDIA's GPU Technology Conference 2018 that will walk you through the detection of accounting anomalies using deep autoencoder neural networks. The the lab content is based on Jupyter Notebook, Python and PyTorch.

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GitiHubi/deepAI/master?filepath=GTC_2018_Lab.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GitiHubi/deepAI/blob/master/GTC_2018_CoLab.ipynb)

The lab is inspired by our publication: 

**"Detection of Anomalies in Large Scale Accounting Data using Deep Autoencoder Networks"** 

by Marco Schreyer, Timur Sattarov, Damian Borth, Andreas Dengel and Bernd Reimer.

**Abstract:** 

Learning to detect fraud in large-scale accounting data is one of the long-standing challenges in financial statement audits or fraud investigations. Nowadays, the majority of applied techniques refer to handcrafted rules derived from known fraud scenarios. While fairly successful, these rules exhibit the drawback that they often fail to generalize beyond known fraud scenarios and fraudsters gradually find ways to circumvent them. To overcome this disadvantage and inspired by the recent success of deep learning we propose the application of deep autoencoder neural networks to detect anomalous journal entries. We demonstrate that the trained network's reconstruction error obtainable for a journal entry and regularized by the entry's individual attribute probabilities can be interpreted as a highly adaptive anomaly assessment. Experiments on two real-world datasets of journal entries, show the effectiveness of the approach resulting in high f1-scores of 32.93 (dataset A) and 16.95 (dataset B) and less false positive alerts compared to state of the art baseline methods. Initial feedback received by chartered accountants and fraud examiners underpinned the quality of the approach in capturing highly relevant accounting anomalies.

**The publication is available via arXiv under the following link:** https://arxiv.org/abs/1709.05254
