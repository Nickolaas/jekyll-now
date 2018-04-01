---
layout: post
title: Benign or malignant
---

Imagine a supervised learning algorithm where we're trying to predict whether
or not a lump (tumor) is harmful or benign. We can use attributes such as age,
tumor size. if we draw an x/y axis, what a learning algorithm would do is throw
a straight line through the dataset, separating the benign from the malignant,
and finding your point on the axis, will give us our answer, but there are other qualities
we could use too, like the clump thickness of the tumor, uniformity of cell size of the tumor, uniformity of cell shape of the tumor, and so forth.
the cool thing about this, is that eventually we'll be able to deal with not just two or three or five features or attributes, but
an infinite number of features.

How do you store an infinite number of things on the computer when your computer is going to run out of memory? It turns out when we use support vector machines, there's a
neat mathematical trick that will allow a computer to deal with an infinite number of features.

Supervised learning, we're told what is the "correct answer" that we would've liked our algorithms to predict. i.e. price of a house, whether a tumor is malignant or benign. but then there's
the regression problem, which means that our goal is to predict a continuous valued output, and the classification problem where the goal is to predict a discrete (1, 0) value. e.g. a learning algorithm that evaluates thousands of user accounts and predicts whether or not it's been hacked or compromised.
