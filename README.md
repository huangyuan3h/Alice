# Alice

- [Alice](#alice)
  - [Environment](#environment)
    - [python env manager](#python-env-manager)
    - [Python Version](#python-version)

Project Alice is currently a personal project to aim to create a `artifical learning intelligence common system`.

Currently, the system is plan use python, as this area, this is the only option.

## Environment

### python env manager

pyenv: <https://github.com/pyenv/pyenv>

### Python Version

Current version is 3.8.1, but still use 3.7

So

``` shell
pyenv install 3.8.1
```

then create venv:

```shell
python3 -m venv .env
```

after create the venv, point the python version to that one:

```shell
source .env/bin/activate
```

install requirement dependency:

```shell
pip install -r requirements.txt
```
