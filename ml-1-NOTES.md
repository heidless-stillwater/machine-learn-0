
# [Build Your First Machine Learning Project [Full Beginner Walkthrough]](https://www.youtube.com/watch?v=Hr06nSA-qww&list=PLwHsEiLdJVW0WX5SLoPTq2HSwKCKeo0KW&index=2&t=10s)

## [git: project_walkthroughs: beginner_ml](https://github.com/dataquestio/project-walkthroughs/tree/master/beginner_ml)


### conda
- ### [conda forge](https://conda-forge.org/download/)
```

# install
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
zsh ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm ~/miniconda3/miniconda.sh

# initialize on all available shelsls
conda init --all

# activate
source ~/miniconda3/bin/activate dataSci-0

```

### [conda - CHEATSHEET](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)]
```

conda config --add channels conda-forge

conda create --name dataSci-0
source activate dataSci-0

conda create --name dataSci-2 python=3.13
source ~/miniconda3/bin/activate dataSci-2

conda env list

conda install scipy --channel conda-forge --channel bioconda

```

### jupyter notebooks
```
source ~/miniconda3/bin/activate dataSci-2

conda install jupyterlab --channel conda-forge

jupyter lab

```

### [gCloud Vertex AI](https://cloud.google.com/vertex-ai/docs/tutorials/jupyter-notebooks)


### install packages
```
conda install pandas --channel conda-forge
conda install numpy --channel conda-forge
conda install seaborn --channel conda-forge
conda install scikit-learn --channel conda-forge



conda install catboost --channel conda-forge

```

### error metric

$$
mean\ absolute\ error = \sum_{i=1}^D|x_i - y_i |
$$






########################

$$
SSB = \sum_{\substack{g = 1}} ng(M_g - M_G)^{2}
$$


$$
R^2 = 1 - 
				\frac
					{Sum\ if\ Squared\ Residuals}
					{Total\ Sum\ of\ Squares}
$$

$$
P(X=k) = 
	\frac 
		{\lambda^k * e^{^-\lambda}}
		{k!}
$$

$$
SE(\^{p}) = 
\frac
	{\sqrt{\^p(1-\^p)}}
	{n}
$$
$$
\^p	= population\  proportion
$$
$$
n = sample\ size
$$
