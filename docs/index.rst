=======
movekit
=======

This is the documentation of **movekit**.

.. image:: ../media/mover.gif
   :width: 250px
   :height: 200px
.. image:: ../media/voronoi.png
   :width: 250px
   :height: 200px
.. image:: ../media/network.png
   :width: 250px
   :height: 200px

movekit is an open-source software package for the processing and analysis of movement data. It has several selling points, for example

* Data pre-processing (e.g. data checks, smoothing, duplicate removal, interpolation, outlier detection)
* Feature extraction (e.g. speed, acceleration, heading)
* Individual-level movement analysis (e.g. autocorrelation, speed distribution, environment exploration)
* Group-level analysis (e.g. cohesion, polarisation, coordination, leadership, clustering)
* Spatial data analysis (Voronoi, delaunay triangulation)
* Network analysis with networkX


Contents
========

.. toctree::
   :maxdepth: 2

   Quick Start <quick_start>
   Data Cleaning <examples/01_data_cleaning>
   Feature Extraction <examples/02_extract_features>
   Group Feature Extraction <examples/03_group_features>
   Spatial Analysis <examples/04_spatial_analysis>
   Network Analysis <examples/05_network_analysis>
   Cluster Analysis <examples/06_clustering>
   License <license>
   Authors <authors> 
   Changelog <changelog>
   Module Reference <api/modules>


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _toctree: http://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html
.. _reStructuredText: http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. _references: http://www.sphinx-doc.org/en/stable/markup/inline.html
.. _Python domain syntax: http://sphinx-doc.org/domains.html#the-python-domain
.. _Sphinx: http://www.sphinx-doc.org/
.. _Python: http://docs.python.org/
.. _Numpy: http://docs.scipy.org/doc/numpy
.. _SciPy: http://docs.scipy.org/doc/scipy/reference/
.. _matplotlib: https://matplotlib.org/contents.html#
.. _Pandas: http://pandas.pydata.org/pandas-docs/stable
.. _Scikit-Learn: http://scikit-learn.org/stable
.. _autodoc: http://www.sphinx-doc.org/en/stable/ext/autodoc.html
.. _Google style: https://github.com/google/styleguide/blob/gh-pages/pyguide.md#38-comments-and-docstrings
.. _NumPy style: https://numpydoc.readthedocs.io/en/latest/format.html
.. _classical style: http://www.sphinx-doc.org/en/stable/domains.html#info-field-lists

Acknowledgments
===============
movekit is funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under Germany's Excellence Strategy – EXC 2117 – 422037984.