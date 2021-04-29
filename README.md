# aiHackCovid
Example Hackathon Submission

# Installing the conda requirements for the notebook
python -m venv hackathon
source hackathon/bin/activate
pip install -r requirements.txt

# Adding conda environment to jupyter notebook
 - open a terminal and activate desired environment
 
conda activate hackathon
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=hackathon
