# ESRGAN
 ESRGAN is differenft from the SRGAN by three aspects:

1. It can adopt a deeper model using Residual-in-Residual Dense Block (RRDB) without batch normalization layers;

2. Deploy Relativistic average GAN instead of the vanilla GAN.

3. Improve the perceptual loss by using the features before activation.

In contrast to SRGAN, which claimed that deeper models are increasingly difficult to train, our deeper ESRGAN model shows its superior performance with easy training.

![image](https://github.com/AICODER009/pytorch_super_resolution/assets/133597851/ce03b717-5e02-46c5-a9fb-ebe829bd4356)

# How to setup
1. Clone the original github repo.

2. > git clone https://github.com/xinntao/ESRGAN

   > cd ESRGAN    

3. Place your own low-resolution images in ./LR folder. (There are two sample images - baboon and comic).

4. Download pretrained models from [Google Drive](https://drive.google.com/drive/u/0/folders/17VYV_SoZZesU6mbxz2dMAIccSSlqLecY).

5. Run test.py.
# Results
![image](https://github.com/AICODER009/pytorch_super_resolution/assets/133597851/96393ea3-bd27-4264-8550-7ad2fe270775)
