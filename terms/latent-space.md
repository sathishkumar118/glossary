---
title: Latent Space
related_terms:
 - dimensionality-reduction
 - overfitting
---
A latent space, also known as a latent feature space or embedding space, is an embedding of a set of items within a manifold in which items resembling each other more closely are positioned closer to one another in the latent space. Position within the latent space can be viewed as being defined by a set of latent variables that emerge from the resemblances from the objects.

In most cases, the dimensionality of the latent space is chosen to be lower than the dimensionality of the feature space from which the data points are drawn, making the construction of a latent space an example of dimensionality reduction, which can also be viewed as a form of data compression. Latent spaces are usually fit via machine learning, and they can then be used as feature spaces in machine learning models, including classifiers and other supervised predictors.

The interpretation of the latent spaces of machine learning models is an active field of study, but latent space interpretation is difficult to achieve. Due to the black-box nature of machine learning models, the latent space may be completely unintuitive. Additionally, the latent space may be high-dimensional, complex, and nonlinear, which may add to the difficulty of interpretation. Some visualization techniques have been developed to connect the latent space to the visual world, but there is often not a direct connection between the latent space interpretation and the model itself. Such techniques include t-distributed stochastic neighbor embedding (t-SNE), where the latent space is mapped to two dimensions for visualization. Latent space distances lack physical units, so the interpretation of these distances may depend on the application.

A number of algorithms exist to create latent space embeddings given a set of data items and a similarity function.




[1]: /terms/dimensionality-reduction/
[2]: /terms/overfitting/