# BFPy Library
Collection of software developed during my Master Thesis.
For further information, refer to my Master Thesis

## IMPORTANT: updated installation procedure below

The specified installation instructions in the printed vesion of the Master Thesis are no longer supported.
Note: Anaconda is required for this procedure. You can obtain your copy here: https://www.anaconda.com/products/distribution#Downloads

Then follow these steps:

1. navigate to lcoal directory on you machine, in which the repository is to be cloned into (where it will be stored)
2. If you have git installed, skip this step. Otherwise, in the Anaconda prompt (Windows) or terminal (Linux, MacOS) type the following, then hit return: conda install -c anaconda git
4. type the following, then hit return: git clone https://github.com/nfb2021/PlasmonicalPy.git
5. type the following, then hit return: cd PlasmonicalPy
6. type the following, then hit return: conda env create -f environment.yml
7. type the following, then hit return: conda activate PlasmonicalPy
8. type the following, then hit return: cd opencv_superres_models
9. type the following, then hit return: git clone https://github.com/Saafke/FSRCNN_Tensorflow.git
10. type the following, then hit return: git clone https://github.com/Saafke/EDSR_Tensorflow.git
11. Move the pre-trained models from their correponsing directories "opencv_superres_models/xxx/models" into "opencv_superres_models"
