Student Research Project Radar Dealiasing
=========================================

Using python and Py-ART to compare hand-dealiased and pyart region-dealiased
weather data.

For the SULI/SRP summer internship program, working under Scott Collis and
Jonathan Helmus, researching the difference between hand dealiased radar
velocity data and Py-ART's region dealiaser. The data used is CSU cpol data.

It was determined that Py-ART's region dealiasing function works quite well,
sometimes produce close to or even better than the hand dealiased data. The
data was presented on a poster at Argonne’s first “Learning on the Lawn”
symposium where the summer students present their research.

Py-ART Source
-------------
The Python ARM Radar Toolkit, `Py-ART <http://arm-doe.github.io/pyart/>`_,
is a Python module containing a collection of weather radar algorithms and
utilities. Py-ART is used by the Atmospheric Radiation Measurement (ARM)
Climate Research Facility for working with data from a number of its
precipitation and cloud radars, but has been designed so that it can be used
by others in the radar and atmospheric communities to examine, processes,
and analyze data from many types of weather radars.

Helmus, J.J. & Collis, S.M., (2016). The Python ARM Radar Toolkit (Py-ART),
a Library for Working with Weather Radar Data in the Python Programming
Language. Journal of Open Research Software. 4(1), p.e25. DOI:
http://doi.org/10.5334/jors.119
