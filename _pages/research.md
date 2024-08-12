---
permalink: /research/
title: "Research"
author_profile: true
---
## *One for All: Towards Training One Graph Model for All Classification Tasks* 
## Accepted for ICLR 2024 Spotlight presentation (top 5%)

Paper: [https://openreview.net/forum?id=4IT2pgc9v6](https://openreview.net/forum?id=4IT2pgc9v6)

Authors: Hao Liu, Jiarui Feng, Lecheng Kong, Ningyue Liang, Dacheng Tao, Yixin Chen, Muhan Zhang

[Github URL](https://github.com/NingyueLiang/OneForAll)

![OFA Pipeline ](../images/ofapipeline.png)

OFA is a general Graph Classification Framework that can solves a wide range of graph classification tasks with a single model and a single set of parameters. The tasks are cross-domain (e.g. citation network, molecular graph,...) and cross-tasks (e.g. few-shot, zero-shot, graph-level, node-leve,...)

OFA use natural languages to describe all graphs, and use a LLM to embed all description in the same embedding space, which enable cross-domain training using a single model.

OFA propose a prompting paradiagm that all task information are converted to prompt graph. So subsequence model is able to read tasks information and predict relavent target accordingly, without having to adjust model parameters and architecture. Hence, a single model can be cross-task.

OFA curated a list of graph datasets from a different sources and domains and describe nodes/edges in the graphs with a systematical decription protocol. We thank previous works including, [OGB](https://ogb.stanford.edu/), [GIMLET](https://github.com/zhao-ht/GIMLET/tree/master), [MoleculeNet](https://arxiv.org/abs/1703.00564), [GraphLLM](https://arxiv.org/pdf/2307.03393.pdf), and [villmow](https://github.com/villmow/datasets_knowledge_embedding/tree/master) for providing wonderful raw graph/text data that make our work possible.

##  *Advanced Astrophysics Telescope Program at Washington University in St. Louis*

Developed with a team of 6 to build a real-time localization system in C++ with object-oriented designs for GRB detections

Implemented reconstruction and localization algorithms with Compton formulas to handle energy data processed by FPGAs

Built an end-to-end ML infrastructure with Python and TensorFlow for preprocessing, training, and serving with 70M data

Optimized the localization pipeline by training and tuning with 40+ versions of regression models (including KNN, ANN, SVM, RF, and XGBoost), and improved its accuracy by 30%, achieving less than 1.5 degrees of error for 10k+ trials



