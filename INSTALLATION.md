# Installation

The latest stable version of _demo-<INSERT-DEMO-NAME>_ is available through _pip_:
```
pip install demo-<INSERT-DEMO-NAME>
```

## Development version

You can install the development version of _demo-<INSERT-DEMO-NAME>_ with _pip_ and _git_:
```
pip install git+https://git@github.com/Avaiga/demo-<INSERT-DEMO-NAME>
```

## Work with the _demo-<INSERT-DEMO-NAME>_ code
```
git clone https://github.com/Avaiga/demo-<INSERT-DEMO-NAME>.git
cd demo-<INSERT-DEMO-NAME>
pip install .
```

If you want to run tests, please install `Pipenv`:
```
pip install pipenv
git clone https://github.com/Avaiga/demo-<INSERT-DEMO-NAME>.git
cd demo-<INSERT-DEMO-NAME>
pipenv install --dev
pipenv run pytest
```
