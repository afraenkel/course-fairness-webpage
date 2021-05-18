---
layout: page
title: Fairness across the ML Pipeline
permalink: /weeks/week07/
doodle: /doodle.png
---

## Topics

* Approaching fairness across the ML Pipeline

## Reading (Required)

This paper approaches pre-processing a dataset via 'label-flipping'
and 're-weighting', in order to impose demographic parity:

* [Building Classifiers with Independency Constraints](https://www.win.tue.nl/~mpechen/publications/pubs/CaldersICDM09.pdf)

This article discusses how even a fair algorithm may result in unfair
circumstances (an intro to next week's topic):

* [Airbnb pricing algorithm led to increased racial disparities](https://www.ft.com/content/5b1471e0-ed4a-47f5-8f3f-0a1ee7f7999c)


## Reading (Optional)

This paper approaches pre-processing a dataset by changing the
distribution of attributes:

* [Certifying and removing disparate impact](https://arxiv.org/pdf/1412.3756.pdf)

This paper using the in-processing approach of adding a penalty to the
loss function to better learn fair model parameters:

* [Fairness-aware Learning through Regularization Approach](https://www.kamishima.net/archive/2011-ws-icdm_padm.pdf)

## Reading Responses

* Implement each of the preprocessing techiniques done in lecture
  using Pandas. Turn in code for the 'label flipping' algorithm (a
  function that takes in a dataset and returns a balanced dataset).

* In the Financial Times article, discuss issues of fairness at stake
  through the lense of Fair Equality of Opportunity and Luck
  Egalitarianism. Be explicit about the utility being considered, the
  model (a regressor, not classifier), and the decision making
  involved. Where in the pipeline do you think fairness should be
  judged?


