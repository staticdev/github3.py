github4.py
==========

|PyPI| |Python Version| |License|

|Read the Docs| |Tests| |Codecov|

|pre-commit| |Black|

.. |PyPI| image:: https://img.shields.io/pypi/v/github4.py.svg
   :target: https://pypi.org/project/github4.py/
   :alt: PyPI
.. |Python Version| image:: https://img.shields.io/pypi/pyversions/github4.py
   :target: https://pypi.org/project/github4.py
   :alt: Python Version
.. |License| image:: https://img.shields.io/pypi/l/github4.py
   :target: https://opensource.org/licenses/MIT
   :alt: License
.. |Read the Docs| image:: https://img.shields.io/readthedocs/github4/latest.svg?label=Read%20the%20Docs
   :target: https://github4.readthedocs.io/
   :alt: Read the documentation at https://github4.readthedocs.io/
.. |Tests| image:: https://github.com/staticdev/github4.py/workflows/Tests/badge.svg
   :target: https://github.com/staticdev/github4.py/actions?workflow=Tests
   :alt: Tests
.. |Codecov| image:: https://codecov.io/gh/staticdev/github4.py/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/staticdev/github4.py
   :alt: Codecov
.. |pre-commit| image:: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
   :target: https://github.com/pre-commit/pre-commit
   :alt: pre-commit
.. |Black| image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Black


github4.py an actively developed wrapper around the GitHub API that forks github3.py_.

Note: This library currently works with Python 3.7+ or pypy3. For older versions, please use github3.py_ version 1.3.0.

Installation
------------

You can install *github4.py* via pip_ from PyPI_:

.. code:: console

   $ pip install github4.py

Dependencies
------------

- dateutil_
- requests_
- uritemplate_

.. _dateutil: https://github.com/dateutil/dateutil
.. _requests: https://github.com/kennethreitz/requests
.. _uritemplate: https://github.com/sigmavirus24/uritemplate

Contributing
------------

Contributions are very welcome.
To learn more, see the `Contributor Guide`_.

License
-------

Distributed under the terms of the MIT_ license,
*github4.py* is free and open source software.

Issues
------

If you encounter any problems,
please `file an issue`_ along with a detailed description.

Credits
-------

Original author of github3.py_ is Ian Stapleton Cordasco (sigmavirus24_).

.. _sigmavirus24: https://github.com/sigmavirus24
.. _github3.py: http://stackoverflow.com/questions/tagged/github3.py
.. _MIT: http://opensource.org/licenses/MIT
.. _PyPI: https://pypi.org/
.. _file an issue: https://github.com/staticdev/github4.py/issues
.. _pip: https://pip.pypa.io/
.. _Contributor Guide: CONTRIBUTING.rst
