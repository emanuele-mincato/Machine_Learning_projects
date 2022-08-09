# Machine_Learning_Projects

## Logo Contest
The aim of the contest is to retrieve the most similar images representing logos of famous companies from a database set containing 110 images. We will consider 4 query images and use the SIFT algorithm. The performance of the model will be evaluated using precision, recall and average precision metrics for each for the query logos. You can modify the baseline (parameters, feature matching technique, ...) and send your results.

## Emojify

The aim of this work is to find the most related sentiment
of a written sequence and map it into an emoji, this is
a problem of text classification. In this case there are only
five emoji: heart, baseball, smile, disappointed, fork-andknife.
Our project is divided into two main parts. In the first
one we implement most of the model
(Logistic Regression, Random Forest, Support Vector Machine,
K-Nearest Neighbors) while in the second one we
build a Neural Network, a Deep NN and also we implement
a Long short-term memory (LSTM) NN because it can keep
track of the dependencies between sequence elements. We
decided to divide the project into these two parts because
we use different working methods.

## Optimization
Addressing a semi-supervised learning problem.
We have to simulate a scenario where we have high number of data
where only few of them are labelled. The goal is to assign
to all points the right labels by some optimization algorithm.

We simulated this case generating two clouds of points
on the plane and randomly choosing few of them to create
the labelled set of points. Then we used methods such as
Gradient Descent, Randomized Block Coordinate Gradient
Descent (BCGD) and Cyclic BCGD with blocks of dimension 1. 
The goal is to properly classify all the points between the two sets and test the accuracy of the implemented
methods. After this first part we tested the methods on a
real dataset for a problem of gender classification.
