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
  <img src="https://github.com/caizhuodi/DXARTS/blob/093bb18f8332f6ec1d045d88eb60a0e931626e35/DreamBooth-image2image/asset/dreambooth3-J-process-output_video_converted.gif" alt="animated" />
</p>

https://github.com/caizhuodi/DXARTS/blob/50b242311483b78b4faf89292e424f3bba8b2225/DreamBooth-image2image/asset/dreambooth3-J-process-output_video_converted.mp4

### inference approach C, generate from an image input & seed control randomness & still images & video
<p align="center">
  <img src="https://github.com/caizhuodi/DXARTS/blob/093bb18f8332f6ec1d045d88eb60a0e931626e35/DreamBooth-image2image/asset/dreambooth3-J-process-output_video_converted_C.gif" alt="animated" />
</p>

https://github.com/caizhuodi/DXARTS/blob/50b242311483b78b4faf89292e424f3bba8b2225/DreamBooth-image2image/asset/dreambooth3-J-process-output_video_converted_C.mp4

## notice
1. Change `num_class_images` according to your own dataset.
2. Keep your dataset image size (width x height) the same, and the size in inference section should be set accordingly, otherwise it will lead to poor results.