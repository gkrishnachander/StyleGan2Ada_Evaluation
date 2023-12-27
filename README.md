Training Generative Adversarial Networks (GANs) is a computationally expensive
and challenging task that typically demands large datasets. However,
the StyleGAN2-ADA offers a solution to this problem by enabling faster
training and requiring smaller datasets. The paper first reproduces and validates
the results of the original StyleGAN2-ADA paper - Karras et al. (2020).
Then, a model was trained on a landscapes dataset with 1349 images created
using Flickr and Stable Diffusion. The results demonstrate that StyleGAN2-
ADA can produce high quality and visually realistic images of natural landscapes
and has potential for various applications such as virtual reality, gaming
and content creation. The resultant model also performed well on GAN
specific evaluation metrics - Fréchet Inception Distance (FID) and Kernal Inception
Distance (KID). FID was observed to be consistent with human perceptual
evaluation of generated synthetic images. Finally, the work proves
that StyleGAN2-ADA consistently produces good quality models without significant
hyper-parameter search or frequent retraining.
