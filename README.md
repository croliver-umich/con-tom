[![DOI](https://zenodo.org/badge/263715491.svg)](https://zenodo.org/badge/latestdoi/263715491)
# con-tom
Confocal tomography (con-tom) toolkit is intended to be a robust open source tool for analyzing 3D Confocal images from organ on a chip devices. It was originally designed to aid in measuring the tumor micro-environment in in vivo devices.

This notebook has only been tested with the following python packages:

python 3.8.1

jupyter notebook 5.3.4

jupyter lab 1.2.4

vtk 8.2.0

os - built into python

sys - built into python

numpy 1.17.3

pickle - built into python

math - built into python

ipywidgets 7.5.1

Ipython 7.11.1 - built into jupyter

pandas 0.25.3

matplotlib 3.1.2 - mpl_toolkits part of above

scipy 1.3.2

functools - built into python

gc - built into python

seaborn 0.9.0

nd2reader 3.0.2

tifffile 2019.7.26.2

Usage: Save ND2 file in a folder below this notebook called ../Experiment_###/Confocal/###.nd2. If this was your tenth experiment then the path would be ../Experiment_100/Confocal/100.nd2

Then use the notebook as annotated to analyze the data.
