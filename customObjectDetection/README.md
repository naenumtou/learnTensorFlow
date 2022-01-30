# ✍🏻 Custom object detection

![Google Colab](https://img.shields.io/badge/Editor-Google%20Colab-brightgreen)
![Python](https://img.shields.io/badge/Code-Python-blue)
![TensorFlow](https://img.shields.io/badge/Code-TensorFlow-blue)

<p align="center">
  <img src="https://miro.medium.com/max/2400/0*59hPdahQiz1dTmgV.jpg" alt="TensorFlow API V.1"/>
</p>

This repository contained model materials for TensorFlow API Verions 1.x. This materials are used for custom object detection model from pre-train Mobilenet v2 model.

## Model materials
* `TensorFlowAPI_Object.ipynb`: The Google Colab notebook to train custom object detection model.
* `TensorFlowAPI_ObjectPredict.ipynb`: The Google Colab notebook to use (prediction) custom object detection model.
* `generate_tfrecord.py`: Python script to generate TensorFlow record (TFRecord). This is to feed into neural network.
* `ssd_mobilenet_v2_coco.config`: The SSD with Mobilenet v2 configuration.
* `xml_to_csv.py`: The converter `.xml` location files of object target to `.csv` format. 

## Sample model results
<p align="center">
<img src="https://miro.medium.com/max/1400/1*rnO7YZWf483apbKNvsAIBw.png" alt="TensorFlow API V.1"/><br/><br/>
<img src="https://miro.medium.com/max/450/1*m2mk36exoi6TUjdxeLypeA.png" alt="TensorFlow API V.1"/><br/><br/>
<img src="https://miro.medium.com/max/450/1*zeSBNd5FuIHtpdz1xMTABQ.png" alt="TensorFlow API V.1"/><br/><br/>
<img src="https://miro.medium.com/max/450/1*JtyLMdfccMbDd8CW1TJDhw.png" alt="TensorFlow API V.1"/><br/><br/>
</p>
