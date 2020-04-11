# taskcicd - CICD based on taskfiles

Demonstration of powerfull yaml syntax of taskfiles
for job automation, environment building
and dependency resolution

## Installations 

### Task Go - Actions Executer

More on https://taskfile.dev.

> Please install task from 
> `https://github.com/go-task/task/releases/tag/v2.8.0`

- **Windows**. 
    - Unarchive it 
    - put to C:\Windows\System32 or other Dir in %PATH% environment variable

- **Linux amd Mac OSs**. 
    - unarchive it: `tar xvf task*.tar.gz`
    - make runnable: `chmod +x task`
    - move it to $PATH dir: `mv task /usr/local/bin`

### Conda For Python DS/ML Dev

For local development we have need to manage python virtual environments,
and sometimes python versions. 
There are a couple ways of doing it:

- `python -m venv` + manual python verion install
- `pyenv` (manual install) + `python -m venv`
- `pyenv` (manual install) + `Pipenv`
- poetry + pyenv
- conda https://docs.conda.io/en/latest/license.html

Well most painfull part here is not the venv management,
which can be reduced to python 3 module venv `python -m venv`,
but the python itself version.

Currently in 2020 we still have ubuntu 16 with default python 3.5,
different kinds of mac os with `brew` python as the only alternative,
and manuall install or use of `choko` on windows.

The most "python way" solution is currently `poetry`,
(which still requires python version management).
The most simple and easier for data scientiets 
approach is `conda`. which have a lots of precompiled modules 
on mac and win and lin.

My Personal choice is wide python management by conda,
and package management with poetry.





