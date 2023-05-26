# Offline Jupyter Notebooks
Instead of using Google Colab, offline versions of the notebooks have been made available in this directory and can be run through the conventional Jupyter IDE. Instructions for setting up the conda virtual environment are provided here and have been verified to work on wsl-Ubuntu 22.04 using the Firefox browser. 
## Conda Instructions
1. Create a conda virtual environment 
```
conda create --name DFT_code python=3.10
```
1. Install dependencies to this environment from the requirements.txt file.
```sh
conda activate DFT_code
pip install -r requirements.txt
```
1. Launch a Jupyter notebook instance.
```sh
jupyter notebook
```
1. Download the offline versions of the notebooks and open them through the Jupyter IDE. The visualizations should become active after executing the code cells.

![MyImage](https://www.neuralnine.com/wp-content/uploads/2020/07/cropped-Design-ohne-Titel-1-2.png)
