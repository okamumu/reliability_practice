# Reliability Practice

This is an exercise for model-based reliability evaluation with stochastic Petri nets on Jupyter notebook.

## Installation

We recommend to use Docker as follows.

1. Run Jupyter notebook server (Jupyter Lab)
```
docker run -it --name notebook --rm -p 8888:8888 -v $(pwd):/home/jovyan/work -e JUPYTER_ENABLE_LAB=yes jupyter/datascience-notebook:julia-1.5.2
```
2. Access Jupyter server using access token with your browser.

3. Open and execute setup.ipynb to install Julia packages and gospn

