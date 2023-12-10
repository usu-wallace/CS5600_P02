# Project Overview

This is my final project for USU 5600 - Intelligent Systems. I will be training a neural network on this **Kaggle dataset** ([link](https://www.kaggle.com/competitions/titanic)). The purpose of this dataset is to determine whether someone on the Titanic disaster survived based on these inputs: `ticket` `class`, `sex`, `age`, `# of family aboard`, `ticket number`, `passenger fare`, `cabin number`, and `port of embarkation`.

## Dependencies

I will be using **Anaconda** ([link](https://www.anaconda.com/download/)) with windows WSL. Anaconda comes preinstalled with many libraries that are helpful for AI work. It is **HIGHLY RECCOMMENDED** that you install CUDA if your device is capable of it. Anaconda will install CUDA capable libraries, but you will need to install CUDA yourself from [here](https://developer.nvidia.com/cuda-toolkit-archive). The project will be done in a Jupyter notebook (comes with Anaconda) so make sure your IDE has support for them.

## Run Instructions

1. Open `project.ipynb` in your IDE that supports Jupyter notebooks

![](/doc/img/1.png)

2. Select the python interpreter from `anaconda` as the kernel to run the Jupyter notebook by:
    1. clicking the select kernel button in the top right corner (see image below)
    2. selecting the python interpreter with `anaconda` in the prompt that will appear in the top middle

![](/doc/img/2.png)

3. Press the following buttons in this order (see image):
    1. Clear all Outputs
    2. Restart
    3. Run all

![](/doc/img/3.png)

4. Wait until program finishes running. My computer took about 4 minutes, but your mileage may vary.

See `project.ipynb` for further details.