# qathar
<p align="center">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&label=code-status&message=Good&color=orange"/>
  <img src="https://img.shields.io/static/v1?style=for-the-badge&label=initial-commit&message=Shantanu&color=inactive"/>
    <img src="https://img.shields.io/static/v1?style=for-the-badge&label=maintainer&message=qathar&color=inactive"/>
</p>


**Documentation**: TODO

## Motivation

This repo is a template for python package creation.

## Installation

*Conda users, please make sure to `conda install pip` before running any pip installation if you want to install `qathar` into your conda environment.*

`qathar` may soon be published on PyPI. Once it is, simply run the following code to install the package:

```bash
pip install qathar
```
If you also want to download the dependencies needed to run optional tutorials, please use `pip install qathar[dev]` or `pip install 'qathar[dev]'` (for `zsh` users).


To check if the installation was successful, run:

```bash
python -c "import qathar"
```

This should execute silently if installation was successful.

## Building from source

To build `qathar` from source, pip install using:

```bash
git clone git@github.com:qcnet/NYUAD-2023.git qathar
cd team-13/qathar
pip install --upgrade .
```

If you also want to download the dependencies needed to run optional tutorials, please use `pip install --upgrade .[dev]` or `pip install --upgrade '.[dev]'` (for `zsh` users).

#### Installation for Devs

If you intend to contribute to this project, please install `qathar` in editable mode as follows:
```bash
git clone git@github.com:qcnet/NYUAD-2023.git qathar
cd team-13/qathar
pip install -e .[dev]
```

Please use `pip install -e '.[dev]'` if you are a `zsh` user.

Installing the package in the usual non-editable mode would require a developer to upgrade their pip installation (i.e. run `pip install --upgrade .`) every time they update the package source code.

## Documentation

Documentation should be viewable here: TODO

#### View locally


To view documentation locally, please open `docs/build/html/index.html` in your browser.


#### Build documentation 

To rebuild documentation, please start in the root folder and run:

```sh
cd docs
make clean
make html
```

*You may also have to delete the `docs/source/_autosummary` directory before running the above commands.*


## Acknowledgements

**Core Devs:** Anubhav Shrestha, Deepesh Garg, Dhruv Srinivasan, Dilyara Sharipova, Oyungerel Amarsanaa, Samhitha Bharthulwar, Sasha Malik, Shantanu Jha, Tasnim Ahmed, Yeji Han


This project was created by the qathar team at NYUAD Hack 2023.

