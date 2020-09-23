---
layout: single
permalink: /projects/
#title: "Projects"
author_profile: true
---

<a href="#research-projects">\[Research Projects\]</a>&nbsp;<a href="#coursework-projects">\[Coursework Projects\]</a>

<h2 id="research-projects">Research Projects</h2>

<h4 id="ligo-lasso"><u>Automated Tool for Identifying LIGO Noise Sources</u></h4>

This project was completed as part of the software development I did as a research assistant when working with [Prof. Joshua Smith](https://physics.fullerton.edu/~josmith/) at the [Gravitational-Wave Physics and Astronomy Center (GWPAC)](https://physics.fullerton.edu/gwpac/). Developing this tool involved contributing to and using the [GWDetChar](https://gwdetchar.readthedocs.io/en/stable/) Python package. This tool uses lasso regression on gravitational wave data to help identify noise sources that reduce [LIGO](https://www.ligo.caltech.edu/)'s astronomical range. It is currently run daily on LIGO data and used by LIGO commissioners and researchers to help identify and analyze noise sources.

This project is not publicly viewable, but I co-authored a paper on some of this work, which is published [here](https://iopscience.iop.org/article/10.1088/1361-6382/aae593) and publicly available [here](https://arxiv.org/abs/1807.02592). I also presented on this work at the [34th Pacific Coast Gravity Meeting](http://www.tapir.caltech.edu/~pcgm34/), where the presentation can be found [here](https://drive.google.com/file/d/1Ic5rUPXpaCZA7rVTPqsHnwRKPGYY2yPI/view?usp=sharing).

<h4 id="gwdetchar"><u>GWDetChar (contributor)</u></h4>
I am not a core developer of [GWDetChar](https://gwdetchar.readthedocs.io/en/stable/), but I contributed to this Python package for an ongoing period of time through the development of the tool mentioned above.

<h4 id="spectre"><u>SpECTRE (contributor)</u></h4>
I am not a core developer of [SpECTRE](https://spectre-code.org/), but I have contributed to this in-development software for an ongoing period of time while working with [Prof. Geoffrey Lovelace](https://geoffrey-lovelace.com/) as a research assistant at the [Gravitational-Wave Physics and Astronomy Center (GWPAC)](https://physics.fullerton.edu/gwpac/). The goal of this software is to use numerical relativity to simulate and study extreme spacetimes and astrophysical events, including binary black hole and binary neutron star mergers.

Currently, I'm working on implementing an interface for working with algebraic representations of tensor expressions in SpECTRE. SpECTRE implements equations used in general relativity that rely on tensor expressions, but working with them in code is not as intuitive or fool-proof as working with tensor expressions on paper. To this end, under the mentorship of [Nils Deppe](https://nilsdeppe.com/), I'm working on adding to his implementation of an interface for working with algebraic representations of tensor expressions.

<h2 id="coursework-projects">Coursework Projects</h2>

<h4 id="airbnb"><u>Destination Recommender for First-time Airbnb Bookers</u></h4>

The project can be found [here](https://github.com/sghariha/Airbnb_Recommendations), and the accompanying report can be found [here](https://drive.google.com/file/d/1380BEefUNgPv2V8DBR549Y4X0voct-8p/view?usp=sharing).

This project was completed as part of the UCSD course, Web Mining and Recommender Systems (CSE 258) in Fall 2019. Myself and two classmates trained an XGB classifier that recommends 1 of 10 country destinations to first-time bookers on Airbnb. This was implemented using scikit-learn and trained using the demographic and web session data at [this public Kaggle competition](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/overview). Our Kaggle submission lands us at around the 22nd percentile.

<h4 id="spongebob"><u>SpongeBob Quote Attributor</u></h4>

The project can be found [here](https://github.com/macedo22/SpongeBob-NLP-speaker-identification) and the web application can be found [here](https://whispering-harbor-58905.herokuapp.com/textclassifier/).

This project was completed as part of the UCSD course, Statistical Natural Language Processing (CSE 256) in Spring 2019. I trained a semi-supervised logistic regression text classifier on episode transcripts from the cartoon, SpongeBob SquarePants, using TF-IDF weighting and 1-3 grams to be able to predict which of 10 possible characters is the speaker of a given input quote. The output of a prediction by the classifier includes graphic explanations involving n-gram weights and word clouds to explain the model’s prediction to the user, and does comparative analysis between the predicted and actual speaker. I used scikit-learn and Django to develop the web application, and Heroku to deploy.

<h4 id="nbody"><u>N-body Simulation</u></h4>

A short report on this project can be found [here](https://cse291d.wordpress.com/).

This project was completed as part of the UCSD course, Physics Simulation (CSE 291D) in Spring 2019. For this project, I implemented the Barnes-Hut algorithm to simulate n-body gravitational dynamics for galaxies and the rings of Saturn. This included generating galactic mass and velocity distributions for disk galaxy models. C++, GLEW, GLUT, and GLM were used to develop this project.
