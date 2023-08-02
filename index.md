---
title: Artificial Intelligence and Machine Learning
description: ENGCE178 ปัญญาประดิษฐ์และการเรียนรู้ของเครื่อง <br><br> วิศวกรรมคอมพิวเตอร์ มหาวิทยาลัยเทคโนโลยีราชมงคลล้านนา
layout: default
---
{% comment %} 
  This will not show

<div class="course-announcements">
  <h2 id="announcements">Announcements</h2>
  <ul>
    <li><a href="">/placeholder</a></li>
  </ul>
</div>
{% endcomment %} 

## General Info
- ผู้สอน: อ.ปรัชญ์ ปิยะวงศ์วิศาล (Pratch Piyawongwisal)
- วิชาบังคับก่อน: โครงสร้างข้อมูลและขั้นตอนวิธี
- ควรเรียนมาก่อน: 
  - ความน่าจะเป็นและสถิติในงานวิศวกรรม 
  - วิยุตคณิตศาสตร์  


### Course Description

ศึกษาและปฏิบัติการเกี่ยวกับ 
- **AI:** นิยามของปัญญาประดิษฐ์ ปัญหาพื้นฐานของปัญญาประดิษฐ์ การเข้าใจภาษามนุษย์ การประมวลผลภาพ การควบคุมหุ่นยนต์ ระบบผู้เชี่ยวชาญการแทนความรู้ การค้นหา การอนุมาน และการใช้ Heuristic การแก้ปัญหาเชิงปัญญาประดิษฐ์ 
- **Machine Learning:** การเรียนรู้ของเครื่องและทฤษฎีการเรียนรู้ การเรียนรู้แบบมีผู้สอน  การแบ่งประเภท  การถดถอย ค่าผิดปกติ ซัพพอร์ตเวกเตอร์แมชชีน การเลือกแบบจำลองและคุณลักษณะ การลดขนาดมิติของข้อมูล ต้นไม้ตัดสินใจ การเรียนรู้แบบไม่มีผู้สอน การจัดกลุ่ม การเรียนรู้แบบเสริมกำลัง ข่ายงานประสาทเทียม การเรียนรู้เชิงลึก 

### Tools
- Language: Python
- Library: Anaconda Package (Numpy, Jupyter, Scikit-Learn, TensorFlow)

### Lectures

| Section | Room | Time | 
| --- | --- | --- |
| 1 | ทค.2-201 | อ 12:00-17:00 |

{% comment %} 


### Assignments

| Homework | Due |
| --- | --- | 
| **Homework 1** จงทำ linear regression กับข้อมูลชุดเดิมกับในแล็บ แต่เปลี่ยนจากวิธีคำนวณสูตร Normal Equation เอง ไปใช้ library ของ scikit-learn แทน โดยทำใน Jupyter แล้วรันให้เห็นผล โดยอ้างอิงจาก: http://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html  | 19 ส.ค. 2561 | 
| :exclamation: **Homework 2** จงใช้โมเดล decision tree เพื่อทำนายการเลือก major ของนักศึกษาโดยพิจารณาจากข้อมูลเกรดในแต่ละหมวดหมู่วิชาของนักศึกษา อ่านรายละเอียดได้ที่ท้าย [สไลด์ Decision Tree](6%20-%20Decision%20Tree.pdf) ดาวน์โหลดข้อมูล: [student_training.csv](data/student_training.csv), [student_scoring.csv](data/student_scoring.csv) | 23 ก.ย. 2561 |

{% endcomment %} 


### Slides

| Week # | Topics |
| --- | --- | 
| 0 | [Course Overview](slides/0-overview.pdf), Math Review |
| 1 | [Introduction to AI, ML](slides/1-intro.pdf), Python Basics |
| 2 | [Supervised Learning](slides/2-supervised.pdf) |
| 3 | [k-Nearest Neighbors](slides/3-knn.pdf)|
| 4 | [Model Selection](slides/4-model-selection.pdf) |
| 5 | [Linear Regression, Gradient Descent](slides/5-linear-regression.pdf) | 
| 6 | [Logistic Regression](slides/6-logistic-regression.pdf) |
| 7 | [Support Vector Machines (SVM)](slides/7-svm.pdf) |
|   | [In-class: Math behind SVM](slides/svm-math.pdf) |
|   | [Supplement Reading: User's Guide to SVM](http://pyml.sourceforge.net/doc/howto.pdf) |
|   | Midterm | 
| 8 | [Decision Tree](slides/8-decision-tree.pdf)|
| 9 | [Ensemble Learning](slides/9-decision-tree-ensemble.pdf)|
| 10 | [Neural Networks, Deep Learning](slides/10-neural-networks.pdf) |
| 11 | CNN, RNN |
|    | Slides: [CS231n@Stanford](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture5.pdf) |
| 12 | [Advanced Topics on DL, NLP](slides/13-advanced-topics.pdf) |
| **Classical AI** ||
| 13 | [Search (State-based Models)](slides/12-search.pdf) |
|    | (Adapted from [UC Berkeley CS118](http://ai.berkeley.edu/slides/Lecture%202%20--%20Uninformed%20Search/SP14%20CS188%20Lecture%202%20--%20Uninformed%20Search.pptx)) |
| 14 | Adversarial Search, Minimax, alpha-beta pruning|
| 15 | [Future Topics](slides/14-future-topics.pdf) |

{% comment %}
|   | [UC Berkeley CS188 - Uninformed Search](http://ai.berkeley.edu/slides/Lecture%202%20--%20Uninformed%20Search/SP14%20CS188%20Lecture%202%20--%20Uninformed%20Search.pptx) |
|   | [UC Berkeley CS188 - Informed Search](http://ai.berkeley.edu/slides/Lecture%203%20--%20Informed%20Search/SP14%20CS188%20Lecture%203%20--%20Informed%20Search.pptx) |
|   | [Chiang Mai U 204471 slides](http://www.cs.science.cmu.ac.th/course/204471/lib/exe/fetch.php?media=04_searching_01_uninformed.pdf) |
|   | [Exercise](http://ai.berkeley.edu/sections/section_0_v55LOfoUUwiW1k6Nchnk3Dw6WQuTW8.pdf) |
|   | [Exercise 2](https://inst.eecs.berkeley.edu/~cs188/fa18/assets/hw/CS_188_Fall_2018_Written_HW1.pdf) |
{% endcomment %}

{% comment %}

|   | [Natural Language Processing](slides-2018/8%20-%20NLP.pdf) |
| 10 | [Final Review]() |
| **Future** | |
| 10 | Dynamic Programming | 
| 11 | Knowledge Representation | 
| 12 | Logic |
|   | First-Order Logic, Propositional Logic, Inference | 
| 13 | Adversarial Search, Game Playing, Minimax, eval func, alpha-beta pruning |

{% endcomment %}

### Textbooks
- [Hands-On Machine Learning with Scikit-Learn & TensorFlow](https://www.amazon.com/_/dp/1491962291?tag=oreilly20-20) by Aurélien Géron
- [Deep Learning with Python](https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438) by Francois Chollet
- [An Introduction to Statistical Learning: with Application in R](https://www.amazon.com/Introduction-Statistical-Learning-Applications-Statistics/dp/1461471370) by Gareth James et al.

### Links
- [CS229@Stanford](https://www.youtube.com/watch?v=UzxYlbK2c7E&list=PLA89DCFA6ADACE599)
- [CS231n@Stanford](http://cs231n.stanford.edu/)
- [Chris Olah's Blog](https://colah.github.io/)
- [Coursera DL Specialization](https://www.coursera.org/specializations/deep-learning)

