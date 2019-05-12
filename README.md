# Python Starter

This Python Starter repo is a skeleton you can use to get a quick project up and running. This
repo sets up the following:
- Pre-commit Hooks ([pre-commit](https://pre-commit.com/))
- Testing ([Pytest](https://docs.pytest.org/en/latest/))
- Code formatting ([Black](https://github.com/python/black) and [flake8](http://flake8.pycqa.org/en/latest/))
- Type checking ([mypy](http://mypy-lang.org/))

## Project Setup
This starter project assumes you are using [pipenv](https://github.com/pypa/pipenv) to manage
virtual environments and project dependencies.

Install project dependencies:
```
pipenv install --dev
```

Initialize the project to use pre-commit:
```
pipenv run pre-commit install
```
