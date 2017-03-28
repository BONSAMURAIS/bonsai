# Pieces of Code for BONSAI-beta version

The functional and technical specifications of BONSAI are described in the [wiki](https://github.com/BONSAMURAIS/bonsai/wiki).
This repository contains pieces of code which execute some of the functions needed for BONSAI.

The [Calculation of LCIA results with Stepwise 1.6](https://github.com/BONSAMURAIS/bonsai/blob/master/Calculate%20product%20footprints%20with%20Stepwise.ipynb) notebook presents the code to calculate the Product Footprints with Stepwise 1.6. The functional specifications of this task are described in the [Global Impact Assessment](https://github.com/BONSAMURAIS/bonsai/wiki/Ensure%20Data%20Quality#global-impact-assessment-ia) working group.

The [Leontief inverse tutorial](https://github.com/BONSAMURAIS/bonsai/blob/master/Calculate%20terminated%20results%20exiobase%20v.3.3.10%20excluding%20iLUC.ipynb) presents the code required to perform the matrix inversion, this function is detailed in the [Product System algorithms](https://github.com/BONSAMURAIS/bonsai/wiki/Make-Data-Usable#product-system-algorithms) working group.

The [least square method tutorial](https://github.com/BONSAMURAIS/bonsai/blob/master/Overdetermined%20system%20resolution%20-%20sugar%20in%20soft%20drinks%20and%20spirits.ipynb) presents a case study using a data filling algorithm, which could be used by the [Input Output Framework](https://github.com/BONSAMURAIS/bonsai/wiki/Harvest%20Data#sut-gap-filling--correction-routines) working group.  

These tutorials are currently written to be executed with the Exiobase IO-database as background data. But Exiobase is not open-source and cannot be uploaded from this site. We intend to modify the tutorials so they can be executed with FORWAST.

This code works with Python 3.4, it requires some additional packages such as Numpy and Pandas. The pices of code are presented in Jupyter Notebooks. Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

BONSAMURAIS/bonsai/ is licensed under an MIT License.
