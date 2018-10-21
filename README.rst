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

.. |docs| image:: https://readthedocs.org/projects/python-cookiecutter-demo/badge/?style=flat
    :target: https://readthedocs.org/projects/python-cookiecutter-demo
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/dsem/python-cookiecutter-demo.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/dsem/python-cookiecutter-demo

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/dsem/python-cookiecutter-demo?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/dsem/python-cookiecutter-demo

.. |requires| image:: https://requires.io/github/dsem/python-cookiecutter-demo/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/dsem/python-cookiecutter-demo/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/dsem/python-cookiecutter-demo/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/dsem/python-cookiecutter-demo

.. |version| image:: https://img.shields.io/pypi/v/cookiecutter-demo.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/cookiecutter-demo

.. |commits-since| image:: https://img.shields.io/github/commits-since/dsem/python-cookiecutter-demo/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dsem/python-cookiecutter-demo/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/cookiecutter-demo.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/cookiecutter-demo

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cookiecutter-demo.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/cookiecutter-demo

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cookiecutter-demo.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/cookiecutter-demo


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install cookiecutter-demo

Documentation
=============


https://python-cookiecutter-demo.readthedocs.io/


Development
===========

To run the all tests run::

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
