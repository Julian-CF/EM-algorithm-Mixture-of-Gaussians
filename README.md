# Unsupervised-learning: Mixture-of-Gaussians EM algorithm
This project:
- (i) generates some data from a mixture of Gaussians (MoG) model, and 
- (ii) subsequently fit a MoG model to the generated data, in order to recover the original parameters using the EM algorithm. A visualisation of the EM variational distribution fit to the data as well as the log likelihood for each iteration is also given to give a sense of how the updates are done. 
- Then (iii) this EM algorithm will be used to fit another mixture of Gaussians model using real data (the constructdata data set) and visualize the posterior for the positive class using Baye's theorem which usually is the real use of an EM algorithm. 


This code is for someone who understands EM algorithm and wants to play around with a Mixture of Gaussians. A good explanation for this algorithm for MoG models can be found here: https://towardsdatascience.com/gaussian-mixture-models-explained-6986aaf5a95 with the derivation of the parameters update which are used in the code.

