# Project_Style_Transfer
Implementation of Neural Style Transfer in Tensorflow + experimental feature for audio style transfer.

This app takes a 'content' image and adapts it with texture elements from a second image or sound file.

EXPERIMENTAL FEATURE: use an audio file in place of a style image. (This is implemented but still being tuned to produce meaningful results.)

- Try my web app implementation at www.communicatemission.com/ml-projects#style_transfer. (audio style not yet implemented)


 
-----
Credits / Attributions:

Using Audio as Style source:

- I have not seen this done before. The idea of representing audio as an image in order to apply visual network comes from *Deep Learning for Coders with fastai & Pytorch by Howard and Gugger (2020)*. (Original inverntor unknwon?)

Image Content & Style:

- This has been been coded heavily relying on utilizing techniques from DeepLearning.ai specialization on Coursera (www.coursera.org/learn/nlp-sequence-models) and the Tensorflow style transfer documentation (www.tensorflow.org/tutorials/generative/style_transfer), which are in turn based on a paper by Gatys, Ecker and Bethge *(https://arxiv.org/abs/1508.06576)*. 

- Pretrained image models used are loaded from the tf.keras.applications model. This model currently ustilizes VGG19 (citation: *Very Deep Convolutional Networks for Large-Scale Image Recognition (ICLR 2015))*

Web app:

- The web app is built on the Anvil platform.
