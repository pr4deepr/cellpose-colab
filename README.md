# Cellpose
Google Colab notebooks for prediction using cellpose (v2.0).
This currently only supports 2D prediction

2D Notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pr4deepr/cellpose-colab/blob/main/Cellpose_cell_segmentation_2D_prediction_only.ipynb)

Cellpose: Cellpose: https://github.com/MouseLand/cellpose


3D prediction is available  by the [ZeroCostDL4Mic team](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki). The notebooks are inspired by the [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) series of notebooks from the Henriques Lab and do borrow components from it as well. 


v0.3 updates:
* Updated for Cellpose 2.0
* Added the new models in the notebook
* Fixed a numpy error when installing cellpose in colab environment. Fix is to restart colab after installing cellpose
* Parameters.txt file gets saved in output folder so as to record the parameters used for cellpose prediction

***********************
## Running cellpose and colab on local conda installation

This is mainly if you'd like to train data using your PC resources
Installation instructions are provided in the notebook below. The _cellpose_colab_local.yml_ file provided here is only for **upgrading** the existing cellpose environment.
Check the notebook below for more info.

2D Notebook_local_environment (run locally on a PC): [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pr4deepr/cellpose-colab/blob/main/Cellpose_2D_run_on_local_environment.ipynb)

This is not guaranteed to work on every system. If you have an error:

_ImportError: Numba needs NumPy 1.21 or less_

Run:

pip install numpy==1.21
