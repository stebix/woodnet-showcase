# `woodnet` Showcase

This repository containes additional showcase information in the form of tutorials and visualizations for our IAWA paper manuscript "Technical framework presentation of advanced volumetric sub-μ-CT imaging integrated with adaptable deep learning-based wood species classification" and the accompanying advanced computed tomography data processing and classification pipeline [`woodnet`](https://github.com/stebix/woodnet).
The visualizations are bundled into a Jupyter notebook that can be viewed and handled interactively. Core showcased elements are 3D volumetric visualizations that are not a good fit for paper- and PDF-based static imagery.
To look at the generated visualizations and explantations, please launch the binder notebook direcntly in your browser via the button below:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stebix/woodnet-showcase/HEAD?labpath=showcase-visualization.ipynb)

The secondary turorial is concerned with a short explanation of the default data layout utilized in the `woodnet` data processing and classification pipeline. It also contains a demonstrative forward pass of the data through an example network. For this, use the secondary link:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stebix/woodnet-showcase/HEAD?labpath=showcase-prediction.ipynb)
To ultimately run the code in the provided notebooks, please select 'Run' $\rightarrow$ 'Run All Cells' in the drop down menu bar after the notebook has opened. 
> [!TIP]
> Binder only provides CPU compute resources for the notebooks. Using a CPU with volumetric data and 3D ResNet can be slow.
> If the compute resources or your patience time out, just use the Jupyter notebook as a starting point for running experiments
> on your own premises using a faster GPU resource.

## Informations

- Supplementary to IAWA Journal submission [TODO: INSERT DOI] by Jannik Stebani, Tim Lewandrowski, Kilian Dremel, Simon Zabler and Volker Haag
- Supplementary to [`woodnet`](https://github.com/stebix/woodnet) package
- Documentation for `woodnet` package online at [read-the-docs](https://woodnet.readthedocs.io/en/latest/)
