# Personal Bookshelf

[![Build Status](https://dev.azure.com/fdahlitz/personal-bookshelf/_apis/build/status/DahlitzFlorian.personal-bookshelf?branchName=master)](https://dev.azure.com/fdahlitz/personal-bookshelf/_build/latest?definitionId=3&branchName=master)
![black](https://img.shields.io/badge/code%20style-black-000000.svg)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Description

Represents a personal bookshelf allowing the multi-user usage.

## Install

To install this project on your machine for development, clone the repository and go to the
projects directory. Optionally, you can create a virtual environment to keep things clean.
After that run:

```bash
$ python -m pip install -e .
```

## Test

To run the tests, you need to install additional dependencies (you may do it inside of a
virtual environment) and run the tests:

```bash
$ python -m pip install '.[test]'
$ pytest
```

## Status

Currently in development.

## Contributing

If you are interested in contributing, please check out the [CONTRIBUTING.md](CONTRIBUTING.md).
There you find information about the commit and branch naming conventions as well as about the
general Gitflow.


[tox]: https://tox.readthedocs.io/en/latest/
