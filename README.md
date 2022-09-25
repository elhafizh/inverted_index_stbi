## Installation Guide

1. Download the dataset from [this link](https://drive.google.com/file/d/186YJ9a8hIr1N5NmKm5ZxjuKe4NM7E1fY/view?usp=sharing).  Create a new folder called `dataset`. Put the `News.csv` file inside the `dataset` folder.
2. Open terminal. Create a new environment called `inv_ind_stbi`
```
$ conda create --name inv_ind_stbi python=3.9
```
3. Activate the environment:
```
$ conda activate inv_ind_stbi
```
4. Install the packages from `environment.yml` into an existing environment
```
$ conda env update --file environment.yml
```
5. Start JupyterLab using:
```
$ jupyter lab
```