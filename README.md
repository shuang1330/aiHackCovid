# aiHackCovid
### Team 5: Presentation
https://docs.google.com/presentation/d/1oaLLuYdHBaCXsbepXuGd3SX5yG5wN1tO0p2BLephV4E/edit?usp=sharing

# START HERE
First we would advise you to use conda and furthermore jupyter notebook. Further down in this document you can find the commands (on ubuntu) required to get to a working conda environment that is linked to jupyter notebook. 
But first you need to install conda and jupyter notebook:
## Jupyter
https://jupyter.org/

## Conda
### Linux
https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html

## Installing the conda requirements for the notebook
### Using pip
python -m venv hackathon
source hackathon/bin/activate
pip install -r requirements.txt

### Using conda
conda env create -f environment.yml

## Adding conda environment to jupyter notebook
 - open a terminal and activate desired environment
 
conda activate hackathon

conda install -c anaconda ipykernel

python -m ipykernel install --user --name=hackathon

## To be able to download jupyter notebook as pdf on ubuntu
sudo apt-get install texlive-xetex

# Example code
nb_versions/trifecta_notebooks -> The three notebooks can be found here.

## i)
The first notebook shows some simple ways of tackling the dataset and visualize the tables involved.

## ii)
The second notebook shows some simple plotting techniques and how to further investigate relationship between different variables.

## iii)
The third notebook shows how to deploy some statistical tests to try and prove some correlation between variables so as to build an argument or conclusion regarding the available data. 
