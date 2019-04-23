# halletal2019
[![arXiv](http://img.shields.io/badge/arXiv-1904.07919-blue.svg?style=flat)](https://arxiv.org/abs/1904.07919)

This repository hosts a tidied version of the code associated with Hall et al. (2019). I've stripped away unused or broken scripts and endless, endless tests. If you're interested in looking at those anyway, the full repository of everything we did on this project can be found here: https://www.github.com/ojhall94/GAIA

**Note**: I have reshuffled some of the directories while tidying this repository, the scripts may not run without fixing paths.

## abstract
Asteroseismology provides fundamental stellar parameters independent of distance, but subject to systematics under calibration. Gaia DR2 has provided parallaxes for a billion stars, which are offset by a parallax zero-point. Red Clump (RC) stars have a narrow spread in luminosity, thus functioning as standard candles to calibrate these systematics. This work measures how the magnitude and spread of the RC in the Kepler field are affected by changes to temperature and scaling relations for seismology, and changes to the parallax zero-point for Gaia. We use a sample of 5576 RC stars classified through asteroseismology. We apply hierarchical Bayesian latent variable models, finding the population level properties of the RC with seismology, and use those as priors on Gaia parallaxes to find the parallax zero-point offset. We then find the position of the RC using published values for the zero-point. We find a seismic temperature insensitive spread of the RC of ~0.03 mag in the 2MASS K band and a larger and slightly temperature-dependent spread of ~0.13 mag in the Gaia G band. This intrinsic dispersion in the K band provides a distance precision of ~1% for RC stars. Using Gaia data alone, we find a mean zero-point of -41 ± 10 μas. This offset yields RC absolute magnitudes of -1.634 ± 0.018 in K and 0.546 ± 0.016 in G. Obtaining these same values through seismology would require a global temperature shift of ~-70 K, which is compatible with known systematics in spectroscopy.

## data

Due to the size of the files, we cannot host the full input & output data here. The output however should be fully reproducible if the random seeds in the code remain unchanged. If you are interested in obtaining these data (for example for reproducing the work, or using our posterior samples as priors in your own work), please contact:

`ojh251 [at] student.bham.ac.uk`

## citation

If using any of our code or results, please cite our paper using the following BibTex entry:

```
@ARTICLE{2019MNRAS.tmp.1036H,
       author = {{Hall}, Oliver J. and {Davies}, Guy R. and {Elsworth}, Yvonne P. and
         {Miglio}, Andrea and {Bedding}, Timothy R. and {Brown}, Anthony G.~A. and
         {Khan}, Saniya and {Hawkins}, Keith and {Garc{\'\i}a}, Rafael A. and
         {Chaplin}, William J. and {North}, Thomas S.~H.},
        title = "{Testing asteroseismology with Gaia DR2: Hierarchical models of the Red Clump}",
      journal = {\mnras},
     keywords = {parallax, asteroseismology, stars: fundamental parameters, stars: statistics, Astrophysics - Solar and Stellar Astrophysics},
         year = "2019",
        month = "Apr",
        pages = {1036},
          doi = {10.1093/mnras/stz1092},
archivePrefix = {arXiv},
       eprint = {1904.07919},
 primaryClass = {astro-ph.SR},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2019MNRAS.tmp.1036H},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

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
