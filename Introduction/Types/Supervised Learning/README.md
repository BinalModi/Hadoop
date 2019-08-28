# Probabilistic Modeling

This refers to models of data generation i.e. generative models. They model where the data comes from.

Consider spam classification. We would learn the probability distribution for the examples in the spam class as well as the probability distribution for the examples in the non-spam (ham) class.

Given a new sample x, we must then calculate P(x is spam).
By default, we label it as spam if P(x is spam)>=0.5 i.e. if P(x is spam)>=P(x is ham).

More generally put, we must compute P(C|X) i.e. the probability of a class C given a training example X i.e. the probability of X belonging to C.

![Neurons](https://vikrambajaj22.gitbooks.io/cs-gy-6923-machine-learning/content/assets/neuron.png)
