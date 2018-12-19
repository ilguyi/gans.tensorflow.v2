# Implementation of various GANs with TensorFlow version 2.0
* Final update: 2018.12. 20
* All right reserved @ Il Gu Yi 2018

This repository is a collection of various GAN models implemented by TensorFlow version 2.0 style.


## Getting Started

### Prerequisites
* `TensorFlow` above 1.12
* Python 3.6
* Python libraries:
  * `numpy`, `matplotlib`, `PIL`
* Jupyter notebook
* OS X and Linux (Not validated on Windows but probably it would work)



## Contents (TF version 2.x style)

### Generative Adversarial Networks
* Original GAN paper [arXiv:1406.2661](https://arxiv.org/abs/1406.2661)
* [gan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v2/gan.ipynb)





## Contents (TF version 1.x style)

### Generative Adversarial Networks
* Original GAN paper [arXiv:1406.2661](https://arxiv.org/abs/1406.2661)
* [gan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/gan.ipynb)
<div align="center">
<img src='./tf.v1/results/gan.result.ckpt.149969.jpg'>
</div>



### Deep Convolutional GAN
* Unsupervised Representation Learning with Deep Convolutional
Generative Adversarial Networks paper [arXiv:1511.06434](https://arxiv.org/abs/1511.06434)
* [dcgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/dcgan.ipynb)
<div align="center">
<img src='./tf.v1/results/dcgan.result.ckpt.28112.jpg'>
</div>


### Conditional GAN
* Conditional Generative Adversarial Nets [arXiv:1411.1784](https://arxiv.org/abs/1411.1784)
* [cgan_based_on_dcgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v1/blob/master/cgan_based_on_dcgan.ipynb)
<div align="center">
<img src='./tf.v1/results/cgan.result.ckpt.18745.jpg'>
</div>


### InfoGAN
* InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets [arXiv:1606.03657](https://arxiv.org/abs/1606.03657)
* [infogan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/infogan.ipynb)


### Bidirectional GAN
* Adversarial Feature Learning [arXiv:1605.09782](https://arxiv.org/abs/1605.09782)
* [bigan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/bigan.ipynb)


### Least Squares GAN
* Least Squares Generative Adversarial Networks [arXiv:1611.04076](https://arxiv.org/abs/1611.04076)
* [lsgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/lsgan.ipynb)


### Wasserstein GAN
* Wasserstein GAN [arXiv:1701.07875](https://arxiv.org/abs/1701.07875)
* [wgan.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/wgan.ipynb)


### Boundary Equilibrium GAN
* BEGAN: Boundary Equilibrium Generative Adversarial Networks [arXiv:1703.10717](https://arxiv.org/abs/1703.10717)
* [began.ipynb](https://nbviewer.jupyter.org/github/ilguyi/gans.tensorflow.v2/blob/master/tf.v1/began.ipynb)


### Author
Il Gu Yi
