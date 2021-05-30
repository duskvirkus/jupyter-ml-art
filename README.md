# Jupyter ML Art Notebooks

A collection of my machine learning art notebooks. Setup to be run locally on linux machine with anaconda.

## Setup

```bash
#install anaconda if not already installed

git clone https://github.com/duskvirkus/jupyter-ml-art
cd jupyter-ml-art

conda create -n jupyter-ml-art python=3.9
conda activate jupyter-ml-art
conda install -c conda-forge jupyterlab
conda install -c anaconda ipykernel

python -m ipykernel install --user --name=jupyter-ml-art

conda install libgcc
pip install -r requirements.txt

jupyter-lab
```