# stochastic-volcanoes
Stochastic volcanic eruptions in future climate projections

## Reproduction steps

### Set up conda repository

This assumes that you are using `anaconda` and `python`. Currently, I recommend `python` versions 3.8, 3.9, 3.10 and 3.11. These are the versions supported by `fair` and `fair-calibrate`. Others may work, but these ones are tested.

1. Create your environment:

```
$ conda env create -f environment.yml
```

2. Activate the environment:

```
$ conda activate stochastic-volcanoes
```

3. Make clean notebooks for version control, which will remove all output and data upon committing, run

```
$ nbstripout --install
```
