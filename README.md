# DPPy_paper

[![Build Status](https://travis-ci.com/guilgautier/DPPy_paper.svg?token=jftmsjDJSt2JLJqsgR9n&branch=master)](https://travis-ci.com/guilgautier/DPPy_paper)

Companion paper associated to the [DPPy](https://github.com/guilgautier/DPPy) Python library

## Dependencies

[Pygments](http://pygments.org/)

```bash
pip install pygments
```
to use `minted` package for highlighting code.

## Build the LaTex file

Clone this repository and run `setup.py`
```bash
git clone https://github.com/guilgautier/DPPy_paper.git
cd DPPy_paper
pip install .
```

Build the PDF
```bash
pdflatex --shell-escape tex/dppy_paper.tex
```
