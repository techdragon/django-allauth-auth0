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
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/django-allauth-auth0/badge/?style=flat
    :target: https://readthedocs.org/projects/django-allauth-auth0
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/django-allauth-auth0.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/django-allauth-auth0

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/django-allauth-auth0?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/django-allauth-auth0

.. |requires| image:: https://requires.io/github/techdragon/django-allauth-auth0/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/django-allauth-auth0/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/techdragon/django-allauth-auth0/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/django-allauth-auth0

.. |landscape| image:: https://landscape.io/github/techdragon/django-allauth-auth0/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/django-allauth-auth0/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/django-allauth-auth0/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/django-allauth-auth0
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/django-allauth-auth0.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/django-allauth-auth0

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/django-allauth-auth0/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/django-allauth-auth0/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/django-allauth-auth0.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/django-allauth-auth0

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/django-allauth-auth0.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/django-allauth-auth0

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/django-allauth-auth0.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/django-allauth-auth0

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/django-allauth-auth0/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/django-allauth-auth0/


.. end-badges

Auth0 specific code for use with Django AllAuth

* Free software: BSD license

Installation
============

::

    pip install django-allauth-auth0

Documentation
=============

https://django-allauth-auth0.readthedocs.io/

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
