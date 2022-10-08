---
layout: default
grid: toolboxes
modal-id: 4
date: 2000-01-01
img: Slide5.png
alt: image-alt
---

<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>

[pdfm]: https://img.shields.io/badge/PDF-Manuscript-brightgreen?style=flat-square#badge
[pdfs]: https://img.shields.io/badge/PDF-Supplement-brightgreen?style=flat-square#badge
[pre]: https://img.shields.io/badge/Link-Preprint-yellow?style=flat-square#badge
[zen]: https://img.shields.io/badge/Link-Zenodo-0475B6?style=flat-square#badge
[git]: https://img.shields.io/badge/Link-GitHub-black?style=flat-square#badge
[pub]: https://img.shields.io/badge/Link-Publisher-orange?style=flat-square#badge
[tw]: https://img.shields.io/badge/Link-Thread-1A8CD8?style=flat-square#badge

#### A toolbox for ensemble-based multimodal gene-category enrichment analysis of human neuroimaging data
 
ABAnnotate is a Matlab-based toolbox to perform ensemble-based gene-category enrichment analysis (GCEA) on volumetric human neuroimaging data via brainwide gene expression patterns derived from the Allen Human Brain Atlas. It applies a nonparametric method developed by [Fulcher et al. (2021)](https://doi.org/10.1038/s41467-021-22862-1) using spatial autocorrelation-corrected phenotype null maps for the estimation of gene-category null ensembles.  
Effectively, with ABAnnotate you can answer the question: "Is this brain map that I have here spatially related to, e.g., a certain neuronal cell type?". All you have to do is put your brain map into a minimum of three lines of Matlab code, choose the GCEA dataset (e.g., cell types) that interests you and run the toolbox. What you get is a set of association scores and a nonparametric corrected *p* values associating your brain map with each GCEA category (e.g., cell type). Read more in the [repository](https://github.com/LeonDLotter/ABAnnotate), in [this example case](https://github.com/LeonDLotter/ABAnnotate/blob/v0.1.0/example/example_pain.md), or our [recent publication](https://doi.org/10.1101/2022.07.26.501562) for which the toolbox was initially developed.

[![github][git]](https://github.com/LeonDLotter/ABAnnotate)
[![zenodo][zen]](https://doi.org/10.5281/zenodo.6463328)
[![tweet][tw]](https://twitter.com/LeonDLotter/status/1516430125142888467)
[![git forks](https://img.shields.io/github/forks/LeonDLotter/ABAnnotate.svg?style=social&label=Fork&maxAge=2592000#badge)](https://GitHub.com/LeonDLotter/JuSpyce/network/)
[![git forks](https://img.shields.io/github/stars/LeonDLotter/ABAnnotate.svg?style=social&label=Star&maxAge=2592000#badge)](https://GitHub.com/LeonDLotter/JuSpyce/stargazers/) 
