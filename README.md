# Jupyter Notebook with Tenserflow and Opencv

This docker image contains [opencv version 4.0.0](https://opencv.org/opencv-4-0-0-alpha.html) and 
as base [jupyter/tensorflow-notebook:e8613d84128b](https://github.com/jupyter/docker-stacks/tree/e8613d84128b870b4ab5dbc6e8006d6186377291).

## Usage

Start as `docker run --rm -it -v "/$(PWD)":/home/jovyan/work -p 8888:8888` which mounts your current folder
and makes the notebook accessible over localhost:8888.
