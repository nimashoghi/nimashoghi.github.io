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

I'm a PhD student in Machine Learning at Georgia Tech, where I am focusing on Deep Learning for Scientific Applications under the guidance of Dr. Pan Li and Dr. Victor Fung. I earned my B.S. and M.S. degrees in Computer Science from Georgia Tech, during which I conducted research at the High Performance Computer Architecture Lab on accelerating ML training and inference.  Prior to starting my PhD, I completed a two-year AI residency at Meta AI's FAIR Chemistry team, where I worked on developing large pre-trained models, trained on a diverse mixture of chemical data across multiple domains, for general-purpose chemical property prediction. My research interests lie in the application of large-scale machine learning techniques to challenging problems in science and engineering. I am particularly excited about the potential for deep learning to accelerate discovery and understanding in fields like chemistry and climate science.

My CV is available [here](files/cv.pdf).

Recent Updates
======
* **[Jan 2024]** Our paper on [large-scale diverse pre-training for chemical property prediction](https://openreview.net/forum?id=PfPnugdxup) has been accepted to ICLR 2024! Please visit our [webpage](https://nima.sh/jmp/) for more information, including an interactive visualization of its embeddings!

Education
======
* Ph.D. in Machine Learning (School of Computational Science and Engineering), **Georgia Institute of Technology**, 2024 - Present
  * *Advisors*: [Dr. Pan Li](https://sites.google.com/view/panli-purdue) and [Dr. Victor Fung](https://cse.gatech.edu/people/victor-fung)
  * *Research Focus*: Deep Learning for Scientific Applications (e.g., Chemistry, Climate Science, etc.)
* M.S. with *Highest Honors* in Computer Science (Machine Learning Specialization), **Georgia Institute of Technology**, 2020 - 2021
* B.S. with *High Honors* in Computer Science (Machine Learning and Devices Threads), **Georgia Institute of Technology**, 2015 - 2019
* International Baccalaureate Diploma, **Druid Hills High School**, 2011 - 2015

Work experience
======
* Temporary Research Staff at the **[High Performance Computer Architecture Lab at Georgia Tech](https://sites.gatech.edu/hparch/)**, Dec 2023 - May 2024
  * Working on efficient inference strategies for pre-trained image diffusion models, with a focus on generating diverse, high-quality images.
  * Advisors: [Dr. Hyesoon Kim](https://www.cc.gatech.edu/~hyesoon/) and [Dr. Stefano Petrangeli](https://research.adobe.com/person/stefano-petrangeli/)

* AI Resident at **[Meta Fundamental AI Research (FAIR)](https://ai.meta.com/research/)**, Aug 2021 - Aug 2023
  * Worked on the [Open Catalyst Project](https://opencatalystproject.org/index.html) on the FAIR Chemistry team, focusing on the development of large-scale pre-training methods for chemical property prediction.
  * Advisors: [Dr. Larry Zitnick](http://larryzitnick.org/) and [Dr. Abhishek Das](https://abhishekdas.com/)

* Research Assistant at **[High Performance Computer Architecture Lab at Georgia Tech](https://sites.gatech.edu/hparch/)**, May 2019 - May 2021
  * Developed software-level and hardware-level techniques for accelerating deep learning training and inference.
  * Advisors: [Dr. Hyesoon Kim](https://www.cc.gatech.edu/~hyesoon/) and [Dr. Moinuddin Qureshi](https://www.cc.gatech.edu/~mqureshi/)

* Graduate Teaching Assistant at **[Georgia Institute of Technology](https://www.gatech.edu/)**, Aug 2020 - May 2021
  * CS 4510: Automata and Complexity, Spring 2021, Taught by [Dr. Zvi Galil](https://www.cc.gatech.edu/people/zvi-galil)
  * CS 4510: Automata and Complexity, Fall 2020, Taught by [Dr. Merrick Furst](https://www.cc.gatech.edu/people/merrick-furst)

Publications
======
(* denotes equal contribution)

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
