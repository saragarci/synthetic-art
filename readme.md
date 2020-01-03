# Synthetic Art

Unsupervised machine learning system that can generate synthetic paintings based on art work using DCGAN.

## Setting up you environment

### Dependencies

The following packages need to be installed:

```
torch
torchvision
numpy
matplotlib
IPython
image_slicer
PIL
```

### Project structure

To use the notebooks, the following directory structure is expected:

```
data/celeba
	/digit_generation/samples
	/wiki_art
```

## References

### Datasets

* [Large-scale CelebFaces Attributes (CelebA) Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

```
@inproceedings{liu2015faceattributes,
 title = {Deep Learning Face Attributes in the Wild},
 author = {Liu, Ziwei and Luo, Ping and Wang, Xiaogang and Tang, Xiaoou},
 booktitle = {Proceedings of International Conference on Computer Vision (ICCV)},
 month = {December},
 year = {2015} 
}
```

* [The MNIST database of handwritten digits](http://yann.lecun.com/exdb/mnist/)
* [Database of abstract art work from the Wikiart.org](https://drive.google.com/file/d/1MgWdaz6aNW7GfSrKHw54tyqPF2pacjhD/view?usp=sharing)

Notice that the notebooks already inclue the process of downloading each required dataset, so you don't have to download them in advanced but only as you go through them.

### Used resources

* https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html
* https://arxiv.org/pdf/1511.06434.pdf
* https://www.kaggle.com/dsaichand3/mnist-classifier-in-pytorch

### Further reading

* https://chainer-colab-notebook.readthedocs.io/en/latest/notebook/official_example/dcgan.html
* https://towardsdatascience.com/gangogh-creating-art-with-gans-8d087d8f74a1
* https://pathmind.com/wiki/generative-adversarial-network-gan
* https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf
* https://arxiv.org/pdf/1906.01529.pdf
* https://github.com/nashory/gans-awesome-applications
* https://medium.com/@jonathan_hui/gan-some-cool-applications-of-gans-4c9ecca35900

### Contributors

* [Sara Garci](s@saragarci.com)

## License

© Copyright 2019 by Sara Garci. All rights reserved.
