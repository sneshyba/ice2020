This is a repository for ice surface data as determined by Scanning electron microscopy & Gauss-Newton Bayesian Framework (GNBF)

Reference:
Butterfield et al, Quantitative three-dimensional ice roughness from scanning electron microscopy, J. Geophys. Res.: Atmospheres, 122, 3023-3041 (2017).


How to install dependencies:

From https://pypi.python.org/pypi/numpy-stl:
pip install numpy-stl

As documented in the folder “nml code”:
pip install f90nml

This is work done by Kayden Lynch and Steven Neshyba 2020.

Data flow

GNBF_makextlvecs.ipynb
    Loads an immage of a smooth ice crystal and creates a namelist file Xtlvecs.nml