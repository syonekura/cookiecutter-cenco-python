===========================
Cookiecutter Python Project
===========================

Cookiecutter_ template for a Python package.

* GitHub repo: https://github.com/syonekura/cookiecutter-cenco-python
* Free software: BSD license

Features
--------

* Continuous Integration with Azure DevOps Pipelines
* Environment and dependency management with Pipenv_
* Testing setup with PyTest_
* Tox_ testing: Setup to easily test for Python 2.7, 3.6, etc
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

- Go to the created project folder and make a repository::

      cd your_project
      git init .

- Install your dependencies there using `pipenv install`. This will keep
  track of every dependency in the Pipfile::

      pipenv install --dev # This will install default packages
      pipenv install <your specific dependencies>
      pipenv shell


.. _Pipenv: https://pipenv.readthedocs.io/en/latest/
.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.io/
.. _`pyup.io`: https://pyup.io/
.. _Bumpversion: https://github.com/peritus/bumpversion
.. _PyPi: https://pypi.python.org/pypi
.. _Click: http://click.pocoo.org/6/
.. _PyTest: https://docs.pytest.org/en/latest/

.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
