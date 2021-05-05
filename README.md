Run using mybinder
------------------
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JoaoSantinha/SIIM21_BIP/HEAD)

Run Jupyter Notebooks locally - Installation and Jupyter notebook launch
------------

1. To set the virtual environment to run this tutorial we will use conda. If you do not have you can install one of these two options:
  - [Anaconda (management system with some packages already built in)](https://docs.anaconda.com/anaconda/install/)
  - [Miniconda (management system without packages)](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

2. Clone this repository or download the .zip file to your documents folder (to clone the repository you need to have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) install): 
  - clone repository in Windows using the following commands on your command line (replace <current_user> by your user name):
  ```
    cd C:\Users\<current_user>\Documents\
    git clone https://github.com/JoaoSantinha/SIIM21_BIP.git
  ```
  - clone repository in Mac/Linux using the following commands on your terminal:
  ```
    cd ~/Documents
    git clone https://github.com/JoaoSantinha/SIIM21_BIP.git
  ```

3. Then create environment (called SIIM_BIP) and install required packages automatically:
  ```
    cd SIIM21_BIP
    conda env create -f environment.yml
  ```
  
4. Activate environment and start jupyter notebook:
  ```
    conda activate SIIM_BIP
    jupyter notebook
  ```
