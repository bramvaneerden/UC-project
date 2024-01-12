# UC-project
Github for the urban computing project - fall 2023

Based on the code from Albert et al. https://github.com/adrianalbert/urbanization-patterns

main pipeline is:

    data_per_city_new -> prepare the datasets, crop the .tif files and save them. 
    compute spatial statistics -> use the cropped tif files to compute the statistics
    benchmarking -> use the statistics to calculate the discrepancy


Rewrote (parts) of the following files:

    benchmarking city energy.ipynb  
    compute spatial statistics.ipynb
    create world dataset.ipynb
    cityanalysis.py

Updated and rewrote parts of all files in the pysatml module and added them to the repository, as that was the only way to get it to work.