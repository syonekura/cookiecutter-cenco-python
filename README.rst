===========================
Cookiecutter Python Project
===========================

Cookiecutter_ template for a Python package.

* GitHub repo: https://github.com/syonekura/cookiecutter-cenco-python
* Free software: BSD license

Features
--------

* Continuous Integration with VSTS
* Testing setup with ``py.test``
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4, 3.5, 3.6
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Bumpversion_: Pre-configured version bumping with a single command
* Command line interface using Click_ (optional)

.. _Cookiecutter: https://github.com/audreyr/cookiecutter

Quickstart
----------

- Install Python

- Install the latest Cookiecutter if you haven't installed it yet::

    pip install -U cookiecutter

- Install Pipenv::

    pip install pipenv

- Generate a Python package project::

      cookiecutter https://github.com/syonekura/cookiecutter-cenco-python

- Create a repo and put it there:

      cd your_project
      git init .

- Start a new environment and install all your dependencies there using
  `pipenv install`. This will keep track of every dependency in the Pipfile

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files


Not Exactly What You Want?
--------------------------

Don't worry, you have options:

Similar Cookiecutter Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `Nekroze/cookiecutter-pypackage`_: A fork of this with a PyTest test runner,
  strict flake8 checking with Travis/Tox, and some docs and `setup.py` differences.

* `tony/cookiecutter-pypackage-pythonic`_: Fork with py2.7+3.3 optimizations.
  Flask/Werkzeug-style test runner, ``_compat`` module and module/doc conventions.
  See ``README.rst`` or the `github comparison view`_ for exhaustive list of
  additions and modifications.

* `ardydedase/cookiecutter-pypackage`_: A fork with separate requirements files rather than a requirements list in the ``setup.py`` file.


Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description.

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

Or Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.


.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.io/
.. _`pyup.io`: https://pyup.io/
.. _Bumpversion: https://github.com/peritus/bumpversion
.. _PyPi: https://pypi.python.org/pypi
.. _Click: http://click.pocoo.org/6/

.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
