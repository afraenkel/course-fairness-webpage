---
layout: page
title: "Assignment: Algorithmic Audit of a Decision Making System"
doodle: "/doodle.png"
permalink: /assignments/algorithmic-audit/
---

Write a paper that audits/analyzes an algorithmic decision making
system that you build (and may serve as a basis of comparison with a
real world system). This audit should go beyond an observational
analysis and leverage ~2 topics discussed in the
second half of the course:

* Inframarginality and threshold testing
* Intersectionality analysis
* Individual Fairness analysis
* Preprocessing, In-processing, and Post-processing (calibration) for
  fairness
* Selective labels problem (contraction; label augmentation)
* Feedback Loop modeling, simulation, and analysis
* Unsupervised representation analysis

This paper will require a lot more code and quantitative analysis than
the first. You do not need to submit code; only include results.

You are encouraged to continue with the subject-matter you began
studying in paper 1. You will meet with course staff during week 8 to
propose a plan for your paper.

This assignment is a group assignment. You may work individually, in
the same group of 2 as paper-1, or a different group of 2 entirely.

**Assignment FAQ**

Am I required to build my own model for this project?

* In most cases, yes. An objective of this assignment is to
  understand, from a Data Scientist's perspective, what it's like to
  build a model from end-to-end (including the context under which it
  operates and how it determines decisions). Part of building a model
  is doing a *self-audit* to surface potential issues of fairness.
  
In what cases do I not need to build/audit a model?

* Investigating threshold testing and individual fairness do not
  strictly require building a model to investigate these
  topics. However, comparing results of an analysis of existing
  (potential) inequities to the outcomes of your algorithmic decision
  makes a richer paper. If you plan on a *very* thorough investigation
  into one of these topics, however, you do not need to build a model.
  
When building a model to audit, what aspects of it should be described?

* You should describe how the model would work in real-life (how would
  it be used? What features would be available when using it? How are
  decisions made from the model output? from a score?). At a minimum,
  you should then compare the model performance (utility and fairness)
  with the observed outcomes. You choice of utility and fairness
  should be thorough and justified.
  
How are the topics listed at top incorporated?

* Investigate the topics in the context of your model? Does
  preprocessing help? How does your model perform on a threshold test?
  on feedback loop evolution? Individual Fairness?
  
How 'good' should the model be?

* Just good enough to do a convincing fairness analysis. Don't waste
  time 'eeking out a bit more performance', as that goes against the
  point of the course!
* Aim for light feature engineering, along the lines of project-5 in
  DSC 80. Use interpretable models when possible (logistic regression,
  random forest, gradient boosted trees).
  
Are there topics that pair together well?

* Threshold tests are a larger topic (look for code/libraries online;
  don't implement it from scratch). They would pair particularly well
  with "luck egalitarian" preprocessing.
  
* Individual Fairness and Intersectionality pair well together. When
  looking at (individually) unfair decisions, do a data analysis to
  understand if that unfairness is attributable to an attribute (and
  perhaps how it interacts with group-level unfairness)
  
* In-processing and intersectional analysis go well together (see
  lecture!)
  
* Pre/Post-processing pairs well with selective labelling approaches
  (including contraction and label augmentation)
  
* Feedback Loop modeling is a larger topic that would be well
  complemented with selective labeling or preprocessing. If exploring
  this subject matter, try to replicate the house price estimation
  procedure from lecture.

