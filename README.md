## Installation Guide

1. Download the dataset from [this link](https://drive.google.com/file/d/186YJ9a8hIr1N5NmKm5ZxjuKe4NM7E1fY/view?usp=sharing).  Create a new folder called `dataset`. Put the `News.csv` file inside the `dataset` folder.
2. Make sure you have [anaconda](https://www.anaconda.com/) installed to be able to access `conda` commands.
3. Open terminal. Create a new environment called `inv_ind_stbi`
```
$ conda create --name inv_ind_stbi python=3.9
```
4. Activate the environment:
```
$ conda activate inv_ind_stbi
```
5. Install the packages from `environment.yaml` into an existing environment
```
$ conda env update --file environment.yml
```
6. Start JupyterLab using:
```
$ jupyter lab
```
7. Download [nlp_tokens.pkl](https://drive.google.com/file/d/1Mqyp7wrWHd69KLZ8vKPrDgxWBcN7Q-kO/view?usp=sharing) for initial processing tokens, then put it in the `datasets` folder.
