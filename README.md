# ✍🏻 The learning processes of TensorFlow

![Google Colab](https://img.shields.io/badge/Editor-Google%20Colab-brightgreen)
![Python](https://img.shields.io/badge/Code-Python-blue)
![TensorFlow](https://img.shields.io/badge/Code-TensorFlow-blue)

<p align="center">
  <img src="https://cdn.dribbble.com/users/166244/screenshots/6167826/tf_dribbb.png" alt="TensorFlow learning"/>
</p>

The learning TensorFlow repository is contained the Google Colab notebooks that have been using TensorFlow to develop the model. This is covered various areas such as Computer Vision (Object detection, Recognition), Natural language processing (NLP), etc.

## Image classification
* `X_rayCOVIDClassification.ipynb`: Using CNN Model to classify COVID-19 film X-Ray out ot normal cases.
* `COVIDXRay`: Re-training COVID-19 film X-Ray classificaiton model with CNN Model and Xception pre-trained model. The python `LIME` library has been leveraged for image explanation.

## Object detection
* `LeicaModel`: The custom object detection with YOLO V3.
* `customObjectDetection`: The custom object detection project using TensorFlow API Version 1.
* `faceMaskDetection`: The custom object detection of face mask image using MobileNetV2 Pre-trained model. The trained model is used for detection face mask on image or vedio.

## Object recognition
* `OCRModel.ipynb`: Developed the Optical Character Recognition (OCR) Model to recognise image handwriting.
* `autoencoder_face.ipynb`: Using Auto-Encoder to reconstruct face images.
* `OCRResNet50.ipynb`: Developed the Optical Character Recognition (OCR) using transfer learning with ResNet50 pre-trained model.
* `OCRUsed.ipynb`: The usage of the Optical Character Recognition (OCR) using trained model by ResNet50 pre-trained model.

## Financial model
* `autoencoders_fraud_detection.ipynb`: Using Auto-Encoder to detect fraud in the credit card dataset.

## Natural language processing (NLP)
* `word2vec.ipynb`: Using Long Short-Term Memory (LSTM) to classify news topics.
* `childrenQuotation.ipynb`: Text generator NLP Model using LSTM. It is to generate children's day quotation in Thailand.

## Others
* `colabTPU.ipynb`: The experiment to use TPU for model training.
* `linearRegression.ipynb`: Building linear regression model in TensorFlow.
