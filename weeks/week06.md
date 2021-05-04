---
layout: page
title: Individual Notions of Fairness
permalink: /weeks/week06/
doodle: /doodle.png
---

## Topics

* Fairness and discrimination at the individual level. Introduction to Causality.

## Reading (Required)

This paper was a ground-breaking paper that discusses fairness as a
fundamental concept among individuals, as opposed to requiring being
classified among an already identified salient group. Read sections
1-3 for the main ideas (don't worry about the details of the proofs).

* [Fairness Through Awareness](https://arxiv.org/abs/1104.3913)
  by Dwork, Hardt, Pitassi, Reingold, Zemel

*Remark*: This paper considers classifiers that potentially return
*distributions* of outcomes (as opposed to outcomes itself). As such,
the metric on the target space is a distance between
distributions. However, the metric that's primarily used is the *total
variation distance*, which takes the point-wise difference of
outcomes; this is exactly the case covered in class.


Carefully read a response to the notion of Individual Fairness criteria:

* [What's Fair about Individual Fairness?](http://philsci-archive.pitt.edu/18889/1/Fleisher%20-%20Individual%20Fairness.pdf)
  by Will Fleischer
  

## Reading (Optional)

The following blog post explains some warnings about matching
processes. You may find it useful to read the previous posts as well
(intro to confounding bias; intro to propensity score matching). We
will go over these background concepts in class.

* [Propensity Score Matching: What Can Go Wrong](https://www.causalflows.com/propensity-score-matching-threats/)

* [Why Propensity Scores Should Not Be Used for Matching](https://gking.harvard.edu/files/gking/files/pan1900011_rev.pdf)
  by Gary King and Richard Nielsen

## Reading Responses

From the *What's Fair about Individual Fairness* paper, summarize the
three main concerns about individual fairness. Do you agree with these
concerns? Give your informed opinion on the relative merits of
individual vs group notions of fairness.
