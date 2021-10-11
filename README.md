# Generative Modelling: Applying GANs to generate out-of-sample inter-class images
Submitted as part of the degree of Msci Natural Sciences (3rd year) to the Board of Examiners in the Department of Computer Sciences, Durham University. 
This summative assignment was assessed and marked by the professor of the module in question:
## Grade: 1st - 104/100 (100 + bonus of 4), 1st in year (of 136 students).
> "This solution is outstanding as you’ve implemented the most relevent recent state-of-the-art model and
> adopted it for the task. The model samples are amongst the best in the class - i’ve used several of them as
> exemplars in the general feedback. The way you approached sampling the data is exactly what professionals
> do in the field. The report is also extremely well-written and presented.
> Overall, this is a fantastic piece of academic writing, scientific experimentation, independent research, and countless
> hours of GPU training and shows an unexpected mastery of deep learning (and reinforcement learning) for
> an undergraduate. This must clearly be your passion, and all I can say is I hope you keep doing this in your
> career! Perfect!" - Dr Chris G. Willcocks

## Paper Abstract:
After successfully implementing and experimenting with two flow-based
generative models [1], namely Glow [6] and the multi-scale augmented normalizing flow proposed in [9], and various variational autoencoder (VAE)
[5] architectures, the study moved on to Generative Adversarial Networks
(GAN) [2], specifically the ”lightweight GAN” structure proposed in [8].

All models were implemented with the goal of generating diverse and realistic images of white winged horses (Pegasi) from data sets containing no
such images, namely CIFAR-10 and STL-10.

## Contents:
* pegasus-paper.pdf - Paper reporting findings and methodology of the study, "The Mythical Pegasus: A Mysterious Journey".
* source-code/ - Folder containing the herein modified version of lucidrains' implementation of state-of-the-art 'lightweight' GAN proposed in ICLR 2021 (this source-code has yet to be cleaned and commented, apologies). Credits for paper and code go to:
    - 'lightweight' GAN paper - [Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis](https://openreview.net/forum?id=1Fqg133qRaI).
    - [lucidrains](https://github.com/lucidrains/)' original implementation - https://github.com/lucidrains/lightweight-gan.

## Results (taken from pegasus-paper.pdf):
![Best Pegasus](results-image-1.png?raw=true "Best Pegasus")
![Other Pegasi](results-image-2.png?raw=true "Other Pegasi")
