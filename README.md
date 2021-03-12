# Image & Audio Style Transfer
Implementation of Neural Style Transfer in Tensorflow + experimental feature for audio style transfer.

This app takes a 'content' (image / audio) and adapts it with texture elements from a second source (image / audio).

EXPERIMENTAL FEATURE: "audio" style transfer is now implemented in ipynb code but being tuned to produce more pleasing audio results.)

- Try my web app implementation at www.communicatemission.com/ml-projects#style_transfer. (audio style not yet implemented in app)


 
-----
Credits / Attributions:

Using Audio as Style source:

- I have not seen this done before. The idea of representing audio as an image in order to apply visual network comes from *Deep Learning for Coders with fastai & Pytorch by Howard and Gugger (2020)*. (Original inverntor unknwon?)

Image Content & Style:

- This has been been coded heavily relying on utilizing techniques from DeepLearning.ai specialization on Coursera (www.coursera.org/learn/nlp-sequence-models) and the Tensorflow style transfer documentation (www.tensorflow.org/tutorials/generative/style_transfer), which are in turn based on a paper by Gatys, Ecker and Bethge *(https://arxiv.org/abs/1508.06576)*. 

- Pretrained image models used are loaded from the tf.keras.applications model. This model currently ustilizes VGG19 (citation: *Very Deep Convolutional Networks for Large-Scale Image Recognition (ICLR 2015))*

Web app:

- The web app is built on the Anvil platform.

Images from Unpslash.com
- *<span><a href="https://unsplash.com/@abm25?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Aida Batres</a> on <a href="https://unsplash.com/@abm25?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@bmowinkel?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Brandon Mowinkel</a> on <a href="https://unsplash.com/@bmowinkel?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@autumnstudio?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Autumn Studio</a> on <a href="https://unsplash.com/@autumnstudio?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@joshhild?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Josh Hild</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Paweł Czerwiński</a> on <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@lucassankey?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Lucas Sankey</a> on <a href="https://unsplash.com/@lucassankey?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
- <span><a href="https://unsplash.com/@ivanana?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Ivana La</a> on <a href="https://unsplash.com/@ivanana?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
