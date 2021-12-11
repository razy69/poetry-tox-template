# How to start

## Python version + venv
```bash
$ pyenv install 3.10
$ pyenv virtualenv 3.10 py310-template
$ pyenv activate py310-template
$ python3 -m pip install -U pip
$ python3 -m pip install poetry==1.2.0a2 tox
```

## Install all deps
```bash
$ poetry install --with quality,format,security,changelog
```

## Run tox
