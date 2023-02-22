---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
Ph.D. in Computer Science, University of California, Irvine
* August 2022 - August 2027
* Advisor: Prof. [Nalini Venkatasubramanian](https://nalini.ics.uci.edu/)

M.S. in Computer Science, San Diego State University 
* August 2020 - August 2022
* Advisor: Prof. [Shangping Ren](https://icip.sdsu.edu/memberProfile/shangping.html)
* Thesis: PACE: Preventing Attacks on Case Identities in event logs through data generalization

B.S. in Computer Science, Western Governors University
* August, 2018 - May, 2020
* Capstone: Differential Privacy Engine using randomized response

Research Interests
======
Data Privacy 

Internet of Things

Process Mining 

Research experience
======
Graduate Student Researcher with a focus on Data Privacy in the [Distributed Systems and Middleware group](https://www.ics.uci.edu/~dsm/members.html) at the University of California, Irvine (2022 - Present).
  * Member of the NSF-funded [Smart WAter Data Exchange (SWADE) project](https://sites.uci.edu/swade/).
    * Focused on privacy issues in water infrastructure.
  * Investigating composition of privacy techniques in smart meter and infrastructure systems.
  * Working with a smart sprinkler company to develop a recommendation system for irrigation usage.
  * Applying Homomorphic Encryption to Meter Readings based on user-policy to metered environments.
  
Graduate Student Researcher with a focus on Privacy in Process Mining in the [Integrating Cyber Innovations within the Physical World lab](https://icip.sdsu.edu/) at San Diego State University.
  * Investigated generalizable privacy schemes within workflows and created the [PMDG: Privacy for Multi-perspective Process Mining through Data Generalization framework](https://github.com/Ryanhilde/PMDG_Framework).
  * Conducted [experiments for finding better bounds of Quasi-Identifiers](https://github.com/Ryanhilde/min_set_cover) in the [K-Anonymity selection problem](https://arxiv.org/abs/2211.13882).
  * Developed a framework for generalizing attribute values based on semantic properties within organization workflows and measured the results using various unsupervised machine learning techniques.
  * Conducted experiments for anomaly detection in mainstream process behavior using clustering techniques.
  * Created synthetic event logs for experiments for filtering mainstream behavior of event logs.

Work experience
======
Quality Control Manager, New Patient Machine (October 2018 - November 2022)
  * Oversaw and Managed the creation of Facebook and Google Ad campaigns for 40 clients.
  * Used Facebook Ad Manager and Google Ad Suite to create customized ad campaigns based on clients specifications. Campaigns included creating multiple webpages, incorporating unique targeting strategies, managing and creating APIs to pull collected data, database access, and automation.

Digital Media & Communications, Paiste America, Inc. (April 2016 - October 2018)
  * Worked with an internal team to create digital media content. Oversaw a network across three countries and handled system admin responsibilities.
  * Created and published digital content that received millions of views. 
  
Projects
======
Applying Homomorphic Encryption to Meter Readings based on user-policy to metered environments (February 2023).
* Created a simulated metering environment using Google's Pub/Sub infrastructure to connect to a Big Query database and publish encrypted meter readings. Encryption is based on a homorphic encryption scheme and data is encrypted from a pre-defined user policy. User policies define membership groups for the generated meter stream and the rate at which data is collected.  

[Python Data Structures and Algorithms repo](https://github.com/Ryanhilde/DS_and_Algs) (December 2022).
* This is a data repo for common algorithms and data structures in python. It is mostly for my own personal use, but I have made it available for anyone looking to implement an algorithm.

[Experiments and Implementation of 'Towards Better Bounds for Finding Quasi-Identifiers](https://github.com/Ryanhilde/min_set_cover/tree/main) (November 2022).
* Experiments across three large datasets to verify and show the accuracy of improved bounds for the NP-Hard problem of selecting optimal attributes for k-anonymity. Paper is in publication review.

[Privacy for multi-perspective Process Mining through data generalization](https://github.com/Ryanhilde/PMDG_Framework) (November 2022).
* Framework for applying K-anonymity to organizational attributes in an event log using generalization and hierarchical trees. The code is applied to two event logs and performance metrics are detailed for machine learning experiments using decision trees and handover graphs.

[Master's Thesis: PACE (Preventing Attacks on Case Identities in event logs through data generalization)](https://github.com/Ryanhilde/PACE_Framework) (May 2022).
* Repo for my Master's Thesis work that applies K-anonymity to organizational attributes in an event log using generalization and hierarchical trees.

[Detecting Pokemon Types Using a Variety of Data Mining and Machine Learning Techniques](https://github.com/Ryanhilde/sdsu_data_mining_project) (April 2021).
* A measurement study on the precision, recall, and F1-score of various machine learning methods using the [Pokemon dataset](https://www.kaggle.com/datasets/rounakbanik/pokemon) on kaggle to predict a Pokemon's type. Techniques include a neural network, support vector machine, KNN-model, Naive Bayes, and Decision Tree Classifier.

[Maze Builder and Solver using various graph traversal methods](https://github.com/Ryanhilde/AI_Club_Maze_Builder) (December 2020).
* This project was built for the San Diego State University's Artificial Intelligence club during the Fall semester of 2020. I lead a team of two undergraduates to build a maze generation application using different search traversal techniques.

[Bachelor's Capstone: Differential Privacy Engine](https://github.com/Ryanhilde/WGU-C964-Capstone) (May 2020).
* A GUI Python implementation of random-response differential privacy where a user can input a dataset and specify sensitive attributes.

Skills
======
Systems: Windows Server Suite

Databases: Oracle SQL Suite, Google Big Query

Tools: Jupyter Notebook, Vim, AWS, Google Cloud

Languages: Python, Java, Scala, C++, Latex, Bash


  
Certifications and Activities
======
University of California, Irvine DECADE Representative (January 2023)

San Diego State University Student Lecturer (August 2021 - August 2022)

San Diego State University Artificial Intelligence Club Project Leader (August 2020)

Stanford Machine Learning Certification – Coursera (July 2020)

Oracle Database SQL Certification - 1Z0-071 (May 2020)

CompTIA Project + - PKO-004 (February 2019)

CIW Site Development Associate (January 2019)

ITIL Foundations Certificate (September 2018)

Microsoft Networking Fundamentals Certification - MSA 98-366 (May 2017)

Achievements
======
First in my immediate family to finish an undergraduate and graduate degree. 

University of California, Irvine Dean's Award Scholarship (2022).

San Diego State University Dean's List (August 2020 - May 2022).

Participated in Becton Dickinson’s 2021 summer Lunch & Learn program as a guest speaker.

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
