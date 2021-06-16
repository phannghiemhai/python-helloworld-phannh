========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-helloworld-phannh/badge/?style=flat
    :target: https://python-helloworld-phannh.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/phannghiemhai/python-helloworld-phannh.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/phannghiemhai/python-helloworld-phannh

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/phannghiemhai/python-helloworld-phannh?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/phannghiemhai/python-helloworld-phannh

.. |requires| image:: https://requires.io/github/phannghiemhai/python-helloworld-phannh/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/phannghiemhai/python-helloworld-phannh/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/phannghiemhai/python-helloworld-phannh/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/phannghiemhai/python-helloworld-phannh

.. |version| image:: https://img.shields.io/pypi/v/python-helloworld-phannh.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/python-helloworld-phannh

.. |wheel| image:: https://img.shields.io/pypi/wheel/python-helloworld-phannh.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/python-helloworld-phannh

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/python-helloworld-phannh.svg
    :alt: Supported versions
    :target: https://pypi.org/project/python-helloworld-phannh

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/python-helloworld-phannh.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/python-helloworld-phannh

.. |commits-since| image:: https://img.shields.io/github/commits-since/phannghiemhai/python-helloworld-phannh/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/phannghiemhai/python-helloworld-phannh/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install python-helloworld-phannh

You can also install the in-development version with::

    pip install https://github.com/phannghiemhai/python-helloworld-phannh/archive/master.zip


Documentation
=============


https://python-helloworld-phannh.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
