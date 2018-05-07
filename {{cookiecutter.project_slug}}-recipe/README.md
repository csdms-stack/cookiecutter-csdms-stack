# About {{ cookiecutter.project_slug }}

Home: {{ cookiecutter.home }}

Package license: {{ cookiecutter.package_license }}

Recipe license: MIT

Summary: {{ cookiecutter.project_short_description }}

# Current build status

OSX: [![TravisCI](https://travis-ci.org/csdms-stack/{{cookiecutter.project_slug}}-recipe.svg?branch=master)](https://travis-ci.org/csdms-stack/{{cookiecutter.project_slug}}-recipe)

# Current release info

Version: [![Anaconda-Server Badge](https://anaconda.org/csdms-stack/{{ cookiecutter.project_slug }}/badges/version.svg)](https://anaconda.org/csdms-stack/{{ cookiecutter.project_slug }})
Downloads: [![Anaconda-Server Badge](https://anaconda.org/csdms-stack/{{ cookiecutter.project_slug }}/badges/downloads.svg)](https://anaconda.org/csdms-stack/{{ cookiecutter.project_slug }})

# Installing {{ cookiecutter.project_slug }}

Installing `{{ cookiecutter.project_slug }}` from the `csdms-stack` channel can be achieved by adding `csdms-stack` to your channels with:

```
conda config --add channels csdms-stack
```

Once the `csdms-stack` channel has been enabled, `{{ cookiecutter.project_slug }}` can be installed with:

```
conda install {{ cookiecutter.project_slug }}
```

It is possible to list all of the versions of `{{ cookiecutter.project_slug }}` available on your platform with:

```
conda search {{ cookiecutter.project_slug }} --channel csdms-stack
```
