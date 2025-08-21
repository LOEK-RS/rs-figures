This repository contains figures and the corresponding R code to reproduce them from the Research group of Remote Sensing and Spatial Modelling, Institute of Landscape Ecology, University of Münster.

## Gallery

### CV figures (`src/cv_figures.qmd`)

**Comparison of random and clustered sampling designs and their effects on distance distributions and cross-validation.**
**[Panel a) shows sampling locations for two different designs: random and clustered. Panel b) shows the respective density distributions of nearest-neighbor distances between samples (green), between prediction points and samples (orange) and between cross-validation (CV) folds. For randomly distributed samples, the CV-distances closely resemble the prediction distances. For clustered sampling, however, the CV-distances are much shorter, and thus won't yield reliable estimates of map accuracy.]**
![geodist_sim.png](figures/geodist_sim.png)

## License

All figures are available under the  
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/).  

This means you are free to **share and adapt** them, as long as proper attribution is given.  

## Citation

If you use material from this repository, please provide proper attribution.
Each figure and corresponding R script may have **different authors**.
Please check the metadata (author information provided with each figure/script) and cite accordingly.

For example, if you use a specific figure, you can cite it like this:

```
Author(s) (YEAR). "Figure Title." In: rs-figures: Figures and R Code for Reproducible Research. Research Group of Remote Sensing and Spatial Modelling, Institute of Landscape Ecology, University of Münster. Available at: https://github.com/LOEK-RS/rs-figures. License: CC BY 4.0
```

Or you can use the following BibTeX entry as a template:

```bibtex
@misc{rs_figures_<shortid>,
  author       = {Author(s)},
  title        = {{Figure Title} [Figure]},
  year         = {Year},
  editor       = {{Research Group of Remote Sensing and Spatial Modelling}},
  institution  = {Institute of Landscape Ecology, University of Münster},
  howpublished = {\url{https://github.com/LOEK-RS/rs-figures}},
  note         = {Licensed under CC BY 4.0}
}
```