# Practical Session using HYPSO-1 for TTK4265
This repo was created to provide the students of TTK4265 with 
a programming envirnoment where they can explore data collected by HYPSO-1.
The notebook `index.ipynb` provides an interactive python notebook where 
the data can be investigated.

This is set up as a Binder-compatible repo with an `environment.yml` file.
Access this Binder by clicking the blue badge above or at the following URL:<br />

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NTNU-SmallSat-Lab/TTK4265-ORS-Practical/master?labpath=index.ipynb)

In this specific notebook only one single file from HYPSO-1 is made available.
The scripts you develop should be able to extend to other data sets from HYPSO-1.
There are several tasks that requires you to be curios and daring to be able 
to answer.

##

The notebook `index.ipynb` is intended to provide you as a student of TK4265 an opurtunity to play around with Hyperpsectral data from the HYPSO-1 Satellite.
You are supposed to look at one specific file form the HYPSO-1 satellite with the identifying name: <br />
**vancouvergrieg_2022_07_29T18_36_58-hsi0**
You need to download the `.bip` and upload it to your binder to be able to follow this assignment.

### Conda environment with environment.yml
To install a virtual envirnoment simply type the following in a terminal where `conda` is installed.

```
conda env create -f environment.yml
```
## Notes
The `environment.yml` file lists all Python libraries on which these project notebook(s)
depend, specified as though they were created using the following `conda` commands:

```
conda activate example-environment
conda env export --from-history -f environment.yml
```

Note that the only libraries available to you will be the ones specified in
the `environment.yml`, so be sure to include everything that you need! 

Also note that if you skip the `--from-history`, conda may include OS-specific
packages in `environment.yml`, which you would have to manually prune from
`environment.yml`.  For example, confirmed macOS-specific packages that should
be removed are:

* libcxxabi=4.0.1
* appnope=0.1.0
* libgfortran=3.0.1
* libcxx=4.0.1
