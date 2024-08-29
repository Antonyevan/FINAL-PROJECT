Type Ia Supernovae Classification and NIR Spectral Analysis
Introduction
This project is focused on the classification of Type Ia Supernovae (SNe Ia) using various clustering algorithms—DBSCAN, K-Means, and Gaussian Mixture Models (GMM). The classification is based on key features such as the velocity of the Calcium II (Ca II) 8662 Å spectral line and the magnitude in the I band. Additionally, the project involves the analysis and visualization of Near-Infrared (NIR) spectra of SNe Ia, as published in Lu et al. 2023.

Publication Reference: Lu et al. 2023
Data Source: NIR spectra of 98 individual SNe Ia from the Carnegie Supernova Project-II (CSP-II).

Due to GitHub's file size limitation of 25 MB per file, the final code and data have been organized and uploaded in multiple parts.

Repository Structure
Jupyter Notebooks:

final_sne_ia_3_models.ipynb
Contains the core calculations and application of clustering algorithms to classify SNe Ia based on the Ca II 8662 Å spectral line velocity and I band magnitude.
final_sne_ia_ca_ii_8498.ipynb
Visualizes the analysis related to the Ca II 8498 Å spectral line.
final_sne_ia_ca_ii_8662_.ipynb
Visualizes the analysis and clustering results for the Ca II 8662 Å spectral line.
Data Files:

Data/Lu2023_TableA1_extension.csv
A comprehensive list of SNe Ia and their NIR spectra, including details from Lu et al. 2023, with additional columns for extended analysis.
Data/observed_spectra/spec_fits/
Contains the FITS files for the observed NIR spectra.
Installation
To set up this project locally:

Clone the repository:
git clone https://github.com/Antonyevan/FINAL-PROJECT.git

Navigate to the project directory:
cd FINAL-PROJECT

Usage
1. Running the Models and Clustering Algorithms
Open the Jupyter notebook final_sne_ia_3_models.ipynb to execute the main calculations and clustering analysis:

jupyter notebook final_sne_ia_3_models.ipynb

2. Visualizing Spectral Line Data
For the Ca II 8498 Å spectral line, open and run:

jupyter notebook final_sne_ia_ca_ii_8498.ipynb

For the Ca II 8662 Å spectral line, open and run:

jupyter notebook final_sne_ia_ca_ii_8662_.ipynb

Features
Clustering Algorithms: Apply DBSCAN, K-Means, and Gaussian Mixture Models (GMM) to classify SNe Ia.
NIR Spectral Analysis: Process and analyze spectra from the CSP-II dataset.
Data Visualization: Generate plots for the spectral lines and clustering results.

Dependencies
pandas
numpy
matplotlib
seaborn
astropy
scipy
sklearn

Data Access
NIR Spectra List: Data/Lu2023_TableA1_extension.csv
Observed Spectra: Data/observed_spectra/spec_fits

Contributors
Antony Evan Alosius

