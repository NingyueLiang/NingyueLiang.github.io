---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Ningyue Liang is a senior undergraduate student double majoring in Computer Science and Statistics at Washington University in St. Louis. His profound interest in machine learning, AI, and software engineering, coupled with his industrial experience and academic achievements, marks him as an emerging professional equipped to face and solve complex technological challenges.

## Research

### *One for All: Towards Training One Graph Model for All Classification Tasks*

Paper: [https://arxiv.org/abs/2310.00149](https://arxiv.org/abs/2310.00149)

Authors: Hao Liu, Jiarui Feng, Lecheng Kong, Ningyue Liang, Dacheng Tao, Yixin Chen, Muhan Zhang

[Github URL](https://github.com/NingyueLiang/OneForAll)

![OFA Pipeline ](../images/ofapipeline.png)

OFA is a general Graph Classification Framework that can solves a wide range of graph classification tasks with a single model and a single set of parameters. The tasks are cross-domain (e.g. citation network, molecular graph,...) and cross-tasks (e.g. few-shot, zero-shot, graph-level, node-leve,...)

OFA use natural languages to describe all graphs, and use a LLM to embed all description in the same embedding space, which enable cross-domain training using a single model.

OFA propose a prompting paradiagm that all task information are converted to prompt graph. So subsequence model is able to read tasks information and predict relavent target accordingly, without having to adjust model parameters and architecture. Hence, a single model can be cross-task.

OFA curated a list of graph datasets from a different sources and domains and describe nodes/edges in the graphs with a systematical decription protocol. We thank previous works including, [OGB](https://ogb.stanford.edu/), [GIMLET](https://github.com/zhao-ht/GIMLET/tree/master), [MoleculeNet](https://arxiv.org/abs/1703.00564), [GraphLLM](https://arxiv.org/pdf/2307.03393.pdf), and [villmow](https://github.com/villmow/datasets_knowledge_embedding/tree/master) for providing wonderful raw graph/text data that make our work possible.

###  *Advanced Astrophysics Telescope Program at Washington University in St. Louis*

Developed with a team of 6 to build a localization pipeline in C++ with an OOP design for GRB detection in the telescope

Optimized the localization algorithm with ML-driven techniques by experimenting with 40+ regression models (e.g. k-NN, CNN, SVM) and improved its accuracy by 30%, achieving less than 1.5 degrees of error for 10k+ trial evaluations

Implemented a comprehensive machine learning infrastructure with Python and TensorFlow, including data loading, cleaning, normalization, training, and serving, efficiently managing 70 million data rows from end to end

## Internship 

###  Impossible Sensing, LLC, Software Engineer Intern                                                                                 

*June 2023 – July 2023; St. Louis, MO*

Skills: Python, C++, REST API, Django, Flask, React.JS, OOP, PostgreSQL, AWS 			              

Collaborated with a team of 5 to build up optical sensing software for NASA projects with backend infrastructure and data 
storage systems using Django, PostgreSQL, and deployed to the AWS cloud with Docker intended for 1k+ users

Designed PostgreSQL schemas to effectively manage sensing data and developed an ETL pipeline with a 2 TB AWS RDS
database to synchronize local database records for replication purposes

Created the front-end interface with React.JS and Tailwind CSS, and enabled interactive data visualizations using Dash

Designed and developed full-flown backend services using the Django MVT framework and REST APIs for record
management (CRUD functions, data processing, etc.) and enabled camera image collection with OpenCV 

Ensured stable inter-process communication by building Flask asynchronous APIs for delay generators and optimized
timing control accuracy by 35% at the millisecond level

###  Sobriety Hub, LLC, Software Engineer Intern   

*May 2022 – Sept. 2022; St. Louis, MO*

[Project URL](https://github.com/NingyueLiang/SobrietyHub)

Skills: Next.JS, React.JS, REST API, PostgreSQL, OOP, AWS                                                                                             

Developed an operating management application for sober living homes and launched the web app with over 500 users

Created a PostgreSQL DB and built file uploading functions with AWS EC2 & S3 for operation management and analysis

Built Next.JS async APIs and Prisma models to support event planning, rent payment, and operating analysis functions

Implemented responsive UI design and data visualizations with React, D3.JS, and Chakra-UI, resulting in 30% more visits

### Roke Data Co., Ltd., Software Engineer Intern                                                                                          

* May 2021 – July 2021; Jinan, China *
  
Skills: React.JS, Python, REST APIs, Odoo, PostgreSQL, D3.JS 

Developed an enterprise resource planning app for China Construction 8th Division with 10+ colleagues from Inspur

Designed a database in PostgreSQL to store project planning information, including locations, resources, and status 

Built non-blocking REST Python APIs to support resource planning functions and data analysis of construction projects

Created an interactive visualization application in D3.JS to show 30+ projects’ progress, locations, and remaining resources

## Project

### [1. Mirror iOS App](https://github.com/NingyueLiang/Mirror-iOS-App)

(Accepted by App Store, not published)
Introducing Mirror, the AI Interviewer App, powered by GPT and designed to help you ace your next interview! With Mirror, you can get a realistic mock practice of real interview questions, and receive real-time feedback from artificial intelligence on your performance. Mirror tracks your performance history, allowing you to see your progress and stay motivated. It’s a comprehensive tool that gives you everything you need to prepare for your interview with confidence.

### [2. Global Emissions Data Analysis & Interactive Visualizations](https://github.com/NingyueLiang/Emssions) 

Data Analysis & Interactive Visualizations on 30 years green house gas emissions for all countries in the world through D3.JS.


###  [3. EDUrain](https://github.com/NingyueLiang/EDUrain)
EDUrain is a platform dedicated to helping every student attend college. We help students file for scholarships for free, and offer a free housing search through our housing engine. Additionally, we’ve built into our platform other services to make the student’s life easier, including renter’s insurance, credit building, and roommate matching! We’re constantly improving our website as we build our startup, so look out for new features that are on the way!

## Teaching
I have worked as a teaching assistant for 7 Computer Science Courses and engineering tutor at Washington University in St. Louis:

CSE247 DATA STRUCTURES AND ALGORITHMS \
CSE204 WEB DEVELOPMENT \
CSE217 INTRODUCTION  TO DATA SCIENCE \
CSE330S RAPID PROTOTYPE DEVELOPMENT AND CREATIVE PROGRAMMING \
CSE332S OBJECT-ORIENTED SOFTWARE DEVELOPMENT LABORATORY \
CSE361S INTRODUCTION TO SYSTEMS SOFTWARE \
CSE438S MOBILE APPLICATION DEVELOPMENT 

## Tech Stack

<br>
<table>
<tbody>

<tr>
  <td align="center" width="20%">
  <span><b><center>Java</center></b></span> 

  </td>
  
  <td align="center" width="20%">
  <span><b><center>Python</center></b></span> 
  </td>
  
  <td align="center" width="20%">
  <span><b><center>C++</center></b></span> 

  </td>

</tr>

<tr>
  <td align="center" width="20%">
  <span><b><center>ReactJS</center></b></span> 

  </td>

  <td align="center" width="20%">
  <span><b><center>Django</center></b></span> 

  </td>

  <td align="center" width="20%">
  <span><b><center>Spring</center></b></span> 
  
  </td>
  
</tr>  

<tr>
  <td align="center" width="20%">
  <span><b><center>PyTorch</center></b></span> 

  </td>
  
  <td align="center" width="20%">
  <span><b><center>TensorFlow</center></b></span> 

  </td>
  

  <td align="center" width="20%">
  <span><b><center>SQL</center></b></span> 
 
  </td>
  

</tr>

<tr>
  <td align="center" width="20%">
  <span><b><center>JavaScript</center></b></span> 
  
  </td>
  
  <td align="center" width="20%">
  <span><b><center>Swift</center></b></span> 
  
  </td>
  

  <td align="center" width="20%">
  <span><b><center>Golang</center></b></span> 
  
  </td>
  

</tr>

<tr>
  <td align="center" width="20%">
  <span><b><center>Git</center></b></span> 
  
  </td>
  
  <td align="center" width="20%">
  <span><b><center>Linux</center></b></span> 

  </td>

  <td align="center" width="20%">
  <span><b><center>Docker</center></b></span> 

  </td>

</tr>

</tbody>
</table>

