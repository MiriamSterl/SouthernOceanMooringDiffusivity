Code accompanying the manuscript "Estimating cross-stream isopycnal eddy diffusivity from mooring observations" submitted to *Ocean Science*.

Figure 1 of the manuscript, showing a map of the study area, is produced in `map_moorings_section.ipynb`.

Figure 2 shows the spline fits of cross-stream distance along the SR1b hydrographic section as a function of dynamic height. These spline fits are produced for different data sets in the files `phi1500_XXX.ipynb` and the results are plotted together in `phi1500_all.ipynb`. Figure A1 is also plotted here.

Figure 3 compares temperature, salinity and neutral density as a function of dynamic height for the SR1b section data and the DIMES mooring data and is produced in `compare_data.ipynb`.

Figures 5, 7 and 8 compare distributions of properties between the SR1b section data and the DIMES mooring data. The data are processed in `process_data_sections.ipynb` aand `process_data_mooring.ipynb`, respectively. Figure 6 also shows the distributions from the SR1b section when the full section is taken into account, computed in `process_data_sections_full.ipynb`. Figure 10 shows the distributions of mixing length from the SR1b section with different (downsampled) vertical resolutions, computed in `process_data_sections_subsample.ipynb`.

Figure 9 shows distributions of eddy diffusivity from the DIMES mooring data and compares these with distributions computed in Chapman & Sallée (2017) and Groeskamp et al. (2020). The data from these two studies are processed in `process_data_ChapmanSallée.ipynb` and `process_data_Groeskamp.ipynb`, respectively. 

Figures 5-10 as well as Figures B1-B5 are all plotted in `plot_data_paper.ipynb`.

`ENVIRONMENT.yml` lists all the Python packages and versions that were used in this project.
