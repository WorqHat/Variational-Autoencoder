# Variational Autoencoder in TensorFlow

## Package Dependencies

This repository trains the Variational Autoencoder in Tensorflow framework on Fashion-MNIST and Cartoon dataset. The cartoon dataset can be download from [here](https://google.github.io/cartoonset/). 

The code is tested with:

- `Cuda-11.1`
- `Cudnn-8.0`

The Tensorflow notebook requires [numpy](https://numpy.org/), [tf-nightly-gpu](https://pypi.org/project/tf-nightly-gpu/), [opencv](https://pypi.org/project/opencv-python/), [sklearn](https://pypi.org/project/scikit-learn/). 
To get the versions of these packages you need for the program, use pip: (Make sure pip is upgraded: ` python3 -m pip install -U pip`)

```python
pip3 install -r requirements.txt 
```

## Add Virtualenv as Python Kernel in Jupyterlab

- Activate the virtualenv

```python
$ source your-venv/bin/activate
```

- Add the virtualenv as a jupyter kernel

```python
(your-venv)$ ipython kernel install --name "local-venv" --user
```

Replace `local-venv` with your virtualenv name.
