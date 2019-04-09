# halletal2019
Public repository for Hall et al. (2019).

This repository contains a tidied version of code used for the work presented in Hall et al. (2019). I've stripped away unused or broken scripts and endless, endless tests. If you're interested in looking at those anyway, the full repository of everything I've ever done on this project can be found here: https://www.github.com/ojhall94/GAIA

**Note**: I have reshuffled some of the directories while tidying this repository, the scripts may not run without fixing paths.

## abstract
Asteroseismology provides fundamental stellar parameters independent of distance, but is subject to systematics that are still under calibration. *Gaia* DR2 has provided parallaxes for more than a billion stars, but these are offset by a parallax zero-point. Red Clump (RC) stars have a narrow spread in luminosity, thus functioning as standard candles that can be used to calibrate seismology and *Gaia* parallaxes.

This work measures how the magnitude and spread of the RC in the *Kepler* field in the 2MASS *K* and *Gaia* *G* bands are affected by changes to temperature and seismic scaling relations for seismic data, and by changes to the parallax zero-point for *Gaia* data. We use a sample of 5576 RC stars classified through asteroseismology.

We apply hierarchical Bayesian latent variable models, finding the population level properties of the RC with seismology, and using those results as priors on the *Gaia* data to find the parallax zero-point. We then find the position of the RC using published values for the zero-point.

We find the inferred absolute magnitude of the RC from seismology to be negatively correlated with a change to temperature. This shift is also degenerate with the application of scaling relations corrections. Using seismology we find a temperature insensitive spread of the RC of ~0.03 mag in *K* and, as predicted, a larger and slightly temperature-dependent spread of ~0.13 mag in *G*. The intrinsic dispersion of 0.03 mag in the *K* band provides a distance precision of ~1% for RC stars. Using parallax and marginalizing over the zero-point, and accounting for spatial correlations in parallax, we find a mean zero-point of -41 +/- 10 micro-arcseconds, in the sense that *Gaia* parallaxes are too small. This offset yields RC absolute magnitudes of -1.634 +/- 0.018 in *K* and 0.546 +/- 0.016 in *G*. Obtaining these same values through seismology would require a global temperature shift of ~ -70 *K*, which is compatible with known systematics in spectroscopy.

## citation

If you wish to cite the associated paper in your work, please use the following BibTeX:


## data

Due to the size of the files, we cannot host the full input & output data here. The output however should be fully reproducible if the random seeds in the code remain unchanged. If you are interested in obtaining these data (for example for reproducing the work, or using our posterior samples as priors in your own work), please contact:

`ojh251 [at] student.bham.ac.uk`

## authors

Oliver J. Hall (@ojhall94) [*corresponding author*]
Guy R. Davies (@grd349)
Yvonne Elsworth
Andrea Miglio
Timothy R. Bedding (@timbedding)
Anthony G. A. Brown (@agabrown)
Saniya Khan (@niyachan)
Keith Hawkins (@keithhawkins)
Rafael A. Garcia
William J. Chaplin
Thomas S. H. North (@tn143)
