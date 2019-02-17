Prerequisites
=================================================

Python environments
-------------------
Using the Jupyter Notebooks for the workshop modules
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
This workshop uses self contained code sets called `Jupyter Notebooks <http://jupyter.org/>`_. The workshop will not explicitly require you to install python on your PC, but you are welcome to try as described in the next paragraph. Consequently for the workshop, the preferred method to run the notebooks will be through the `binder <https://mybinder.org/>`_ links that build the correct python environment for the notebooks to be run under. This ensures that no one will have issues properly running the notebooks.

**Please run through** the short notebook `A quick tour of Jupyter/IPython Notebooks <https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2Fpandas-cookbook%2Fcookbook%2FA%20quick%20tour%20of%20IPython%20Notebook.ipynb>`_. It will familiarise you with Jupyter notebooks and some of its capabilities, but don't worry if you don't understand everything.

Installing a Python environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
If you would like to install your own Python environment, then please read through and follow the documentation in `Intro to Python for Environmental Scientists <https://basic-python.readthedocs.io/en/latest/installing_python.html>`_ especially as it relates to installing Anaconda/Miniconda and creating multiple python environments. If you feel like you'd like to give it a try, download the `environment.yml <https://raw.githubusercontent.com/Data-to-Knowledge/Hydrosoc-python-2018/master/environment.yml>`_ from this workshop's github repo and run the following line from the Anaconda prompt:

.. code::

  conda env create -f environment.yml

It might take a couple minutes, but just be patient...
