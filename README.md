# Location
nb_versions/trifecta_notebooks -> The three notebooks can be found here.

# aiHackCovid
Example Hackathon Submission

# Installing the conda requirements for the notebook
## Using pip
python -m venv hackathon
source hackathon/bin/activate
pip install -r requirements.txt

## Using conda
conda env create -f environment.yml

# Adding conda environment to jupyter notebook
 - open a terminal and activate desired environment
 
conda activate hackathon

conda install -c anaconda ipykernel

python -m ipykernel install --user --name=hackathon

# To be able to download jupyter notebook as pdf on ubuntu
sudo apt-get install texlive-xetex
