---
layout: page
title: "Assignment: Analysis of a Possible Inequity"
doodle: "/doodle.png"
permalink: /assignments/inequity-analysis/
---

In this assignment, you will write a paper that identifies and
analyzes a potential inequity in the world. You may either choose from
an option below or propose your own topic (see requirements at
bottom).

Your paper must contain the following components:
1. An introduction to the problem and the main conclusion of the
   paper.
2. A description of the historical/sociological/economic context of
   the studied inequity, as well as a description of the inequity
   itself. This section should put the inequity in the context of
   the qualitative theories of justice, equality, and power structures
   covered in class. 
3. A description of the observed data and in what ways it is
   appropriate for investigating the inequity at hand, and in what
   ways it *fails* to capture needed information for your study
   (making reference to material on measurement and power in week
   2). This portion with be backed by data.
4. A description of the quantitative measures of fairness that you
   used in your investigation, why they are appropriate for the given
   context, alongside the results of those calculations.
5. An interpretation of the results from (4), including informal
   reasoning of the cause of the inequities. If appropriate, you can
   discuss possible reasons your results don't represent the inequity
   in a straightforward way (e.g. under/over represents it). Be
   specific about the limitations of your approach.

## Potential Topics 

You may choose from the topics below, or choose your own. If you do
choose your own topic, you must get the proposed investigation
approved by course staff (you must have the dataset in hand, along
with a preliminary data analysis).

If choosing from the options below, the existing literature likely
differs from the requirements for this paper. You should digest and
reframe the given reference, do your own data analysis, and refocus
the investigation. 

### Option 1: Police Traffic Stops

Focusing on potential inequities in traffic stops, including police
actions like pulling drivers over, searching and arresting them.

Dataset: Stanford [Open Policing](https://openpolicing.stanford.edu/)
dataset has traffic stops on many counties/cities around the US.

There are a number of papers to help orient you in the area, including
1. many of them listed on [Open Policing](https://openpolicing.stanford.edu/) 
1. Baumgartner, Frank R., Derek A. Epp, Kelsey Shoub, and Bayard Love. 2017. [Targeting Young Men of Color for Search and Arrest during Traffic Stops: Evidence from North Carolina, 2002-2013](https://fbaum.unc.edu/articles/PGI-2017-Targeting.pdf). Politics, Groups, and Identities 5, 1: 107-131.
1. [SDSU Study on SD Police](https://spa.sdsu.edu/documents/Traffic_enforcement.pdf)

### Option 2: Bias in Lending

The consumer financial protection bureau provides
mortgage
[data](https://www.consumerfinance.gov/data-research/hmda/historic-data/)
for public use.

In the 1990s, the Boston Fed published [Mortgage Lending in Boston:
Interpreting HMDA
Data](https://www.bostonfed.org/publications/research-department-working-paper/1992/mortgage-lending-in-boston-interpreting-hmda-data.aspx). 

There were many articles published in response over the last 25 years
that you may also follow:

* [Do Minorities Pay More for Mortgages?](https://academic.oup.com/rfs/article/34/2/763/5827007)
* [Algorithmic Fairness in Mortgage Lending: from Absolute Conditions to Relational Trade-offs](https://link.springer.com/article/10.1007/s11023-020-09529-4)
* [Evidence on Discrimination in Mortgate Lending](https://pubs.aeaweb.org/doi/pdfplus/10.1257/jep.12.2.41)
* [Mortgage Lending in Boston: Interpreting HMDA Data](https://www.jstor.org/stable/2118254?seq=1)
* [Same Sex Couples and Mortgage Lending](https://ncrc.org/same-sex-couples-and-mortgage-lending/)
* [Missing Race Data in HMDA and the Implications for the Monitoring of Fair Lending Compliance](https://www.occ.gov/publications-and-resources/publications/economics-working-papers/pub-econ-working-paper-2001-1.pdf)

### Option 3: Medical imaging

Medical imaging data often exhibits imbalance in the gender/race of
the patient. This imbalance has been known to affect the quality of
disease detection algorithms.

This dataset is a large image dataset. I suggest you only work on this
option if you have some experience working with image data (or want to
put in extra work to learn). Kaggle stores a large database of chest
X-Rays from the NIH: https://www.kaggle.com/nih-chest-xrays/data

[This
paper](https://www.pnas.org/content/pnas/early/2020/05/19/1919012117.full.pdf)
looks at the performance of image classifiers due to gender imbalance
in the dataset.

If you work on this option, please see the instructor early for
guidance. You will likely use a subset of the data and a large pretrained
CNN (that you tweak) to start.

### Option 4: Find your own topic

You may also propose your own investigation!
If you are interested in finding your own topic, you must discuss the
idea with course staff (instructor or TA) before starting.

*Note*: One difficulty here, is finding a dataset that has information about
the group that you are writing about. One option, if a dataset has
names in it (e.g. public salary/loan data), is to use census data to
make a best guess at an individual's gender/race from their name (as
in DSC 80).

## Requirements for writing and style

While your project will require coding work, the coding will not
directly appear in your work. Your paper will be a narrative
about your subject that's informed by your (code) investigation. 

Expect your paper to be approximately 1600 words (4-5 pages).

### Writing about high-stakes topics

* You should follow guidelines found in the AP guide (see the 'Writing
  about Bias and Discrimination' section of the course webpage). 
* If you are writing about a specific group, read the referenced
  articles on writing about that group.

### Style

* This is a data-driven study; you should have tables and plots. The
  gist of your paper should be understandable from the figures alone.
* All figures should have *titles*, graphs should have *labeled axes*,
  and legends should be easily understandable. Any of the many
  research papers in this class provide examples of good figures.
* Either LaTeX, Rmd, or a pdf generated from markdown (e.g. with a
  notebook). If notebook, code must not be visible (see resources).
* Figures should be generated/saved as an image (no screenshots).
* Be sure to cite your references, including the paper you are
  working from.

## Initial Project Checkpoints

You must check-in with either the instructor or TA by the *end of week 2*.
The check-in can either happen in discussion section, lecture,
scheduled office hours, or by email. You may be asked for a
synchronous meeting if questions remain after checking-in via email.

The checkpoint consists of:
* Confirming who is in your group, if you are not working alone.
* Your proposed paper topic (even if you are choosing one of the
  default ones).
* Running by any potential new data sources (if proposing your own
  'new' project or want to tweak an existing one).

By the end of week 3, you need to turn in an initial exploratory data
analysis on the primary dataset for your paper (to ensure that you
have looked at the data).

## Final Due Date

The final paper is due Friday 11:59PM PDT on May 7 (week 6).

**If you are working in a group**, the final paper is due 48 hours later,
Sunday 11:59PM PDT on May 9.

## Rubric

The following descriptions should give you an idea of what a paper of
a given grade (range) looks like. A paper of a given grade must meet
*or exceed* all requirements listed below it.

A grade of A+/A/A- on the paper will:
* Thoroughly connect the scenario of study with relevant readings and
  topics covered in the lecture component of the course.
* Clearly address all five paper components given at top of this
  assignment.
* Put together content in a clear, cohesive narrative, using the
  writing and style guidelines described above.

A grade of B+/B/B- on the paper will:
* On a surface level, connect portions of the scenario of study with relevant readings and
  topics covered in the lecture component of the course.
* Attempt to address all five paper components given at top of this
  assignment, though some may not be thoroughly addressed. For
  example, the paper's result interpretation may be too cursory.
* Put together content following most writing/style guidelines from
  above. Best practices on writing about bias and discrimination must
  still be followed.

A grade of C+/C/C- on the paper will:
* Summarize the investigation, but rarely connects
  explicitly to course material.
* Only address a few of the paper components in meaningful ways; the
  rest are cursory.
* Ignore much of the style and writing guidelines, including best
  practices on writing about bias and discrimination.

A grade of D/F on the paper will result from meeting none of the
standards above.
