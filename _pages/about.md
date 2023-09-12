---
permalink: /
title: "Nima Shoghi"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

About me
======
I am an AI researcher with a background in computer science and machine learning. I received my B.S. and M.S. in Computer Science from Georgia Tech, where I worked on a variety of projects in the fields of machine learning, high-performance computing, and cyber security. I recently concluded my two-year AI residency at Meta AI's FAIR Chemistry team, where I worked on developing large pre-trained models, trained on a large mixture of available chemical data across multiple different domains, for general-purpose chemical property prediction. I am particularly interested in the application of large-scale machine learning techniques to problems in science and engineering.

My CV is available [here](files/cv.pdf).

Education
======
* M.S. with *Highest Honors* in Computer Science (Machine Learning Specialization), **Georgia Institute of Technology**, Jan 2020 - May 2021
* B.S. with *High Honors* in Computer Science (Machine Learning and Devices Threads), **Georgia Institute of Technology**, May 2015 - Dec 2019
* International Baccalaureate Diploma, **Druid Hills High School**, Aug 2011 - May 2015

Work experience
======
* AI Resident at **[Meta Fundamental AI Research (FAIR)](https://ai.meta.com/research/)**, Aug 2021 - Aug 2023
  * Worked on the [Open Catalyst Project](https://opencatalystproject.org/index.html) on the FAIR Chemistry team, focusing on the development of large-scale pre-training methods for chemical property prediction.
  * Advisors: [Dr. Larry Zitnick](http://larryzitnick.org/) and [Dr. Abhishek Das](https://abhishekdas.com/)

* Research Assistant at **High Performance Computer Architecture Lab at Georgia Tech**, May 2019 - May 2021
  * Developed software-level and hardware-level techniques for accelerating deep learning training and inference.
  * Advisors: [Dr. Hyesoon Kim](https://www.cc.gatech.edu/~hyesoon/) and [Dr. Moinuddin Qureshi](https://www.cc.gatech.edu/~mqureshi/)

* Graduate Teaching Assistant at **Georgia Institute of Technology**, Aug 2020 - May 2021
  * CS 4510: Automata and Complexity, Fall 2020
  * CS 4510: Automata and Complexity, Spring 2021

* Student Research Assistant at the **Cyber Forensics Innovation (CyFI) Lab at Georgia Tech**, Jan 2020 - Aug 2020
  * Developed GNN-based ML models to analyze social media data for detecting incoming cyber attacks.
  * Advisor: [Dr. Maria Konte](https://mkonte.github.io/)

* Software Engineering Intern at **Ciena**, May 2017 - May 2018
  * Developed software to interface with network devices and maintained CI/CD pipelines for build processes.

Skills
======
* **Data Science and Machine Learning**:
  * Proficient in Python data science libraries: NumPy, Pandas, Matplotlib, and Seaborn.
  * Extensive experience with deep learning libraries: PyTorch and JAX.
  * Experience with high-performance computing (HPC) and distributed (e.g., 128+ GPUs) training.
* **Programming and Development**:
  * Proficient in Python, C, C++, Rust, C\#, and JavaScript/TypeScript
  * Experience with test-driven development, including unit tests, integration tests, and end-to-end tests.
  * In-depth knowledge of virtualization, containers, and Docker/Podman/Singularity.

Publications
======
(* denotes equal contribution)

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
