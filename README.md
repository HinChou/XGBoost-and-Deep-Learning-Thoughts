# XGBoost-and-Deep-Learning-Thoughts
Comparison Between XGBoost and Deep Learning Algorithms(LSTM, CNN and RNN, etc.), and Create New Formats Which Combined Both.

## XGBoost:
Search wikipedia and github

pros: Always get nice results for medium size of data.

cons: Lacking CV for feature selection, but I fix this by rewrited the function.

## Deep Learning Algorithms:
Search wikipedia and github

pros: Always get nice results for large size of data.

cons: Hard to figure out the insight of the algorithm.

### Question:
* Is LSTM better than CNN or RNN for time series analysis?
* What is GAN(Generative Adversarial Networks)?
* What is collaborative filtering recommendation?

## Combining XGBoost and Deep Learning Algorithms:
* Use boosting algorithm for outer framework. 
* Set weak learner(aka base leaner) as one hidden layer ANN(LSTM, CNN or RNN). 
* Set low learning rate and use CV or OOB for predictive ability test.
* Could CV also be used to do the feature selection for this new framework?
* Need to find a way to figure out how to reduce the number of features instead of sacrificing too much performance.

## Questions:
* What kind of data should I use for this?
* How many data should I use for this?
* When, where & how can I achieve this topic?
* Heard about AlphaGo also used similar framework(tree ensemble works with nerual network), interesting coincidence, right? 
* Need to come up a way to train the model by using GPU(AMD) on my PC as a demo.
* Where can I use this framework? How does this framework solve real world problem?
* Need to dig into the deep learning world.
