# llm-from-scratch
Hands-on practice on NLP and LLM applications
- <a href="https://nbviewer.jupyter.org/github/xiangshiyin/llm-from-scratch/blob/main/index.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a> - to view the notebooks on `nbviewer`

## Envrionment Setup
### Pre-requisites
Start by installing [Anaconda](https://www.anaconda.com/products/distribution) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads).

Next, clone the project repo to your local machine:
```bash
git clone https://github.com/xiangshiyin/llm-from-scratch.git
cd llm-from-scratch
```

### Install Dependencies
Run the following commands to setup the environment:
```bash
conda env create -f environment.yml
conda activate torch
```

If any changes are made to the environment, update the `environment.yml` file by running:
```bash
conda env export > environment.yml
```

### IDE Setup
For VSCode, install the following extensions:
- Python
- Jupyter (this will allow you to run Jupyter notebooks within VSCode)

## Miscellaneous
- PyTorch tutorial [[youtube](https://www.youtube.com/playlist?list=PL_lsbAsL_o2CTlGHgMxNrKhzP97BaG9ZN)] [[official](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)]

