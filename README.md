# Python Starter

This is a Python project skeleton that will you get up and running quickly. It sets up the following:
- Pre-commit Hooks ([pre-commit](https://pre-commit.com/))
- Testing ([Pytest](https://docs.pytest.org/en/latest/))
- Code formatting ([Black](https://github.com/python/black) and [flake8](http://flake8.pycqa.org/en/latest/))
- Type checking ([mypy](http://mypy-lang.org/))

Prior to every commit, the **pre-commit hooks** will run unit tests, format the code, and perform
type checking.

## Project Setup
This starter project assumes you are using [pipenv](https://github.com/pypa/pipenv) to manage
virtual environments and project dependencies.

#### 1. Install project dependencies:
```
pipenv install --dev
```

#### 2. Setup project to use **pre-commit**:
```
pipenv run pre-commit install
```

#### 3. Install additional project dependencies:
```
pipenv install [package]
```
Use the **--dev** flag if needed.

#### 4. Run tests:
```
make test
```
Tests will be automatically run prior to every commit.

## Additional Notes
In addition to autoformatting the code via **Black** and **flake8** for each commit,
it does the following:
- Runs the unit tests
- Runs mypy for type checking

If you would like to disable this, edit this [file](.pre-commit-config.yaml).
