# Pieces of Code for BONSAI-beta version

The functional and technical specifications of BONSAI are described in the [wiki](https://github.com/BONSAMURAIS/bonsai/wiki).
This repository contains pieces of code to execute some of the functions needed for BONSAI.

The [Calculation of LCIA results with Stepwise 1.6](https://github.com/BONSAMURAIS/bonsai/blob/master/Calculate%20product%20footprints%20with%20Stepwise.ipynb) notebook presents the code to calculate the Product Footprints with Stepwise 1.6. The functional specifications of this task are described in the [Global Impact Assessment](https://github.com/BONSAMURAIS/bonsai/wiki/Ensure%20Data%20Quality#global-impact-assessment-ia) working group.

The [Leontief inverse tutorial 1](https://github.com/BONSAMURAIS/bonsai/blob/master/Leontiev%20inverse%20tutorial%20-%20investments%20ARE%20integrated.ipynb) and [2](https://github.com/BONSAMURAIS/bonsai/blob/master/Leontive%20inverse%20tutorial%20-%20investments%20are%20NOT%20integrated%20-%20iLUC%2C%20electricty%20markets%20and%20social%20extensions%20ARE%20included.ipynb) present the code required to perform the matrix inversion, this function is detailed in the [Product System algorithms](https://github.com/BONSAMURAIS/bonsai/wiki/Make-Data-Usable#product-system-algorithms) working group. The code for the tutorial 1 is valid for Exiobase v3.3.11b1 where investments ARE integrated in the core matrix. The code in the tutorial 2 is valid for Exiobase v3.3.11b2 where investments are NOT integrated in the core matrix. Also, indirect Land Use Change activities, electricity markets and social extensions are included.

The [least square method tutorial](https://github.com/BONSAMURAIS/bonsai/blob/master/Overdetermined%20system%20resolution%20-%20sugar%20in%20soft%20drinks%20and%20spirits.ipynb) presents a case study using a data filling algorithm, which could be used by the [Input Output Framework](https://github.com/BONSAMURAIS/bonsai/wiki/Harvest%20Data#sut-gap-filling--correction-routines) working group.  

These tutorials are currently written to be executed with the Exiobase IO-database as background data. But Exiobase is not open-source and cannot be uploaded from this site. We intend to modify the tutorials so they can be executed with FORWAST.

The pieces of code are presented in Jupyter Notebooks. Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. This code works with Python 3.4, although it requires some additional packages such as Numpy and Pandas.

BONSAMURAIS/bonsai/ is licensed under an MIT License.
