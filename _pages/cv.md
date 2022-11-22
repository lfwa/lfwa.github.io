---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

CV. Last updated: Nov 2022. ([download](../files/cv.pdf))

Education
======
**ETH Zürich**\
*MSc ETH in Computer Science*, Sep 2020 &ndash; Mar 2023 (expected)

**University of Copenhagen**\
*BSc in Computer Science*, Sep 2017 &ndash; Jun 2020

**University of California, Merced**\
*BSc Exchange Study in Computer Science*, Aug 2019 &ndash; Dec 2019

Experience
======
**University of Copenhagen**\
*Teaching Assistant*, Feb 2020 &ndash; Jul 2020
* TA for the course Data Science (2019/2020): Databases, introduction to machine learning and data science with an emphasis on natural language processing and data pipelines.
* Main duties included organizing and teaching of lab sessions.

**Nykredit**\
*Software Developer*, Oct 2018 &ndash; Jan 2020
* Part of an agile C\#-development team using Scrum and Kanban at one of Denmark's leading financial institutions.
* Developed and maintained financial software for mortgage loans in .NET Framework significantly reducing time spent by in-house financial advisors to process and evaluate loan applications.
* Developed and maintained a web-based ASP.NET tool for ensuring compliance across all of Nykredit IT with the data protection and privacy law GDPR.
* Lead the effort to set up a continuous deployment pipeline using a Jenkin CI server integrated with BitBucket completely eliminating manual work associated with integration testing and deployment.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Highlighted projects
======
**Carbontracker**\
[github.com/lfwa/carbontracker](https://github.com/lfwa/carbontracker)\
Open-source tool released under the MIT license for tracking and predicting the energy consumption and carbon emissions of training deep learning models in Python. Corresponding publication [arXiv](https://arxiv.org/abs/2007.03051). It has been downloaded $>$$55$k times on the Python Package Index (PyPI) as of writing.

**Reinforced Graph Neural Networks for Collaborative Filtering**\
[github.com/lfwa/reinforced-gnn](https://github.com/lfwa/reinforced-gnn)\
Introduced a novel architecture to generate predictive compatibility scores for never-before-seen content in recommendation systems. The architecture combines the strength of graph-extracted embeddings in a graph neural network with the generalization power of a deep feed-forward network and adds "reinforcements" providing additional information to the network.

**Static Taint Analysis For Ethereum Contracts**\
[github.com/lfwa/reinforced-gnn](https://github.com/lfwa/reinforced-gnn)\
Designed and implemented a static taint analyzer in Datalog for Ethereum smart contracts. The analyzer detects vulnerable contracts that may be deleted from the blockchain and have all remaining cryptocurrency transferred to an untrusted address.

**Supporting Alternative SMT Solvers in Viper**\
[github.com/viperproject](https://github.com/viperproject)\
Added support for multiple SMT solvers, such as cvc5, in the symbolic-execution based automated verification backend written in Scala for the program verification tool chain and infrastructure, Viper.

Relevant coursework
======
| Machine Learning & Big Data    | Mathematics                     | Software Engineering                                 |
| ------------------------------ | ------------------------------- | ---------------------------------------------------- |
| Advanced Machine Learning      | Statistics & Probability Theory | Program Verification                                 |
| Causal Representation Learning | Discrete Mathematics            | Program Analysis for System Security and Reliability |
| Natural Language Processing    | Linear Algebra                  | Concepts of Object-Oriented Programming              |
| Probabilistic AI               | Modelling & Analysis of Data    | Computer & Network Security                          |
| Reliable & Trustworthy AI      | Algorithms & Data Structures    |                                                      |
| Computational Intelligence     | Randomized Algorithms           |                                                      |
| Big Data                       |                                 |                                                      |

Skills
======
**Programming Languages**
* Python, C#, SQL, Rust, Scala, F#, Java, C, Datalog

**Databases**
* PostgreSQL, Oracle

**Frameworks and Tools**
* PyTorch, TensorFlow, Gym(nasium), scikit-learn, NumPy, pandas, Matplotlib, Git, Spark, Hadoop, Neo4j
