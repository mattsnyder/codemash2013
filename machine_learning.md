# Machine Learning
Predicting the future
Seth Juarez

## What?
* finding and exploiting patterns in data
* replace "human writing code" with "human supplying data"
* system figures out whatthe person wants based on examples
* need to abstract from "training" examples to "test" examples

* Two areas => Supervised learning, unsupervised learning

* Kinect uses decision forest

## Supervised Learning
About making decisions
1. Data, regular objects
2. Maths => convert data to linear algebra
3. Model
4. Prediction

What are we trying to learn?
* binary classification (if we have binary, can do multi)
* multi class classification
* regression

Given an x and y, if we get a new x, we should predict y

Data Descriptor => Describe Features and Labels on data (Math -
Conversion)

_Seth has written library for generating models and applying math._

Pack learning, tells you how many data points you need to get quality
results

## Linear Classifiers
Locate a single point to create a separator
It will make some mistakes
Dot product of vectors
a.b = |a| x |b| cos 0
When does this equal 0?

### Perceptron
Frank Roenblatt

Projecting into infinite space. Use a kernel. Kernels transform your
space in the hope there is a linear classifier.

## Non Linear Classifiers
Kernels transform space
Linear separators in an augmented space become non linear in their
original space

## Decision Trees
Find which columns to split on first, which ones to split on next =>
Entropy
Entropy
=======
* Measures the messiness
* Which decision trees we want to measure the messiness of the answer

Conditional entropy => If I know X, how much less messy is Y


## Recap
http://numl.net

Computer is not good at making decisions with data it's never seen.

