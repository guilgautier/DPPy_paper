# DPPy_paper

[![Build Status](https://travis-ci.com/guilgautier/DPPy.svg?branch=master)](https://travis-ci.com/guilgautier/DPPy)
[![Documentation Status](https://readthedocs.org/projects/dppy/badge/?version=latest)](https://dppy.readthedocs.io/en/latest/?badge=latest)
[![Coverage Status](https://coveralls.io/repos/github/guilgautier/DPPy/badge.svg?branch=master)](https://coveralls.io/github/guilgautier/DPPy?branch=master)

This is the companion paper associated with the [DPPy](https://github.com/guilgautier/DPPy) Python library, itself supported by an extensive [documentation](https://dppy.readthedocs.io/en/latest/).

We wrote this companion paper to [DPPy](https://github.com/guilgautier/DPPy), for latter submission to the [MLOSS](http://www.jmlr.org/mloss/) track of JMLR.

The companion paper is available on:

- [arXiv](http://arxiv.org/abs/1809.07258) (maybe not upto date)
- [here on GitHub](https://github.com/guilgautier/DPPy_paper) for the lastest version

## Build the PDF

If you are on this page, you most likely already have [git](https://git-scm.com/):
```bash
git clone https://github.com/guilgautier/DPPy_paper.git
cd DPPy_paper/tex
```

Then, you need a full LaTeX installation, like [TeXlive](https://www.tug.org/texlive/) or [MikTex](https://miktex.org/) to build the `pdf`:
```bash
pdflatex dppy_paper.tex
```

If you use this package, please consider citing it with this piece of
BibTeX:

### How to cite this work?

If you use the [DPPy](https://github.com/guilgautier/DPPy) package, please consider citing it with this piece of BibTeX:

```bibtex
@article{GaBaVa18,
    archivePrefix = {arXiv},
    arxivId = {1809.07258},
    author = {Gautier, Guillaume and Bardenet, R{\'{e}}mi and Valko, Michal},
    eprint = {1809.07258},
    journal = {ArXiv e-prints},
    title = {{DPPy: Sampling Determinantal Point Processes with Python}},
    keywords = {Computer Science - Machine Learning, Computer Science - Mathematical Software, Statistics - Machine Learning},
    url = {http://arxiv.org/abs/1809.07258},
    year = {2018},
    note = {Code at http://github.com/guilgautier/DPPy/ Documentation at http://dppy.readthedocs.io/}
}
```

## Reproducibility

We would like to thank [Guillermo Polito](https://guillep.github.io/) for leading our reproducible research [workgroup](https://github.com/CRIStAL-PADR/reproducible-research-SE-notes), this project owes him a lot.

Take a look at the corresponding [booklet](https://github.com/CRIStAL-PADR/reproducible-research-SE-notes) to learn more on how to make your research reproducible!
