# PyTorch image recognition



Colab + PyTorch + CUDA 


## Requirements

colabollatory environment is required
[available on the Docker website](https://docs.docker.com/engine/installation/).


## Prebuilt images

Prebuilt images are available on Docker Hub under the name
[anibali/pytorch](https://hub.docker.com/r/anibali/pytorch/).

For example, you can pull an image with PyTorch 1.13.0 and CUDA 11.8 using:

```bash
$ docker pull anibali/pytorch:1.13.0-cuda11.8
```


## Usage

### Running PyTorch scripts

It is possible to run PyTorch programs inside a container using the
`python3` command. For example, if you are within a directory containing
some PyTorch project with entrypoint `main.py`, you could run it with
the following command:

```sh
print(hello)
```


