# Leverage Score Sampling for Complete Mode Coverage in Generative Adversarial Networks

Code, pdf and Supplementary Material accompanying the paper Leverage Score Sampling for Complete Mode Coverage in Generative Adversarial Networks: https://arxiv.org/abs/2104.02373.

Authors: Joachim Schreurs, Hannes De Meulemeester, Michaël Fanuel, Bart De Moor, and Johan A.K. Suykens

Abstract: Commonly, machine learning models minimize an empirical expectation. As a result, the trained models typically perform well for the majority of the data but the performance may deteriorate in less dense regions of the dataset. This issue also arises in generative modeling. A  generative model may overlook underrepresented modes that are less frequent in the empirical data distribution. This problem is known as complete mode coverage. We propose a sampling procedure based on ridge leverage scores which significantly improves mode coverage when compared to standard methods and can easily be combined with any GAN. Ridge leverage scores are computed by using an explicit feature map, associated with the next-to-last layer of a GAN discriminator or of a pre-trained network, or by using an implicit feature map corresponding to a Gaussian kernel. Multiple evaluations against recent approaches of complete mode coverage show a clear improvement when using the proposed sampling strategy.
