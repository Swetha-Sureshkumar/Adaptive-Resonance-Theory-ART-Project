# Adaptive-Resonance-Theory-ART-Project

The Adaptive Resonance Theory (ART) is a neural network that utilizes an unsupervised learning method to detect patterns within a dataset. Unlike other networks, ART can continuously learn new input patterns while retaining previously learned information. The algorithm uses a clustering approach, where an input is compared to existing clusters to determine if it belongs to one of them or if a new cluster needs to be created.

In this project, the ART network was implemented using Python and applied to the MNIST dataset, which was divided into a training set of 60,000 samples and a testing set of 10,000 samples. The implementation utilized the following python libraries: Keras, Pandas, Numpy, Random, and Matplotlib.pyplot.

After 14 iterations of learning and updating the network's vectors, a contingency matrix was generated to evaluate its performance. The matrix showed the number of samples that were assigned to each cluster and how they related to the MNIST classes. The network's performance was also evaluated by comparing different vigilance values and the resulting clusters with the MNIST classes.
