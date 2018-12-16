========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|



.. |travis| image:: https://travis-ci.org/wmeints/motorcontrol.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/wmeints/motorcontrol

.. |codecov| image:: https://codecov.io/github/wmeints/motorcontrol/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/wmeints/motorcontrol

.. |version| image:: https://img.shields.io/pypi/v/motorcontrol.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/motorcontrol

.. |commits-since| image:: https://img.shields.io/github/commits-since/wmeints/motorcontrol/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/wmeints/motorcontrol/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/motorcontrol.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/motorcontrol

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/motorcontrol.svg
    :alt: Supported versions
    :target: https://pypi.org/project/motorcontrol

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/motorcontrol.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/motorcontrol


.. end-badges

A library to control two DC motors using the Raspberry PI.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install motorcontrol

Documentation
=============


To use the project:

.. code-block:: python

    import motorcontrol
    motorcontrol.longest()


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
