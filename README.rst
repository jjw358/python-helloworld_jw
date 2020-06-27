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
.. |docs| image:: https://readthedocs.org/projects/python-helloworld_jw/badge/?style=flat
    :target: https://readthedocs.org/projects/python-helloworld_jw
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/jjw358/python-helloworld_jw.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/jjw358/python-helloworld_jw

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/jjw358/python-helloworld_jw?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/jjw358/python-helloworld_jw

.. |requires| image:: https://requires.io/github/jjw358/python-helloworld_jw/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/jjw358/python-helloworld_jw/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/jjw358/python-helloworld_jw/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/jjw358/python-helloworld_jw

.. |version| image:: https://img.shields.io/pypi/v/helloworld-jw.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/helloworld-jw

.. |wheel| image:: https://img.shields.io/pypi/wheel/helloworld-jw.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/helloworld-jw

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/helloworld-jw.svg
    :alt: Supported versions
    :target: https://pypi.org/project/helloworld-jw

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/helloworld-jw.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/helloworld-jw

.. |commits-since| image:: https://img.shields.io/github/commits-since/jjw358/python-helloworld_jw/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/jjw358/python-helloworld_jw/compare/v0.0.1...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install helloworld-jw

You can also install the in-development version with::

    pip install https://github.com/jjw358/python-helloworld_jw/archive/master.zip


Documentation
=============


https://python-helloworld_jw.readthedocs.io/


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
