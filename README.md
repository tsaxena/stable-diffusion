# Stable Diffusion

#### Unofficial Implementation of Stable Diffusion

This repo is a copy of [Stable Diffusion ](https://github.com/CompVis/stable-diffusion/tree/main) for self learning and running some experiments with Stable Diffusion.

Thus, the repo aims to reproduce SD on different generation task. I highly recommend you to read the config to understand each fuction.

* [Task0 Autoencoder finetuning](#Unconditional)
* [Task1 Unconditional Image Synthesis](#Unconditional)
* [Task2 Class-conditional Image Synthesis](#Class-conditional)
* [Task3 Inpainting](#Inpainting)
* [Task4 Super-resolution](#Super-resolution)
* [Task5 Text-to-Image](#Text-to-Image)
* [Task6 Layout-to-Image Synthesis](#Layout-to-Image)
* [Task7 Semantic Image Synthesis](#Semantic-to-Image)
* [Task8 Image-to-Image](#Image-to-Image)
* [Task9 Depth-to-Image](#Depth-to-Image)

If you find it useful, please cite their original paper.

[arXiv](https://arxiv.org/abs/2112.10752) | [BibTeX](#bibtex)

<p align="center">
<img src=assets/results.gif />
</p>



[**High-Resolution Image Synthesis with Latent Diffusion Models**](https://arxiv.org/abs/2112.10752)<br/>
[Robin Rombach](https://github.com/rromb),
[Andreas Blattmann](https://github.com/ablattmann),
[Dominik Lorenz](https://github.com/qp-qp),
[Patrick Esser](https://github.com/pesser),
[Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer)<br/>

<p align="center">
<img src=assets/modelfigure.png />
</p>


## Requirements
A suitable [conda](https://conda.io/) environment named `ldm` can be created
and activated with:

```
conda env create -f environment.yaml
conda activate ldm
```

## Pretrained Models
A general list of all available checkpoints is available in via our [model zoo](#model-zoo).
If you use any of these models in your work, we are always happy to receive a [citation](#bibtex).




