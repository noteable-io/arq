# Contributing

Thanks for your interest in contributing to `arq`.
This document outlines how to get set up locally and how to make your first contribution.

## Getting started

### Prerequisites

1. Install [Git](https://git-scm.com/downloads)
1. Install [pyenv](https://github.com/pyenv/pyenv#installation)
1. Install [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv#installing-as-a-pyenv-plugin)

### Setting up your local environment

1. Clone the repository: `git clone git@github.com:samuelcolvin/arq.git`
1. Change directory: `cd arq`
1. Install Python: `pyenv install 3.10.8`
1. Create a virtualenv: `pyenv virtualenv 3.10.8 arq-3.10.8`
1. Use the virtualenv: `pyenv local arq-3.10.8`
1. Install the project: `make install`
1. Run the tests: `make test`
1. Run the linter: `make lint`
1. Format the code: `make format`
