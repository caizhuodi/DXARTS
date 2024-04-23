# DreamBooth

The following is based on `text2image-DreamBooth_Stable_Diffusion-Juan-large.ipynb`.

## dataset sample
![image](https://github.com/caizhuodi/DXARTS/blob/main/DreamBooth-image2image/asset/dreambooth0-J-datasetsample.png)

## explaination
![image](https://github.com/caizhuodi/DXARTS/blob/main/DreamBooth-image2image/asset/dreambooth1-J.jpg)

## results
![image](https://github.com/caizhuodi/DXARTS/blob/main/DreamBooth-image2image/asset/dreambooth2-J.jpg)

## video

The following is based on `text2image-DreamBooth_Stable_Diffusion-Juan.ipynb`.

### inference approach B, seed control randomness & still images & video
<p align="center">
  <img src="https://github.com/caizhuodi/DXARTS/blob/1d0d3b9f5404fa76dbac00eff91762f5ec6a61bb/DreamBooth-image2image/asset/dreambooth3-T-process.gif" alt="animated" />
</p>

https://github.com/caizhuodi/DXARTS/blob/48a75ca1b37dd4632571acc096ba2362bc2bada6/DreamBooth-image2image/asset/dreambooth3-T-process.mp4

### inference approach C, generate from an image input & seed control randomness & still images & video
<p align="center">
  <img src="https://github.com/caizhuodi/DXARTS/blob/1d0d3b9f5404fa76dbac00eff91762f5ec6a61bb/DreamBooth-image2image/asset/dreambooth3-T-process.gif" alt="animated" />
</p>

https://github.com/caizhuodi/DXARTS/blob/48a75ca1b37dd4632571acc096ba2362bc2bada6/DreamBooth-image2image/asset/dreambooth3-T-process.mp4

## notice
1. Change `num_class_images` according to your own dataset.
2. Keep your dataset image size (width x height) the same, and the size in inference section should be set accordingly, otherwise it will lead to poor results.