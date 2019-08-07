George
======

**Fast and flexible Gaussian Process regression in Python.**

.. image:: http://img.shields.io/travis/dfm/george/master.svg?style=flat
        :target: http://travis-ci.org/dfm/george
.. image:: http://img.shields.io/pypi/dm/george.svg?style=flat
        :target: https://pypi.python.org/pypi/george/
.. image:: http://img.shields.io/pypi/v/george.svg?style=flat
        :target: https://pypi.python.org/pypi/george/
.. image:: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
        :target: https://github.com/dfm/george/blob/master/LICENSE
.. image:: http://img.shields.io/badge/DOI-10.5281/zenodo.11989-blue.svg?style=flat
        :target: http://dx.doi.org/10.5281/zenodo.11989

Read the documentation at: `dan.iel.fm/george <http://dan.iel.fm/george>`_.



cd george

git submodule init

git submodule update

# if eigen3 is not installed:

# download eigen3 and add path to setup.py

# add "BayesianLinearRegressionKernel" and "TaskKernel" to "__all__" in george/kernels.py

python setup.py build_ext --inplace

python setup.py install
