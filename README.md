# Audible HW
To reproduce this work:
1. Clone this repo
2. Download and unzip the datasets in the data folder (link in data/data.txt)
3. Create a conda env, run the following command lines:
	- conda create -n myenv python=3.7.2
	- while read requirement; do conda install --yes $requirement; done < requirements.txt 2>error.log
	- pip install --upgrade git+https://github.com/scikit-learn-contrib/categorical-encoding
	- jupyter notebook
4. Check and modify audible_imdb_challenge
