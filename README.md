# Project: I Wanna Know

 [Quick link: <img alt="Quick google collab link" width="200px" src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg" /> ](https://colab.research.google.com/github/malikov917/i-wanna-know/blob/main/i-wanna-know.ipynb)


This project is an application designed for inspiration, in-depth reading, and exploration of popular topics. The idea is to start with 100 categories, each containing 100 finely curated topics.

For example, if you choose the psychology category, you'll encounter topics like Gestalt psychology, where a concise, 5-page summary covers the essentials—with potential follow-up prompts added later.

## Implementation:
A specialized model processes millions of text lines from the internet to form clusters through topic modeling. Each cluster is then analyzed to extract and develop detailed topics.

This approach is inspired by the deep research methodology seen in platforms like Perplexity (have you tried it?), offering a unique, customizable format for engaging with content.

## Running the project:

You will need conda (aka miniconda) as your python env manager.
1. Install [miniconda](https://docs.conda.io/projects/conda/en/stable/index.html)
2. Init your env:
    - `conda create -n bertopic_env python=3.9`
    - `conda activate bertopic_env`
    - `conda install jupyter`
3. Run jupyter
    - `jupyter notebook`

known issues:
1. Conda init:
    - [https://community.anaconda.cloud/](https://community.anaconda.cloud/t/unable-to-activate-environment-prompted-to-run-conda-init-before-conda-activate-but-it-doesnt-work/68677)
