[![DOI](https://zenodo.org/badge/1081778890.svg)](https://doi.org/10.5281/zenodo.24277496)

Code accompanying the manuscript "Estimating cross-stream isopycnal eddy diffusivity from mooring observations" [submitted to *Ocean Science*](https://egusphere.copernicus.org/preprints/2026/egusphere-2026-2566/). 

Figure 1 of the manuscript, showing a map of the study area, is produced in `map_moorings_section.ipynb`.

Figure 2 shows the spline fits of cross-stream distance along the SR1b hydrographic section as a function of dynamic height. These spline fits are produced for different data sets in the files `phi1500_XXX.ipynb` and the results are plotted together in `phi1500_all.ipynb`. Figure A1 is also plotted here.

Figure 3 compares temperature, salinity and neutral density as a function of dynamic height for the SR1b section data and the DIMES mooring data and is produced in `compare_data.ipynb`.

Distributions of temperature and mixing properties of the SR1b section and the DIMES mooring are computed in `process_data_sections.ipynb` and `process_data_mooring.ipynb`, respectively. The distributions from the SR1b section when the full section is taken into account are computed in `process_data_sections_full.ipynb`. Distributions from the SR1b section with different (downsampled) vertical resolutions are computed in `process_data_sections_subsample.ipynb`. The distributions are saved both as a function of neutral density and as a function of depth as vertical coordinate. From these calculations, Figures 5-10, B1, and C1-C5 are produced, all in `plot_data_paper.ipynb`.

Figure 9 shows distributions of eddy diffusivity from the DIMES mooring data and compares these with distributions computed in Chapman & Sallée (2017) and Groeskamp et al. (2020). The data from these two studies are processed in `process_data_ChapmanSallée.ipynb` and `process_data_Groeskamp.ipynb`, respectively.

`ENVIRONMENT.yml` lists all the Python packages and versions that were used in this project.
