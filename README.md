# DPPy_paper

[![Build Status](https://travis-ci.org/guilgautier/DPPy_paper.svg?branch=arXiv-v1)](https://travis-ci.org/guilgautier/DPPy_paper)

This is the companion paper associated with the [DPPy](https://github.com/guilgautier/DPPy) Python library, itself supported by an extensive [documentation](https://dppy.readthedocs.io/en/latest/).

This paper together with [DPPy](https://github.com/guilgautier/DPPy) are fully reproducible.

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

### How to cite this work?

We wrote this companion paper to [DPPy](https://github.com/guilgautier/DPPy), for latter submission to the [MLOSS](http://www.jmlr.org/mloss/) track of JMLR.

The companion paper is available on:
- [arXiv](http://arxiv.org/abs/1809.07258) or see the [`arxiv`](https://github.com/guilgautier/DPPy_paper/tree/arxiv) branch
- [GitHub](https://github.com/guilgautier/DPPy_paper)

If you use this package, please consider citing it with this piece of BibTeX:

```bibtex
@article{GaBaVa18,,
    archivePrefix = {arXiv},
    arxivId = {1809.07258},
    author = {Gautier, Guillaume and Bardenet, R{\'{e}}mi and Valko, Michal},
    eprint = {1809.07258},
    journal = {ArXiv e-prints},
    title = {{DPPy: Sampling Determinantal Point Processes with Python}},
    keywords = {Computer Science - Machine Learning, Computer Science - Mathematical Software, Statistics - Machine Learning},
    url = {http://arxiv.org/abs/1809.07258},
    year = {2018},
    note = {Code at https://GitHub.com/guilgautier/DPPy/ ; Documentation at http://DPPy.ReadTheDocs.io/}
}
```

## Reproducibility

We would like to thank [Guillermo Polito](https://guillep.github.io/) for leading our reproducible research [workgroup](https://github.com/CRIStAL-PADR/reproducible-research-SE-notes), this project owes him a lot.

Take a look at the corresponding [booklet](https://github.com/CRIStAL-PADR/reproducible-research-SE-notes) to learn more on how to make your research reproducible!
