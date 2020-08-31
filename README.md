CTSM_PY
=======

A place to put sample workflows and tools that use ctsm model output

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4009510.svg)](https://doi.org/10.5281/zenodo.4009510)

## Installing

First clone this repository:

```
git clone https://github.com/NCAR/ctsm_py.git
```

Then intall the utilities:

```bash
cd ctsm_py
conda activate $ENVIRONMENT_NAME
pip install -e .
```

Import ctsm_py in Python

```python
In [1]: from ctsm_py.utils import weighted_annual_mean
```
