# enviroments
Enviroments


## Steps

1. build model inside envs with pendulum_dae_builder.ipynb 
2. pip install -e .
3. modify pendulum_dae.py as explained in pendulum_dae_builder.ipynb 


winpty docker run -it --gpus=all -e GRANT_SUDO=yes --user root -p 8889:8888 jupyter/tensorflow-notebook


