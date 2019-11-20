# My Experiments

This repository contains some code experiments and their corresponding notes and results. In addition, I am also listing some of my favorite publications here.


**Some of my favorite publications**

- Cubic Stylization [[November, 2019]](http://www.dgp.toronto.edu/projects/cubic-stylization/)

    This publication presents a 3D stylization algorithm that can turn a 3D input shape into the style of a cube while maintaining the content of the original shape. This article is playful, yet impressive.

    <img src="docs/cubic_stylization.jpg" height="200">


- In Silico Labeling: Predicting Fluorescent Labels in Unlabeled Images [[April 12, 2018]](https://ai.googleblog.com/2018/04/seeing-more-with-in-silico-labeling-of.html)

    This paper is an impressive use-case of machine learning to transform images from transmitted light microscopy (cheap) into color-annotated images as typically observed with fluorescence microscopy (more expensive), potentially removing the need for expensive technology.

    <img src="docs/in_silico_labeling.gif" height="250">


## Experiments

**3D Ken Burns Effect from a Single Image [[September 12, 2019]](https://arxiv.org/abs/1909.05483)**

<img src="docs/3dkenburns1.jpg" width="350"><img src="docs/3dkenburns1.gif" width="350">

<img src="docs/3dkenburns2.jpg" width="350"><img src="docs/3dkenburns2.gif" width="350">

**StyleGAN: A Style-Based Generator Architecture for Generative Adversarial Networks [[December 12, 2018]](http://stylegan.xyz/paper)**

Using the StyleGAN TensorFlow implementation, playing around with the latent vectorspace in the direction of age is easy. The predictions regarding 'me from the past' and 'future me' are pretty convincing, although clear artefacts are especially visible in hair.

![](docs/stylegan.gif)

