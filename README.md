# MultiView ICA

## Install

Clone the repository

`git clone https://github.com/hugorichard/multiviewica.git`

Create virual environment

`virtualenv -p python3 venv`


Activate virtual environment

`source venv/bin/activate`

Move into MultiViewICA directory

``cd multiviewica``

Install MultiViewICA

`pip install -e .`

## Experiments

### Syntetic experiment

Install MultiViewICA and Activate virtual environment (see Install)

Move into examples directory

``cd multiviewica/examples``

Run experiment on synthetic data

`python synthetic_experiment.py`

This will create a figure `synthetic_experiment.png`:

![synthetic_experiment](./examples/synthetic_experiment.png)
