# GANsBeyondDivergenceMin

I wrote the paper "GANs beyond divergence minimization" a month before the paper "The relativistic discriminator: a key element missing from standard GAN", more precisely on May 15th 2018. I did not release it on ArXiv until now because it was under anonymous reviews. Sadly, it was rejected by NIPS2018 because of the limited experiments.

In retrospect, I would have calculated the FID using Tensorflow (as done in the Relativistic GAN paper) rather than PyTorch to get values that can be comparable to other papers. I also would have run more experiments with different datasets. However, my computing power is extremely limited, and it is very demanding for me to train models (every night I have to reboot my computer on Linux, train some models for the night, stop training in the morning, keep track of what I did, and reboot on Windows). I also have new projects I am more interested in pursuing. Therefore, I am not planning to redo the analyses with Tensorflow FID and to add more experiments with these alternative loss functions. I leave this code for those who would like to try the different generator loss functions proposed in the paper. This is simply the code from https://github.com/AlexiaJM/RelativisticGAN, but with the additional generator loss functions.
