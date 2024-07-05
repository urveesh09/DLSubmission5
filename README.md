# Week 5: GANs

Our goal is to use Generative Adversarial Networks to generate images to see if we can pass the Discriminator.  This is based on a Kaggle competition.  Description from Kaggle:

A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

Your task is to build a GAN that generates 7,000 to 10,000 Monet-style images. 

Note: As per the recommendation from the Kaggle competition, I'll be using the Monet CycleGAN Tutorial as a reference guide for the architectural approach.

#### Data description


    monet_jpg - 300 Monet paintings sized 256x256 in JPEG format
    monet_tfrec - 300 Monet paintings sized 256x256 in TFRecord format
    photo_jpg - 7028 photos sized 256x256 in JPEG format
    photo_tfrec - 7028 photos sized 256x256 in TFRecord format