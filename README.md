# Cookiecutter csdms-stack

[Cookiecutter](https://github.com/audreyr/cookiecutter) template
for a csdms-stack recipe

* GitHub repo: https://github.com/csdms-stack/cookiecutter-csdms-stack
* Free software: MIT license

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet
(this requires Cookiecutter 1.4.0 or higher)::

    $ pip install -U cookiecutter

or

    $ conda install cookiecutter -c conda-forge

Generate a csdms-stack recipe::

    $ cookiecutter https://github.com/csdms-stack/cookiecutter-csdms-stack.git

Then:
* Create a repo and put it there
* Add the repo to csdms-stack [Travis-CI](https://travis-ci.org) account
* Run the Travis CLI command

    $ travis encrypt --add "ANACONDA_TOKEN=<token>"
