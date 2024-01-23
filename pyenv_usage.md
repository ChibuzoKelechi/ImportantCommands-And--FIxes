# Usage commands for pyenv

## Installation

* pyenv --version
* pyenv install python 3.x.x
* pyenv install --list
* pyenv versions

## To set up virtual environment

* pyenv virtualenv 3.10.10 env_name
* pyenv shell env_name

## To restart shell

export PYENV_ROOT="$HOME/.pyenv"
[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
