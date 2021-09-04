# cookiecutter-poetry-base

python project template with pre-configured development tools:
 - mypy: Static Typing for Python
 - poetry: Dependency Management for Python
 - nitpick: Command-line tool and flake8 plugin to enforce the same settings across multiple language-independent projects.
 - wemake-python-styleguide
 - tox: automation tool with preconfigured test script (tox.ini)
 - pytest
 - pytest-cov
 
## usage
 1. install cookiecutter: 
 `pip install --user cookiecutter` [link](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html)
 2. install poetry: 
 `curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -`
 [link](https://python-poetry.org/docs/)
 3. create project: `cookiecutter gh:hamedsh/cookiecutter-poetry-base`
