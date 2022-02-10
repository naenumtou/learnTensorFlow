# ✍🏻 COVID-19 X-Ray film classification model with LIME Explainer

![Google Colab](https://img.shields.io/badge/Editor-Google%20Colab-brightgreen)
![Python](https://img.shields.io/badge/Code-Python-blue)
![TensorFlow](https://img.shields.io/badge/Code-TensorFlow-blue)

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*Wnhp24Yr4eeQxKZZrsjxNA.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/>
</p>

This repository contained the process of LIME Explanation. Begin with generating images dataset, which are including films X-Ray of COVID-19 cases and normal cases. Followed by the training model processes, which are including create new CNN Model and transfer-learning with pre-trained model. At last, using LIME Explainer to see inside the model black-box.

## Model materials
* `XRayImageGen.ipynb`: The dataset generator using films X-Ray of COVID-19 cases and normal cases. The image processing is to fit with Xception pre-trained model from Keras.
* `COVIDXRayTrainingModel.ipynb`: The model classification training process. There are two trained models, which are simple CNN Model and transfer-learning with Xception.
* `LIMEImageExplainer.ipynb`: The model explanation using LIME. It looks inside the black-box of models and create interpretability concept of classifier. 

## Sample LIME Explainer results
<p align="center">
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/1RvKnCjc/1.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>CNN Model: Correctly predict COVID-19 case<br/>
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/rsZGBsrY/2.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>Xception Model: Correctly predict COVID-19 case<br/>
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/j2SQ3PL7/3.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>CNN Model: Correctly predict normal case<br/>
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/nzkG10cx/4.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>Xception Model: Correctly predict normal case<br/>
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/MTxYRhwt/5.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>CNN Model: Correctly predict COVID-19 cases<br/>
  <a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/zfTjyqsV/6.png" alt="COVID-19 X-Ray film classification model with LIME Explainer"/></a><br/>Xception Model: Incorrectly predict COVID-19 case (predicted as normal case)<br/>
</p>
