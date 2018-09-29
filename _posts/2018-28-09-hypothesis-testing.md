---
layout: post
title: "Hypothesis Testing"
date: 2018-09-28
tags: [statistics, machinelearning]
comments: true

---

A statistical hypothesis is conjecture about the population parameter which may or may not be true. A simple example of conjecture would be average height of all children of age 14 years is 135cm. We need observations to verify the validity of the hypothesis. The verification procedure from observed data is called hypothesis testing. Lets consider another example, we want to verify that the acceleration due to gravity on earth and on moon is same or not. When we do hypothesis testing we have to split hypothesis into two parts, NULL hypothesis and alternate hypothesis. Based on the observed data we decide whether we would reject NULL hypothesis or do not reject null hypothesis. Generally we make null hypothesis which we want to disapprove, such that rejection of it, approves the alternate hypothesis. Failing to reject null hypothesis does not mean that we are accepting null hypothesis, it means there are not enough evidence in data to reject it. For example in case of jury, following are null and alternate hypothesis,

H0(Null Hypothesis) : Defendant is innocent.
H1(Alternate Hypothesis) : Defendent is guilty.

Based on evidences jury decides to reject or failure to reject null hypothesis, which means either he is guilty or there is not enough evidence that he is not innocent. In such decision there are two ways to commit mistakes and these are,
     | Defendant is innocent | Defendant is criminal|
Defendant is set free | Correct Decision | Misjudgement|
Defendant is convicted | Misjudgement | Correct Decision | 

In statistics these are called type I and type II errors
	| H0 is true | H1 is true|
Do not reject H0| Correct Decison | Type II Error|
Reject H0| Type I Error | Correct Decision|

Acceptance of H1 when H0 is true is called type I error. Probability of committing type I error is called level of significance. In case of jury example would be convicting the defendant when he is innocent. 
