# State space tutorial

Author: Christian Donner, SDSC

This contains some notebooks, that explain the basics of state-space modelling, Kalman Filter, and linear quadratic 
regulator for dampend spring-mass.

## Getting started

This repo comes with an a Dockerfile, that with VSCode should already create the necessary environment. If you want to 
use conda please do within the repo

```bash
conda create --name state-space-tutorial python=3.11
conda activate state-space-tutorial
pip install -r requirements.txt
```

Then you can start the notebook:

```bash
jupyter notebook notebooks/00_tutorial_wo_solutions.ipynb
```