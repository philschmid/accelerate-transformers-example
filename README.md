# Examples and Experiments on how to use [Accelerate](https://huggingface.co/docs/accelerate/index) to train Transformers

## Getting started

1. setup conda env

```bash
conda create --channel=conda-forge --name ac \
  python=3.9 \
  nvidia::cudatoolkit=11.3 \
  pytorch::pytorch=1.11.0=py3.9_cuda11.3_cudnn8.2.0_0 \
  mpi4py=3.0 
```
2. install pip packages
```bash
pip install transformers datasets accelerate evaluate
```

## Checkout examples

* [migrate vanilla pytorch to accelerate](./examples/migrate.ipynb)