# Painting-GAN

Created a basic DCGAN for a landscape painting dataset of over 5000 images with resolution greater than 256x256
after about 2 hours of training on an RTX 2060 it lead to the following images generated. It seems to have been subject to mode collapse (some images are very similar to each other but come from different noise given to the generator)
![image](https://github.com/dkzhang01/Painting-GAN/assets/97487042/59f55bbd-9e2a-4b06-b184-bd046089714b)

The following is an animation that shows the generator working on fixed noise every 5 epoches of training.
![training-images](https://github.com/dkzhang01/Painting-GAN/assets/97487042/bb5467d1-4071-4067-9f16-a1c2e9a63394)

