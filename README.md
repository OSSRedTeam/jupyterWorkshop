# OSS Workshop Docker Image

[![docker pulls](https://img.shields.io/docker/pulls/jupyter/base-notebook.svg)](https://hub.docker.com/r/jupyter/base-notebook/)
[![docker stars](https://img.shields.io/docker/stars/jupyter/base-notebook.svg)](https://hub.docker.com/r/jupyter/base-notebook/)
[![image size](https://img.shields.io/docker/image-size/jupyter/base-notebook/latest)](https://hub.docker.com/r/jupyter/base-notebook/ "jupyter/base-notebook image size")

GitHub Actions in the <https://github.com/jupyter/docker-stacks> project builds and pushes this image to Docker Hub.

Please visit the project documentation site for help to use and contribute to this image and others.

- [Jupyter Docker Stacks on ReadTheDocs](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html)
- [Selecting an Image :: Core Stacks :: jupyter/base-notebook](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-base-notebook)

First login to osscsuf docker account <br>
To Build: <br>
`docker build . -t osscsuf/workshop-notebook:latest`
To Push: <br>
`docker push osscsuf/workshop-notebook:latest`
