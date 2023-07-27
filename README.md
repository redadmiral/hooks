# Github Hooks

This repo contains github hooks for my personal use in Python projects.

## Installation

Simply clone this repo in the `.git` folder in your repo.

### Dependencies

The hook relies on the pyenv conventions to work properly. It needs a virtual environment `precommit` with the packages

- black
- ruff
- safety

installed.

Also for the pytest run, it is necessary to have your virtualenv named as the folder of the repo.
