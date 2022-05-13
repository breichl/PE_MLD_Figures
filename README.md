# PE MLD Figures

This repository contains all scripts needed to process data and create figures from the manuscript: "A potential energy analysis of ocean surface mixed layers" by Reichl, Adcroft, Griffies, and Hallberg.  This manuscript is accepted for publication in Journal of Geophysical Research - Oceans as of May 2022.  A link to the paper will be provided when it is available.

# Instructions for using this repository

First please find the instructions for installing the necessary Python environments at github.com/breichl/oceanmixedlayers.  Other packages may be needed, such as cmocean, if you wish to use the same colormaps.  
If issues are encountered using the notebooks, check that all paths are appropriately connected to directories and datasets that exist and that your machine has access to.  

This repository includes the notebook to generate all processed Mixed Layer Depth data from the Roemmich and Gilson gridded Argo data product (using the provided notebook within the "Data" folder from the main directory).  The gridded Argo product can be found here: https://sio-argo.ucsd.edu/RG_Climatology.html  and these notebooks should be compatible with any updates to that data product provided they are merged into a single netCDF file (e.g., with nco).  

Finally, specific figures can be recreated from within the "Figures" folder from the main directory.  The paths to save files should be updated and/or created as necessary (or the commands to save figures can be commented out).

