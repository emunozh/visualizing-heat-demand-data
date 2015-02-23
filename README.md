# Visualizing Heat Demand Data
Visualizing heat demand data in the ipython notebook

The aim of this repository is to show preliminary results from a simulation.
This simulation aims to estimate heat demand at low aggregation level
(buildings) for large urban agglomerations (in this case Hamburg). Although
the simulation runs at a building level I'm not allow to publish these results.
This results show the hourly heat demand for the city of Hamburg at a
statistical unit level.

This repository contains three ipython notebooks: 

1. [time series](http://nbviewer.ipython.org/github/emunozh/visualizing-heat-demand-data/blob/master/1%20time%20series.ipynb)
A notebook that reads the simulation result stored on a set of csv files and
created a HDF file. This file is used on the other two notebook to visualize
and map the result. In this notebook I show to to properly index the files as
time series.

2. [mapping the result](http://nbviewer.ipython.org/github/emunozh/visualizing-heat-demand-data/blob/master/2%20mapping%20the%20result.ipynb)
This notebook constructs two widgets for the visualization of heat demand in
space. The aim of this widgets is to select a particular time and time to
render the simulated heat demand in space. 

3. [viewing the result](http://nbviewer.ipython.org/github/emunozh/visualizing-heat-demand-data/blob/master/3%20viewing%20the%20result.ipynb)
The last notebook shows some examples of generated animations. 
