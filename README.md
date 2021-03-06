# PyTorch Offline Documentation

[![numpy version](https://badgen.net/badge/NumPy%20version/v1.18.1/black?icon=dockbit)](https://github.com/numpy/numpy)
[![scikit-learn version](https://badgen.net/badge/Scikit-learn%20version/v0.22/black?icon=libraries)](https://github.com/scikit-learn/scikit-learn/releases/tag/0.22)
[![torch version](https://img.shields.io/badge/torch_version-v1.5.0-282828.svg?labelColor=4F4F4F&logo=PyTorch)](https://github.com/pytorch/pytorch)
[![torchvision version](https://img.shields.io/badge/torchvision_version-v0.6.0-282828.svg?labelColor=4F4F4FF&logo=PyTorch)](https://github.com/pytorch/vision)

Offline documentation built from official [NumPy](https://github.com/numpy/numpy.git), [Scikit-learn](https://github.com/scikit-learn/scikit-learn), [PyTorch](https://github.com/pytorch/pytorch.git) and [torchvision](https://github.com/pytorch/vision.git) release. The documentations of pytorch and torchvision are separate.

Offline documentation does speed up page loading, especially for some countries/regions.

This repo helps to relieve the pain of building PyTorch offline documentation.

No need to clone the huge PyTorch repo. No need to install Sphinx. No need to wait for searching.

## How to use

You can download from [release page](https://github.com/unknownue/PyTorch.docs/releases)(recommended), or clone this repo(about 100+MB) by

```shell
$ git clone https://github.com/unknownue/PyTorch.docs.git
```

The documentation of PyTorch is in `torch` directory, and that of torchvision is in `torchvision` directory. 

Open `Index.html` to view the documentation.

If you want to build by yourself, the `build` directory contains the build configuration in docker.