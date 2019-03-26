# Preliminary Code for BONSAI-beta version

This subfolder contains preliminary code meant to execute some of the functions requried for a Bonsai-beta version.

The functional and technical specifications of BONSAI are currently described in an evoloving documentatioin in the [wiki](https://github.com/BONSAMURAIS/bonsai/wiki).

Substantial development is now taking place in dedicated working [groups](https://github.com/BONSAMURAIS) in preparation of the [Hackathon](https://github.com/BONSAMURAIS/hackathon-2019)

## Description of the code in this repostitory

* The [Calculation of LCIA results with Stepwise 1.6](https://github.com/BONSAMURAIS/bonsai/blob/master/Calculate%20product%20footprints%20with%20Stepwise.ipynb) notebook presents the code to calculate the Product Footprints with Stepwise 1.6. The functional specifications of this task are described in the [Global Impact Assessment](https://github.com/BONSAMURAIS/bonsai/wiki/Ensure%20Data%20Quality#global-impact-assessment-ia) working group.

* The [Leontief inverse tutorial 1](https://github.com/BONSAMURAIS/bonsai/blob/master/Leontive%20inverse%20tutorial%20-%20investments%20are%20NOT%20integrated.ipynb) and [tutorial 2](https://github.com/BONSAMURAIS/bonsai/blob/master/Leontive%20inverse%20tutorial%20-%20investments%20are%20NOT%20integrated%20-%20iLUC%2C%20electricty%20markets%20and%20social%20extensions%20ARE%20included.ipynb) present the code required to perform the matrix inversion. The code for the tutorial 1 is valid for Exiobase v3.3.11b1 where investments are NOT integrated in the core matrix. The code in the tutorial 2 is valid for Exiobase v3.3.11b2 where investments ARE integrated in the core matrix. Also, in version 3.3.11b2, indirect Land Use Change activities, electricity markets and social extensions are included.
The Lontiev inverse function is detailed in the [Product System algorithms](https://github.com/BONSAMURAIS/bonsai/wiki/Make-Data-Usable#product-system-algorithms) description. 

* The [least square method tutorial](https://github.com/BONSAMURAIS/bonsai/blob/master/Overdetermined%20system%20resolution%20-%20sugar%20in%20soft%20drinks%20and%20spirits.ipynb) presents a case study using a data filling algorithm, which could be used by the [Input Output Framework](https://github.com/BONSAMURAIS/bonsai/wiki/Harvest%20Data#sut-gap-filling--correction-routines) working group.  

### NOTE: 
These tutorials are currently written to be executed with the Exiobase IO-database as background data. They are presented in Jupyter Notebooks, an open-source web application that allows creating and sharing documents that contain live code, equations, visualizations and explanatory text. This code works with Python 3.4, although it requires some additional packages such as Numpy and Pandas.
