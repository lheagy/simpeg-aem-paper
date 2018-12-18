# Open source software for simulations and inversions of airborne electromagnetic data

Paper about airborne EM inversions with SimPEG. Submitted to Exploration Geophysics for the special edition to the Proceedings of the 2018 Conference on Airborne Electromagnetics held in Denmark.

## Abstract

Inversions of airborne EM data are often an iterative process, not only requiring that the researcher be able to explore the impact of changing components such as the choice of regularization functional or model parameterization, but also often requiring that forward simulations be run and fields and fluxes visualized in order to build an understanding of the physical processes governing what we observe in the data. In the hope of facilitating this exploration and promoting reproducibility of geophysical simulations and inversions, we have developed the open source software package, SimPEG. The software has been designed to be modular and extensible with the goal of allowing researchers to interrogate all of the components and to facilitate the exploration of new inversion strategies. We present an overview of the software in its application to airborne EM and demonstrate its use for visualizing fields and fluxes in a forward simulation as well as its flexibility in formulating and solving the inverse problem. We invert a line of airborne TDEM data over a conductive vertical plate using a 1D voxel-inversion, a 2D voxel inversion and a parametric inversion, where all of the forward modelling is done on a 3D grid. The results in this paper can be reproduced  by using the provided Jupyter notebooks. The Python software can also be modified to allow users to experiment with parameters and explore the physics of the electromagnetics and intricacies of inversion.

## Notebooks

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/heagy_2018_AEM/master)
[![Azure](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/simpeg-research/heagy_2018_emcyl)
[![Zenodo](https://zenodo.org/badge/124603211.svg)](https://zenodo.org/badge/latestdoi/124603211)

The examples shown were produced using the Jupyter notebooks available at: https://github.com/simpeg-research/heagy-2018-aem

## Citation

Coming soon... 
