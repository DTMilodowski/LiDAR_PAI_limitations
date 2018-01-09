# LiDAR_PAI_limitations
**David T. Milodowski**, School of GeoSciences, University of Edinburgh

(January 2018)

This repository hosts a python library to undertake the analyses presented in: "Point density and spatial resolution limit estimation of Leaf Area Index using discrete return LiDAR", submitted to Methods in Ecology and Evolution.

## What is in the repository?
This repository hosts code currently under development.  Not all the functions listed in the modules are used in the analysis, as there are some relict functions from previous iterations, and some functions that are currently being used in other projects.

- LiDAR_io.py : Interfacing with laspy for i/o and spatial filtering of LiDAR returns based on neighbourhood or polygon boundaries; also constructs kdtrees
- LiDAR_tools.py : a bunch of useful tools to interact with LiDAR in python includes spatial filtering of LiDAR returns based on neighbourhood or polygon boundaries.
- auxilliary_functions.py : some generic useful stuff
- LiDAR_MacHorn_LAD_profiles.py : this code calculates the vertical leaf area distribution (_sensu stricto_ plant area distribution) using the method proposed by Stark et al. [Ecology Letters, 2012], which utilises the MacArthur-Horn-based approach to invert the vertical distribution of first returns
- *PAI_limitations_figures.py* : driver function to undertake all analysis in manuscript
- *generate_PAI_raster.py* : driver function to generate the raster datasets (PAI, point density)

## Contact
If you have any questions regarding the code, please don't hesitate to email me at: d.t.milodowski@ed.ac.uk
