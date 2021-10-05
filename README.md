# Generative Modelling: Applying GANs to generate out-of-sample inter-class images - "The Mythical Pegasus: A Mysterious Journey"
Submitted as part of the degree of Msci Natural Sciences (3rd year) to the Board of Examiners in the Department of Computer Sciences, Durham University. 
This summative assignment was assessed and marked by the professor of the module in question:
## Grade: 1st - 104/100 (100 + bonus of 4)
## Paper Abstract:
After successfully implementing and experimenting with two flow-based
generative models [1], namely Glow [6] and the multi-scale augmented normalizing flow proposed in [9], and various variational autoencoder (VAE)
[5] architectures, the study moved on to Generative Adversarial Networks
(GAN) [2], specifically the ”lightweight GAN” structure proposed in [8].

All models were implemented with the goal of generating diverse and realistic images of white winged horses (Pegasi) from data sets containing no
such images, namely CIFAR-10 and STL-10.

## Contents:
* pegasus-paper.pdf - Paper reporting findings and methodology of the study.
* source-code/ - Folder containing the herein modified version of lucidrains' implementation of state-of-the-art 'lightweight' GAN proposed in ICLR 2021 (this source-code has yet to be cleaned and commented, apologies). Credits for paper and code go to:
    - 'lightweight' GAN paper - [Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis](https://openreview.net/forum?id=1Fqg133qRaI).
    - [lucidrains](https://github.com/lucidrains/)' original implementation - https://github.com/lucidrains/lightweight-gan.
