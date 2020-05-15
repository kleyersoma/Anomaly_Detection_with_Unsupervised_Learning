# Anomaly Detection with Unsupervised Learning


We are going to train some models that will be either able to reproduce the probability density function of a 
specific data-generating process or to identify whether a given new sample is an inlier or an outlier. 

What these models aim to do is finding and returning anomalies. These anomalies are samples that are below or under a predefined threshold,
this threshold is given by a probability distribution.

In this notebook we are going to develop and understand the next parts:

* Saying Hello to Probability Density Functions.
* Histograms are not enought, but why?
* Kernel Density Estimation (KDE).
* Selection criteria with Bandwidth.
* Univariate Anomaly Detection.
* Anomaly Detection with HTTP Attacks.
* One-class Support Vector Machines.
* Isolation Forests for Anomaly Detection.
* Summary.

### Note:
This notebook is a summary of the chapter **Anomaly Detection** of [Hands-On Unsupervised Learning with Python](https://www.packtpub.com/big-data-and-business-intelligence/hands-unsupervised-learning-python) 
by **Giuseppe Bonaccorso**
