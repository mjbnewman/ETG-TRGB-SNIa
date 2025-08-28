# ETG-TRGB-SNIa
This is the publicly available repository that contains the code for our SN Ia cosmology analysis reported in the manuscript https://arxiv.org/abs/2508.20023 (submitted to ApJ).

The analysis code is in the notebook `unblinded_analysis.ipynb`

Input files are CSV for the calibrators (`trgb_calibrators_cov.csv` and `trgb_calibrators_cov_with94D.csv`) and the Hubble flow from ZTF SN Ia DR2 ([Rigault et al. 2025, A&A, 694, A1](https://ui.adsabs.harvard.edu/abs/2025A%26A...694A...1R/abstract)), with `ztf_data_hd.csv` corresponding to the volume-limited sample (z_helio < 0.06) and a column added for the Hubble diagram redshift after flow correction ([Carr et al. 2022, PASP, 39, e046](https://ui.adsabs.harvard.edu/abs/2022PASA...39...46C/abstract)) using the code at [https://github.com/KSaid-1/pvhub](https://github.com/KSaid-1/pvhub).

Output plots and files are in the `output/` directory. They start with `H0-` and then the name of the sample used. Our recommended samples are `with94D` and `fiducial`.