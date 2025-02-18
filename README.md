# Toyformers

This repository contains a bunch of "toy" set modelling tasks with synthetic data.
We train transformers on this data and see how well they do.

In general, these tasks involve training sequences of uniform random length up to 100, and then evaluating on sequences up to length 200.

## Getting Started

```sh
# create and activate whatever environment you want
pip install -r requirements.txt
```

Each experiment exists entirely inside a self-contained notebook, with outputs already saved.
To reproduce the experiments, you can re-run the notebook.
