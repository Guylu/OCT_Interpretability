# OCT_Interpretability
Project for Weizmann institute course: Deep Learning For Computer Vision.

Using OCT dataset provided by Kermany, we investigate differant deep learning methods (mostly transformers) and their application in medical imaging.
We fit several architectures on the data in a supervised fashion, and interpret the models using Grad-CAM, Occlusion tests, and review the attention maps.

In addition we look into the self supervised model called DINO (by FAIR), and investigate the usages of self supervised models in medical imaging ( transfer learning from ImageNet to Kermany dataset)


Check out video explaining the project of Youtube ***(use captions on :nerd_face:)***:

*
*
*
* Short Explanation About The Project:  **https://www.youtube.com/watch?v=97NHk06N5uY**
*
*
*
*

Quick demonstration of how Vision models (in the example: ConvNext - A ConvNet for the 2020s [2022] ) learn a latent representation of the Kermany Retinal OCT scans dataset:
</div>
<div align="center">
  <img width="30%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/ConvNextLearning.gif">
</div>
<!--
![This is an image](http://drive.google.com/uc?id=1aiUoeCK1qD4JD5O-na7GM7f_zhR6ckp8)
![This is an image](http://drive.google.com/uc?id=1X7j1Ak4TjHXEsfkvFZw-jDgq437jfCmM)
![This is an image](http://drive.google.com/uc?id=13oXRCTriC0DaKZTmmBwcVfx2ociVPfNe)
![This is an image](http://drive.google.com/uc?id=1oX77gJZENvKPG893qUsvNy5bEltSqFBE)
![This is an image](http://drive.google.com/uc?id=1TFCJC5LbgcnJZxkh4WmRbOJdklOxOu1b)
-->

#Presenting our paper on OCT interpetability in deep learning
<div align="center">
  <img width="100%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/DL4CV_Report_Guy_Lutsker_Hagai_Ravid-1.png">
</div>
<div align="center">
  <img width="100%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/DL4CV_Report_Guy_Lutsker_Hagai_Ravid-2.png">
</div>
<div align="center">
  <img width="100%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/DL4CV_Report_Guy_Lutsker_Hagai_Ravid-3.png">
</div>
<div align="center">
  <img width="100%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/DL4CV_Report_Guy_Lutsker_Hagai_Ravid-4.png">
</div>
<div align="center">
  <img width="100%" alt="Self-attention from a Vision Transformer with 8x8 patches trained with DINO" src="imgs/DL4CV_Report_Guy_Lutsker_Hagai_Ravid-5.png">
</div>

Some additional results can be viewed on my weights & biases server :
https://wandb.ai/guylu
