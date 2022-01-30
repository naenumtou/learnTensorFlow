# ✍🏻 Real-time face mask detection

![Google Colab](https://img.shields.io/badge/Editor-Google%20Colab-brightgreen)
![Python](https://img.shields.io/badge/Code-Python-blue)
![TensorFlow](https://img.shields.io/badge/Code-TensorFlow-blue)

<p align="center">
  <img src="https://www.surveillance-video.com/media/catalog/product/cache/c01a9be670ea9db53792e63d854bd9d2/image/1304310da6/samsung-op-a2fmd-01-face-mask-detection-application-op-a2fmd-01.jpg" alt="Real-time face mask detection"/>
</p>

This repository contained face mask detection model. The overall process is to use transfer learning to build the object detection model to detect the face mask. Then, it will be appiled on the video by using `faceNet` to help for face detection prior appiled face mask trained model. 

## Model materials
* `face_mask.model`: The trained face mask detection model.
* `faceMaskDetection.ipynb`: The Google Colab notebook to develop face maks detection model.
* `res10_300x300_ssd_iter_140000.caffemodel`: The faceNet model to help for face detection prior apply face mask detection model.
* `deploy.prototxt.txt`: The faceNet config file.
* `faceMaskVideo.ipynb`: The Google Colab notebook to use face mask detection model with video files. 

## Sample model results
<p align="center">
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/9FQf7Kyd/1.png" alt="Real-time face mask detection"/></a><br/><br/>
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/pL9X0jGy/2.png" alt="Real-time face mask detection"/></a><br/><br/>
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/NfCj7DxW/3.png" alt="Real-time face mask detection"/></a><br/><br/>
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/qv9BW7Sw/4.png" alt="Real-time face mask detection"/></a><br/><br/>
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/MGVZwS8S/5.png" alt="Real-time face mask detection"/></a><br/><br/>
<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/d1FstxqT/6.png" alt="Real-time face mask detection"/></a><br/><br/>
</p>

## Full video results
1. https://youtu.be/I0F2UCaSqw8
2. https://youtu.be/Hkc9g2a1yXI
3. https://youtu.be/hfcz7A5DCV8
4. https://youtu.be/Bi6HnDc7wtw
