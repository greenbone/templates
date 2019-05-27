# Greenbone Templates for repositories on GitHub

A collection of templates we use to keep the quality consistent over the various projects we maintain.

To use a template, remove the `-template` part from the filename and place the
file in the top level directory of your repository unless otherwise noted.

## .clang-format

The `.clang-format` template provides a specification for the formatting of C
code by the `clang-format` tool. The template is compatible with `clang-format`
>= 6.0.

## ISSUE_TEMPLATE.md

The ISSUE_TEMPLATE.md is shown to the user when they create a new issue on
GitHub. We want to ensure that users provide the necessary information and to
redirect support questions to our community forum. This file needs to be placed
into a directory named `.github`.

## .pylintrc

The .pylintrc is the configuration for [Pylint](https://www.pylint.org/) which is used to test the code quality of our python projects.

## pyproject.toml

The `pyproject.toml` template provides a consistent specification of the minimum
build system requirements for Python projects. The file format is specified in
[PEP518](https://www.python.org/dev/peps/pep-0518/).

The template contains configuration options for the
[autohooks](https://github.com/bjoernricks/autohooks) framework and for the
[black](https://github.com/ambv/black) code formatter. Together, this
configuration makes sure that all commits are properly formatted in a consistent
style.

Note that both `autohooks` and `black` need to be present in the development
environment for the configuration to be applied.

## README.md

We want to establish a consistent structure of the readme in our projects.

There are several projects that provide a readme template out there, for example https://www.makeareadme.com/ with a general suggestion for open source projects or the [Standard Readme Style Specification](https://github.com/RichardLitt/standard-readme) especially for code modules. They differ only in details on the suggested sections. A good resource on writing great READMEs is also [Art of README](https://github.com/noffle/art-of-readme).

Our template is heavily based on these two templates.

The first project using this template is [gvm-tools](https://github.com/greenbone/gvm-tools#readme), which can be used as an example.

## License

Copyright (C) 2019 [Greenbone Networks GmbH](https://www.greenbone.net/)

Licensed under the [Creative Commons Attribution Share Alike 4.0 International](LICENSE) license.
