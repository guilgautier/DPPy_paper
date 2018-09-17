# DPPy_paper

[![Build Status](https://travis-ci.com/guilgautier/DPPy_paper.svg?token=jftmsjDJSt2JLJqsgR9n&branch=master)](https://travis-ci.com/guilgautier/DPPy_paper)

This is the companion paper associated with the [DPPy](https://github.com/guilgautier/DPPy) Python library which equipped with an extensive [documentation](https://dppy.readthedocs.io/en/latest/).

## Dependencies

[Pygments](http://pygments.org/) to use `minted` package for highlighting code.

```bash
pip install pygments
```

## Install the project

```bash
git clone https://github.com/guilgautier/DPPy_paper.git
cd DPPy_paper
pip install .
```

## Build the PDF

```bash
pdflatex --shell-escape tex/dppy_paper.tex
```

### How to cite this work?

[DPPy](https://github.com/guilgautier/DPPy) has the present [companion paper](https://github.com/guilgautier/DPPy_paper) to be submitted to the [JMLR Machine Learning Open Source Software](http://www.jmlr.org/mloss/) track.

If you use this package, please consider citing it with this piece of BibTeX:
```bibtex
@misc{DPPy,
    title =   {{DPPy: Sampling Determinantal Point Processes with Python}},
    author =  {Guillaume Gautier, Rémi Bardenet, Michal Valko},
    year =    {2018},
    url =     {https://github.com/guilgautier/DPPy/},
    howpublished = {Online at: \url{github.com/guilgautier/DPPy/}},
    note =    {Code at https://github.com/guilgautier/DPPy/, documentation at https://dppy.readthedocs.io/, companion paper at https://github.com/guilgautier/DPPy_paper/}
}
```

## Reproducibility

This paper together with the [DPPy](https://github.com/guilgautier/DPPy) Python library are fully reproducible.

We would like to thank \href{https://guillep.github.io/}{Guillermo Polito} for leading our reproducible research \href{https://github.com/CRIStAL-PADR/reproducible-research-SE-notes}{workgroup}, this project owes him a lot.
Take a look at the corresponding [booklet](https://github.com/CRIStAL-PADR/reproducible-research-SE-notes) to learn more on how to make your research reproducible!