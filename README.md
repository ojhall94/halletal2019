# halletal2019
Public repository for Hall et al. (2019).

This repository contains a tidied version of code used for the work presented in Hall et al. (2019). I've stripped away unused or broken scripts and endless, endless tests. If you're interested in looking at those anyway, the full repository of everything I've ever done on this project can be found here: https://www.github.com/ojhall94/GAIA

## abstract
Asteroseismology provides fundamental stellar parameters independent of distance, but is subject to systematics that are still under calibration. \gaia DR2 has provided parallaxes for more than a billion stars, but these are offset by a parallax zero-point ($\varpi_{\rm zp}$). Red Clump (RC) stars have a narrow spread in luminosity, thus functioning as standard candles that can be used to calibrate seismology and *Gaia* parallaxes.

This work measures how the magnitude and spread of the RC in the *Kepler* field in the 2MASS *K* and *Gaia* *G* bands are affected by changes to temperature and seismic scaling relations for seismic data, and by changes to the parallax zero-point for *Gaia* data. We use a sample of 5576 RC stars classified through asteroseismology.

We apply hierarchical Bayesian latent variable models, finding the population level properties of the RC with seismology, and using those results as priors on the *Gaia* data to find $\varpi_{\rm zp}$. We then find the position of the RC using published values for the zero-point.

We find the inferred absolute magnitude of the RC from seismology to be negatively correlated with a change to $T_{\rm eff}$. This shift is also degenerate with the application of scaling relations corrections. Using seismology we find a temperature insensitive spread of the RC of $\sim0.03\, \rm mag$ in *K* and, as predicted, a larger and slightly temperature-dependent spread of $\sim0.13\, \rm mag$ in *G*. The intrinsic dispersion of $0.03\, \rm mag$ in the *K* band provides a distance precision of $\sim 1\%$ for RC stars. Using parallax and marginalizing over $\varpi_{\rm zp}$, and accounting for spatial correlations in parallax, we find a mean zero-point of $-41 \pm 10\, \mu \rm as$, in the sense that \gaia parallaxes are too small. This offset yields RC absolute magnitudes of $-1.634 \pm 0.018$ in *K* and $0.546 \pm 0.016$ in *G*. Obtaining these same values through seismology would require a global temperature shift of $\sim-70\ K$, which is compatible with known systematics in spectroscopy.

## citation

If you wish to cite the associated paper in your work, please use the following BibTeX:


## data

Due to the size of the files, we cannot host the full input & output data here. The output however should be fully reproducible if the random seeds in the code remain unchanged. If you are interested in obtaining these data (for example for reproducing the work, or using our posterior samples as priors in your own work), please contact:

`ojh251 [at] student.bham.ac.uk`
