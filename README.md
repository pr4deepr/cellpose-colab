# Cellpose
**This notebook uses cellpose v2.3.2.**


2D Notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pr4deepr/cellpose-colab/blob/main/Cellpose_cell_segmentation_2D_prediction_only.ipynb)

Cellpose: Cellpose: https://github.com/MouseLand/cellpose

3D prediction is available  by the [ZeroCostDL4Mic team](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki). The notebooks are inspired by the [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) series of notebooks from the Henriques Lab and do borrow components from it as well. 


v0.5 update:
* 2024/04/09 Constrained cellpose version to be 2.3.2 to maintain compatibility.


v0.4 update:
* Fixed bug where new models could not be used for prediction


v0.3 update:
* Updated for Cellpose 2.0
* New models incorporated: https://cellpose.readthedocs.io/en/latest/models.html
* Parameters used in cellpose will be saved as a txt file (Thanks for suggestion Kota Miura)

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
