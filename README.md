# SR-GAN
## _Super Resolution Generative Adversial Network_
With the surge of Convolutional Neural Networks (CNN), artificial intelligence applied to computer vision has been booming in the last few years. This deep learning technology never ceases to surprise us with new applications such as Super Resolution Generative Adversial Network.

Super-resolution imaging (SR) is the process in which a high-resolution (HR) image is recovered from a low-resolution (LR) image. This technology has been the subject of research for the last 3 years, which has allowed different DL specialists to perform different studies to make SR images as realistic as possible.

## About the project

In this project we share a Generative Adversarial Network based on the research carried out by _Christian Ledig, Lucas Theis, Ferenc Huszar, Jose Caballero, Andrew Cunningham, Alejandro Acosta, Andrew Aitken, Alykhan Tejani, Johannes Totz, Zehan Wang, Wenzhe Shi_ and published at archive.org under the name [_Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network_](https://arxiv.org/abs/1609.04802).

The project does not strictly follow the model proposed by the previously mentioned authors of the paper, but rather includes slight modifications, particularly in the way the loss is computed for backpropagation in each of the models. It is also intended for personal testing, so that the exposed design manages to increase the resolution of small images to double its original size (128x128) since the resources required for computing higher resolution images are not accessible to ordinary users.

To recreate the results of the project documentation the following dataset has been used: [NTIRE 2017 Challenge on Single Image Super-Resolution: Dataset and Study](https://data.vision.ee.ethz.ch/cvl/DIV2K/).

## Features
- The project code in .ipynb format.
- The project code in .py format.
- A .ipynb file to create new .mat Dataset files and slice images and downgrade resolution.
- A .mat file with 1000 of images from DIV2K Dataset (TEST).
- A .mat file with 800 images randomly taken from the web and proccessed to be tested with the model.
- A .ckpt of the last pre-trained state of the model.

## Sample Test Images
![sample test](https://github.com/VPRamon/SR-GAN/blob/b73b94d08d8f9fb4e51bfa3593076e3d3ea71700/Results/sample_test.png)

## Requirements

Make sure you have installed the PyTorch library: https://pytorch.org/get-started/locally/
```bash
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
```
or
```bash
pip install torch===1.7.0 torchvision===0.8.1 torchaudio===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html
```
and other used libraries such as _numpy_, _scipy_, _matplotlib_, _opencv-python_ and _pillow_.

## Contact
For any doubt or reporting bug, you can contact me by email: vallespuigramon@gmail.com
