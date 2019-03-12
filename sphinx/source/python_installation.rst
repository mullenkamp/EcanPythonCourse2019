Installing Python
===============================
Installing Python is relatively simple and does not require admin rights to install.

Install Miniconda3
------------------
The first step is to download and install the Python 3 64bit version of `Miniconda <https://conda.io/en/latest/miniconda.html>`_. Miniconda is a variant of the `Anaconda <https://www.anaconda.com/>`_ distribution, but Miniconda only contains the base Python installation and the package manager `conda <https://conda.io/en/latest/>`_. See the earlier link for more details about Miniconda and how to install it.

Packages
--------
Everything other than the base Python installation is considered an ancillary package. The base Python is meant to provide a foundation for other people and organizations to build upon...and many people have build many great packages. With tens of thousands of packages, something needs to manage the handling and cross-dependencies of all these packages. That's what conda does.

Channels
--------
Conda also has the concept of Channels. Different people and organizations can have their own set of packages that they are working on and be kept separate from the greater ecosystem of packages. The default channel is managed by the Anaconda organization, while the channel called conda-forge is a community driven channel of packages. It is recommended to set conda-forge as the default channel to ensure all of the packages are installed consistently.

Go to the start menu and open up the recently added Anaconda prompt.
Copy and paste the following line to the prompt to make conda-forge the default channel:

.. code::

  conda config --prepend channels conda-forge

Then update your packages to make everything nice and consistent:

.. code::

  conda update conda

Installing Packages
-------------------
Now that you have Miniconda all set up, you can install any number of additional packages with one line on the Anaconda prompt opened from earlier:

.. code::

  conda install pandas spyder numpy

Where "conda install" tells conda to install packages which should be followed by the package names with spaces in between (in our case we want to install pandas, spyder, and numpy). Conda handles all of the downloading and installing of those packages.

At this point, you should be ready write Python code and run it in the `Spyder <https://www.spyder-ide.org/>`_ development environment!


Environments
------------
Just to add a bit more complexity to the existing Python, conda, packages, and channels from earlier, conda also has the concept of python environments. When you installed Python/Miniconda you created the base Python environment. When you opened the Anaconda prompt, you started in this base environment and any packages you install will be placed in this base environment. Additional environments allows you to create additional independent Python installations with their own independent set of packages. This becomes very important when you create multiple scripts with different sets of packages that you don't want to mix.

To create a new environment, use the following syntax:

.. code::

  conda create --name newenv python=3.6 pandas spyder

Where newenv is the name you are calling the new environment then followed by the packages you want to install.

**Please download** and look at the `conda cheat sheet <https://conda.io/projects/conda/en/latest/_downloads/conda-cheatsheet.pdf>`_ for many of the commands to use conda.
