# tensorflow-drupal
Repository for Drupal ConGov monthly meeting July 16th, 2021

## Docker Container
For dev purposes I am using a Docker container that uses tensorflow-gpu to utilize my GPU using JupyterLab
```
docker run --gpus all -d -it -p 8848:8888 -v $(pwd)/data:/home/jovyan/work -e GRANT_SUDO=yes -e JUPYTER_ENABLE_LAB=yes --user root cschranz/gpu-jupyter:v1.4_cuda-11.0_ubuntu-20.04_python-only
```
## TensorFlow.org Recommender Tutorial
Example model to run using Jupyter Notebook and then exporting model for use with TensorFlow.js:
(Recommending movies: retrieval)[https://www.tensorflow.org/recommenders/examples/basic_retrieval]

