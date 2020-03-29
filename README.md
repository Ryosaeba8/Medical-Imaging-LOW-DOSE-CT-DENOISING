# DLMI
DLMI PROJECT : LOW DOSE CT DENOISING

Implementation of Low Dose CT Image Denoising Using a Generative Adversarial Network with Wasserstein Distance and Perceptual Loss
https://arxiv.org/abs/1708.00961 

<img src="https://github.com/Ryosaeba8/DLMI/images/wgan_vgg.JPG" width="550"/>    

### DATASET & CODE

We used a Benchmark Dataset for Low-Dose CT Reconstruction Methods. In total, the dataset contains 35 820 training images, 3522 validation images, 3553 test images. Each part contains scans from a distinct set of patients as we want to study the case of learned reconstructors being applied to patients that are not known from training.
https://zenodo.org/record/3384092
The notebook dlmi_project.ipynb contains a pytorch implementation of the Wgan-VGG Algorithm
### Evolution of reconstruction over the epochs

<img src="https://github.com/Ryosaeba8/DLMI/videos/wgan_vgg.gif" width="550"/>   

<img src="https://github.com/Ryosaeba8/DLMI/videos/vgg_alone.gif" width="550"/>   

