# inner-speech-detection

What I did to make it run:

* Download all 3 N-Nieto git repositorys.

* Install miniconda.

* Create conda environment for Inner_Speech_Dataset with *conda env create -f environment.yml*

* Register the conda environment as jupyter kernel with *python -m ipykernel install --user --name inner_speech*

* In VSCode add the inner_speech kernel as a python interpreter

* Select inner_speech as kernel in ipynb notebook

* Add git submodules with *git add submodule git@github.com:OpenNeuroDatasets/ds003626.git* and *git add submodule git submodule add git@github.
com:N-Nieto/Inner_Speech_Dataset.git*
