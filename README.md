<div align="center">
    <h1>Tree Crown Detection</h1>
</div>

<p align="center">
    <a href="https://github.com/scivision-gallery/tree-crown-detection/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="https://mybinder.org/v2/gh/scivision-gallery/tree-crown-detection.git/main?labpath=tree-crown-detection.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/scivision-gallery/tree-crown-detection/workflows/ci/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/scivision-gallery/tree-crown-detection/workflows/ci/badge.svg">
    </a>
    <br/>
</p>

<p align="center">
  <img src="https://github.com/scivision-gallery/tree-crown-detection/blob/main/figs/detectreeRGB_prediction_example.png?raw=true" 
        alt="Tree crown delineation in a sample drone RGB image" width="90%" align="center">
</p>

<p align="center">
    <em>
    Tree crown delineation in a sample drone RGB image. 
    </em>
</p>

## Abstract
The delineation of individual trees in remote sensing images is an key task in forest analysis. As part of Sebastian Hickman's AI4ER MRes project, titled 'Detecting changes in tall tree height with machine learning, LiDAR, and RGB imagery', the authors propose the `detectreeRGB` model, an implementation of Mask R-CNN from [Detectron2](https://github.com/facebookresearch/detectron2) to perform tree crown delineation from RGB imagery.

In this notebook, we demonstrate how `scivision` can assist in discovering a pretrained `detectreeRGB` model provided by Hickman et al (2021), and then use it to delineate crowns from a sample drone RGB image dataset.

Further details of the detectreeRGB can be found in the [original model repository](https://github.com/shmh40/detectreeRGB).

## How to run

The notebook is designed to be launched from Binder.
* Click the **Launch Binder** button at the top level of the repository

You may also download the notebook from GitHub to run it locally:
* Open your terminal
* Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))
* Clone the repository, `https://github.com/scivision-gallery/treecrown-detection_detectreeRGB.git` 
* Move into the cloned repository, `cd treecrown-detection_detectreeRGB`
* Install the dependencies, `conda env create -f environment.yml`
* Activate the installed environment, `conda activate treecrown-detection_detectreeRGB`
* Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

## Acknowledgment 
This notebook was supported by the outcomes of Sebastian Hickman's [AI4ER MRes project](https://ai4er-cdt.esc.cam.ac.uk/StaffDirectory/students-all/2020-students). The scivision team thanks the individuals and institutions involved in the project, in particular Sebastian for providing one of the trained models and sample images used in this notebook.

## Resources
* [DetectreeRGB model repository](https://github.com/shmh40/detectreeRGB)