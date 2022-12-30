# ELMED219: Artificial intelligence and computational medicine

<p>

[<img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg">](https://deepnote.com/launch?url=https%3A%2F%2Fgithub.com%2Fmmiv-ml%2FELMED219) &nbsp; [![kaggle](https://camo.githubusercontent.com/a08ca511178e691ace596a95d334f73cf4ce06e83a5c4a5169b8bb68cac27bef/68747470733a2f2f6b6167676c652e636f6d2f7374617469632f696d616765732f6f70656e2d696e2d6b6167676c652e737667)](https://www.kaggle.com/alexanderlundervold/code) &nbsp;  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/ELMED219/blob/main/) &nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MMIV-ML/ELMED219/HEAD) &nbsp; [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/MMIV-ML/ELMED219/tree/main/)
</p>

The [course](https://www.uib.no/en/course/ELMED219) is offered by the [Department of Biomedicine](https://www.uib.no/biomedisin) in collaboration with the [Machine Learning Engineering group](https://github.com/HVL-ML) at the [Department of Computer science, Electrical engineering, and Mathematical sciences](https://www.hvl.no/en/about/management/faculty-of-engineering-and-science/department-of-computer-science-electrical-engineering-and-mathematical-sciences-ny-side), Western Norway University of Applied Sciences, and the Medical AI group at [Mohn Medical Imaging and Visualization Center](https://mmiv.no/).

<img src="./assets/elmed219_logo.png" width="700"> <br>


During the course, you will gain insight into computationally oriented thinking, machine learning, and artificial intelligence and an understanding of the pros and cons of AI for the future of medicine. The course provides a guided tour through some biomedical and clinical applications of mathematical and statistical modeling techniques, as well as principles for selected sensors and measuring instruments in research and clinical practice.


We meet concepts such as **big data**, **data analysis**, **machine learning**, and **artificial intelligence (AI)**, with examples from personalized and predictive medicine. You will use methods and tools from numerical programming, data analysis, and "scientific computing" for medical applications, and learn about the importance of **open science**, **data sharing**, **reproducible research**, and **ethics by/in/for design** [[link](https://ec.europa.eu/info/funding-tenders/opportunities/docs/2021-2027/horizon/guidance/ethics-by-design-and-ethics-of-use-approaches-for-artificial-intelligence_he_en.pdf)]

:point_right: This repository contains most of the course material. Students enrolled in the course will also find some practical information at [MittUiB](https://mitt.uib.no/courses/33274).

:eyes: A presentation and reflection on the course (presented for the "**Kunstig intelligens i norsk helsetjeneste** ([KIN](https://ehealthresearch.no/kin))" network meeting, February 8th, 2022) can be found [here](https://docs.google.com/presentation/d/e/2PACX-1vQ2goLSZsIjeCQrjUnA4lfnXe2wgsgDpUXWe8be4K_pTqo4OD9qELxDlJyKknYVdCjJ34-Q4gcu-yYx/pub?start=false&loop=false&delayms=3000).

:question: For **academic questions** about the course, contact course coordinator [Arvid Lundervold](https://www.uib.no/en/persons/Arvid.Lundervold) (UiB) or [Alexander S. Lundervold](https://www.hvl.no/en/employee/?user=Alexander.Selvikvag.Lundervold) (HVL).

:question: For **practical or administrative inquiries**, contact the Studies Section at the Department of Biomedicine at studie.biomed@uib.no


<img src="./assets/cc_by_sa.png" width="75"> The content for the course is offered with a <b><a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a></b> license unless otherwise stated.


--------

# Tentative time schedule


| **TIME**                    | ACTIVITY                                                                                |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mon, Jan 2** |                                                                                               |
| On your own                 | Get an overview of the course; installation of software and/or test out Google Colab                                                                                                                                                                                                                                                                       |
|                             | Follow the instructions at [MittUiB](https://mitt.uib.no/courses/40381)                                                                                                                                                                                                                                                                  |
| **Tue, Jan 3**          |                                                                                                                                                                                        |
| 09:15-12:00             | About the course / Motivation lectures<br>&nbsp;Computational medicine<br>&nbsp;Medical AI     |
|                             | *Arvid Lundervold / Alexander Selvikvåg Lundervold*   |                                                                                                                                                                                                                                                                                                                          |
| **Wed, Jan 4**          |                                                                                                                                                                                                                                                                             |
| 12:15-14:00                 | Tools, teams and [project](./Project/) work                                                                                                              |
|                             | *Arvid Lundervold / Alexander Selvikvåg Lundervold*                                                                                                                                                                                                                                                                                                       |
| **Thu, Jan 5**          |                                                                                                                                                                                                                                                                                                                                                   |
| 09:15-11:00                 | [LAB 0: Introduction to theory and tools for machine learning](./Lab0-ML/)                                                                                                                                                                                                                                                                                                  |
|                             | *Alexander Selvikvåg Lundervold*                                                                                                                               |
| 11:30-13:00                 |  [LAB 1: Brain imaging (mpMRI) in glioblastoma](./Lab1-mpMRI-glioblastoma/)                                                                                                                                                                                                                                                                                       |
|                             |   *Arvid Lundervold*                                                                                                                                                                        |
|                             |                                                                                                                                                                             |
| **Jan 6&ndash;15**  |                                                                                                                                                                              |
| On your own                 | You'll spend approximately four hours completing at least one DataCamp course (remember to use the link on MittUiB for free access to DataCamp). The rest of the week, you'll work on your course projects. Which DataCamp course you're encouraged to do depends on your previous programming experience:<br><br>- No Python programming experience? Complete the course [Introduction to Python](https://learn.datacamp.com/courses/intro-to-python-for-data-science)<br>- Know some Python, but no machine learning? Complete the course [Supervised Learning with scikit-learn](https://learn.datacamp.com/courses/supervised-learning-with-scikit-learn)<br>- Know the fundamentals of machine learning in Python? Can you pass the *Machine Learning Fundamentals Assessment*? Complete the course [Biomedical Image Analysis in Python](https://learn.datacamp.com/courses/biomedical-image-analysis-in-python) |                                                                                                                       
| **Mon, Jan 16**         |                                                                                                                                                                                                                                                                |
| 10:15-12:00                 | [Lab 2: Machine Learning Engineering in Medicine](./Lab2-MedML/)                                                                                                                                                                                                                                                                 |
| **Fri, Jan 20**         |                                                                            
| 13:15-16:00                 | [Lab 3: Deep Learning](./Lab3-DL/) |
| **Mon, Jan 23**         |                                                                                                                                                                                                                                                                      |
| 13:15-16:00                 | Project Presentations <br> Perspectives on Medical AI and the Future of Medicine|                                                                                  |
|**Fri, Jan 27** | 
||**Home exam**; Duration: 2 hours;  Assignment is handed out: 27.01.2023, 09:00; Submission deadline: 27.01.2023, 11:00; Examination system: Inspera Digital exam
