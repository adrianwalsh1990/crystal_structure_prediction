# Crystal Structure Prediction

This project introduces a way to perform fast prediction of crystal structure information (Bravais lattice and point group symmetries) from a set of atomic positions using a series of PointNet models.


# Installation
All of the notebooks are designed to work in google colab. The train notebooks should be run using the GPU hardware accelerator and high-ram memory option (if using colab pro).
The predict notebook can be run without the hardware acceleration.


#Usage
The project contains three notebooks, a series of datasets and pretrained model weights. 

For basic usage open the ![Crystal_Predict](https://colab.research.google.com/github/adrianwalsh1990/crystal_structure_prediction/blob/main/Crystal_Predict.ipynb) notebook. Enter the atomic positions and crystal system. The Bravais lattice and point group symmetries will then be predicted. 

The models can be retrained with the ![Pointgroup_train](https://colab.research.google.com/github/adrianwalsh1990/crystal_structure_prediction/blob/main/PointGroup_train.ipynb) and ![Bravais_train](https://colab.research.google.com/github/adrianwalsh1990/crystal_structure_prediction/blob/main/Bravis_train.ipynb). The datasets for these models are downloaded from ![Materials Project](materialsproject.org).


# Networks 
The networks are designed from the ![PointNet](https://stanford.edu/~rqi/pointnet/) model.
