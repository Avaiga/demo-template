# Installation

## Install with _requirements.txt_

You can install the requirements by clonning the repo version of _demo-<INSERT-DEMO-NAME>_ with _pip_ and _git_:
```
git clone https://github.com/Avaiga/demo-<INSERT-DEMO-NAME>.git
cd src
pip install -r requirements.txt
```

## Install with `Pipenv`:
  
```
pip install pipenv
git clone https://github.com/Avaiga/demo-<INSERT-DEMO-NAME>.git
cd demo-<INSERT-DEMO-NAME>
pipenv install --dev
pipenv run pytest
```
