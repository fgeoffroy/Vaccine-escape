# Code for the paper "Vaccination strategies when vaccines are scarce: Conflicts between reducing burden and avoiding the evolution of escape mutations"

```bash
$ conda update conda
$ conda env create -f environment.yml
$ conda activate VaccineEscape
$ ipython kernel install --user --name=VaccineEscapeKernel
$ jupyter notebook vaccine_escape.ipynb
```

Make sure that the right kernel is used in the jupyter notebook: `Kernel>Change kernel>VaccineEscapeKernel`

The source code was tested on Ubuntu 18.04.
