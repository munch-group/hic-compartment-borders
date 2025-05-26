# Probabilistic Hi-C Compartment borders with PyMC

Rather than relying on the deterministic compartment assignments as from ICE, we place the E—the eigendecomposition—in a Bayesian framework. By modeling the eigenvector (E1) of the Hi-C contact matrix probabilistically, we aim to quantify uncertainty in compartment structure and more precisely localize boundaries. This approach replaces hard thresholding with posterior estimates of chromatin state, allowing a more flexible and interpretable view of genome organization.

The method is experimental and is meant to 

1) explore the usability of PyMC for Hi-C data,  
2) provide a probabilistic extension to the ICE method, establishing a confidence in the border prediction, and
3) provide a layer of meta data that can be interpreted when comparing transition zones with genomic regions of interest. 


# GH Pages

This repo is rendered and published using [Quarto](https://quarto.org/). The rendered site is available at [https://munch-group.org/hic-compartment-borders/](https://munch-group.org/hic-compartment-borders/).

![example event parameter](https://github.com/munch-group/hic-compartment-borders/actions/workflows/quarto-publish.yml/badge.svg?event=push)
