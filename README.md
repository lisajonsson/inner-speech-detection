# inner-speech-detection

Wat I did to make it run:

Download all 3 N-Nieto git repositorys.
Install miniconda.
create conda environment for Inner_Speech_Dataset with *conda env create -f environment.yml*
register the conda environment as jupyter kernel with *python -m ipykernel install --user --name inner_speech*
in VSCode add the inner_speech kernel as a python interpreter
Select inner_speech as kernel in ipynb notebook
add git submodules with *git add submodule git@github.com:OpenNeuroDatasets/ds003626.git* and *git add submodule git submodule add git@github.com:N-Nieto/Inner_Speech_Dataset.git*