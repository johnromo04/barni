BARNI - Benchmark Algorithm for RadioNuclide Identification
========================================================

BARNI is a software for radionuclide identification from gamma-ray spectra. 

It uses a machine learning approach to train for a variaity of spectroscopic gamma-ray radiation detectors.

Introduction
------------
This README file is meant as a simple overview of the BARNI repository. 

Documentation
-------------
[Full documentation](https://barni.readthedocs.io/en/latest/) is generated by sphinx. 


Directory Structure
-------------------
The following is an overview of the top directory structure folders:

* `barni`: Code of the BARNI python package. 
* `doc`: The Sphinx documentation of the BARNI package. 
* `examples`: Input and configuration files for running BARNI identification and training routines
* `test`: Unit tests for the code found in the `barni` folder.

In addition, there are various files on the top directory:

* `barni_cli.py`: BARNI command line interface module.
* `barni_cli.spec`: PyInstaller configuration file.
* `pyinstall.py`: PyInstaller build script. 
* `barni.yml`: Anaconda environment file.
* `nose2.cfg`: Nose2 (unit test) configuration file. 
* `setup.py`: BARNI package installation script. 
* `LICENSE`: The liscence description. 


Required Libraries
------------------
* Python 3.7+
* Numpy 1.17+
* SciKit-Learn 0.20+
* Bokeh 1.4+
* Pandas 0.25+

Contributing
------------
Contributing to BARNI is relatively easy.  Just send us a
[pull request](https://help.github.com/articles/using-pull-requests/).
When you send your request, make ``develop`` the destination branch on the
[barni repository](https://github.com/llnl/barni).

Your PR must pass BARNI's unit tests and documentation tests, and must be
[PEP 8](https://www.python.org/dev/peps/pep-0008/) compliant.  We enforce
these guidelines with Travis CI.  To
run these tests locally simply use [tox](https://tox.readthedocs.io/en/latest/). 
BARNI uses a rough approximation of the
[Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)
branching model.  The ``develop`` branch contains the latest
contributions, and ``master`` is always tagged and points to the latest
stable release.

Authors
-------

- Mateusz Monterial, LLNL
- Karl Nelson, LLNL

License
-------

BARNI is released under an MIT license. For more details see the [LICENSE](/LICENSE) file.

SPDX-License-Identifier: MIT

LLNL-CODE-805904
