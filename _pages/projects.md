---
layout: single
permalink: /projects/
title: "Projects"
---

## Coursework Projects

#### <u>Destination Recommender for First-time Airbnb Bookers</u>

The project can be found [here](https://github.com/sghariha/Airbnb_Recommendations), and the accompanying report can be found [here](https://drive.google.com/file/d/1380BEefUNgPv2V8DBR549Y4X0voct-8p/view?usp=sharing).

This project was completed as part of the UCSD course, Web Mining and Recommender Systems (CSE 258) in Fall 2019. Myself and two classmates trained an XGB classifier that recommends 1 of 10 country destinations to first-time bookers on Airbnb. This was implemented using scikit-learn and trained using the demographic and web session data at [this public Kaggle competition](https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/overview). Our Kaggle submission lands us at around the 22nd percentile.

#### <u>SpongeBob Quote Attributor</u>

The project can be found [here](https://whispering-harbor-58905.herokuapp.com/textclassifier/).

This project was completed as part of the UCSD course, Statistical Natural Language Processing (CSE 256) in Spring 2019. I trained a semi-supervised logistic regression text classifier on episode transcripts from the cartoon, SpongeBob SquarePants, using TF-IDF weighting and 1-3 grams to be able to predict which of 10 possible characters is the speaker of a given input quote. The output of a prediction by the classifier includes graphic explanations involving n-gram weights and word clouds to explain the model’s prediction to the user, and does comparative analysis between the predicted and actual speaker. The user may provide their own text, ask the application choose a real quote from a specific character at random, or ask the application to choose a real quote from any of the characters at random. I used scikit-learn and Django to develop the web application, and Heroku to deploy.

#### <u>N-body Simulation</u>

A short report on this project can be found [here](https://cse291d.wordpress.com/).

This project was completed as part of the UCSD course, Physics Simulation (CSE 291I) in Spring 2019. For this project, I implemented the Barnes-Hut algorithm to simulate n-body gravitational dynamics for galaxies and the rings of Saturn. This included generating galactic mass and velocity distributions for disk galaxy models. C++, GLEW, GLUT, and GLM were used to develop this project.
