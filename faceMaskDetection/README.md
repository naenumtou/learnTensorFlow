# ✍🏻 Real-time face mask detection

![Google Colab](https://img.shields.io/badge/Editor-Google%20Colab-brightgreen)
![Python](https://img.shields.io/badge/Code-Python-blue)
![TensorFlow](https://img.shields.io/badge/Code-TensorFlow-blue)

<p align="center">
  <img src="https://www.surveillance-video.com/media/catalog/product/cache/c01a9be670ea9db53792e63d854bd9d2/image/1304310da6/samsung-op-a2fmd-01-face-mask-detection-application-op-a2fmd-01.jpg" alt="Real-time face mask detection"/>
</p>

This repository contained --.

## Model materials
* `TensorFlowAPI_Object.ipynb`: The Google Colab notebook to train custom object detection model.
* `TensorFlowAPI_ObjectPredict.ipynb`: The Google Colab notebook to use (prediction) custom object detection model.
* `generate_tfrecord.py`: Python script to generate TensorFlow record (TFRecord). This is to feed into neural network.
* `ssd_mobilenet_v2_coco.config`: The SSD with Mobilenet v2 configuration.
* `xml_to_csv.py`: The converter `.xml` location files of object target to `.csv` format. 

## Sample model results
<p align="center">
<a href="https://imgbb.com/"><img src="https://i.ibb.co/hHv96VC/1.png" alt="Real-time face mask detection" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/hmj2v8g/2.png" alt="Real-time face mask detection" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/QFs4mNq/3.png" alt="Real-time face mask detection" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/cTQXSwS/4.png" alt="Real-time face mask detection" border="0"></a>
<a href="https://ibb.co/TYYfbLG"><img src="https://i.ibb.co/sbbf6H4/5.png" alt="Real-time face mask detection" border="0"></a>
<a href="https://ibb.co/mTN8pjN"><img src="https://i.ibb.co/7Ck4hfk/6.png" alt="Real-time face mask detection" border="0"></a>
</p>

## Full video results
1. https://youtu.be/I0F2UCaSqw8
2. https://youtu.be/Hkc9g2a1yXI
3. https://youtu.be/hfcz7A5DCV8
4. https://youtu.be/Bi6HnDc7wtw
