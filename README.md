# SRGAN
Super Resolution Generative Adversial Network
    
This repository includes:

    The project code in .ipynb format.
    The project code in .py format.
    Two scripts in .py format to create new .mat files and slice images, both commented.
    A .mat file with 100 of images from DIV2K Dataset (TEST).
    A .mat file with few images of pixel-art to test the results in other kind of images (TEST).
    

It has been followed the DL architecture proposed in this[https://arxiv.org/abs/1609.04802] paper with some minor changes.

To recreate the resouls of the project documentation the following dataset has been used: {NTIRE 2017 Challenge on Single Image Super-Resolution: Dataset and Study}[https://data.vision.ee.ethz.ch/cvl/DIV2K/].

This SRGAN is trained and programed to increment by 2 the resolution, we use images of 64x64 to obtain 128x128 images.

But it can be used to obtain 128x128 to 256x256, we doesn't test the results.

To upscale the resolution more than 2 is necessary change a little bit the architecture!!

    
