# Cellpose
Google Colab notebooks for prediction using cellpose.

Currently, only have the 2D prediction. 
Future plans are to include 3D predictions and possibly options for training data

2D Notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/pr4deepr/cellpose-colab/blob/main/Cellpose_cell_segmentation_2D_prediction_only.ipynb)


Cellpose: Cellpose: https://github.com/MouseLand/cellpose

**UPDATE: ZeroCostDL4Mic has [cellpose training and prediction notebooks](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) with the option for 3D**

The notebooks are inspired by the [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki) series of notebooks from the Henriques Lab and do borrow components from it as well. 


v0.2 updates:
* Added the new models in the notebook
* Fixed a numpy error when installing cellpose in colab environment. Fix is to restart colab after installing cellpose
* Parameters.txt file gets saved in output folder so as to record the parameters used for cellpose prediction

