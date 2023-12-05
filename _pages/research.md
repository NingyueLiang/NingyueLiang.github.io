---
permalink: /research/
title: "Research"
author_profile: true
---
## *One for All: Towards Training One Graph Model for All Classification Tasks*

Paper: [https://arxiv.org/abs/2310.00149](https://arxiv.org/abs/2310.00149)

Authors: Hao Liu, Jiarui Feng, Lecheng Kong, Ningyue Liang, Dacheng Tao, Yixin Chen, Muhan Zhang

[Github URL](https://github.com/NingyueLiang/OneForAll)

![OFA Pipeline ](../images/ofapipeline.png)

OFA is a general Graph Classification Framework that can solves a wide range of graph classification tasks with a single model and a single set of parameters. The tasks are cross-domain (e.g. citation network, molecular graph,...) and cross-tasks (e.g. few-shot, zero-shot, graph-level, node-leve,...)

OFA use natural languages to describe all graphs, and use a LLM to embed all description in the same embedding space, which enable cross-domain training using a single model.

OFA propose a prompting paradiagm that all task information are converted to prompt graph. So subsequence model is able to read tasks information and predict relavent target accordingly, without having to adjust model parameters and architecture. Hence, a single model can be cross-task.

OFA curated a list of graph datasets from a different sources and domains and describe nodes/edges in the graphs with a systematical decription protocol. We thank previous works including, [OGB](https://ogb.stanford.edu/), [GIMLET](https://github.com/zhao-ht/GIMLET/tree/master), [MoleculeNet](https://arxiv.org/abs/1703.00564), [GraphLLM](https://arxiv.org/pdf/2307.03393.pdf), and [villmow](https://github.com/villmow/datasets_knowledge_embedding/tree/master) for providing wonderful raw graph/text data that make our work possible.

##  *Advanced Astrophysics Telescope Program at Washington University in St. Louis*

Developed with a team of 6 to build a localization pipeline in C++ with an OOP design for GRB detection in the telescope

Optimized the localization algorithm with ML-driven techniques by experimenting with 40+ regression models (e.g. k-NN, CNN, SVM) and improved its accuracy by 30%, achieving less than 1.5 degrees of error for 10k+ trial evaluations

Implemented a comprehensive machine learning infrastructure with Python and TensorFlow, including data loading, cleaning, normalization, training, and serving, efficiently managing 70 million data rows from end to end
