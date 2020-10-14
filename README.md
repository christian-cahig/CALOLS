
# A Consumer Appliance-Level Framework for Optimized Load Shedding

---

## Overview

An implementation of the paper
*Consumer Appliance-level Load Shedding Optimization for Real-time Application*
by
Jabian, Funaki, and Murata
which is yet to appear in a peer-reviewed journal.

This is part of the curricular requirements of the graduate course
EE 257 Optimization in Power Systems
offered by Mindanao State University - Iligan Institute of Technology
and handled by Engr. Abdul Aziz G. Mabaning.

---

## Directory

### Paper

The primary documentation for this project is the paper entitled
*A Consumer Appliance-Level Framework for Optimized Load Shedding*.
Everything related to the paper is in [`./Paper`](./Paper/).
Some of the key files:

- [`paper_ieee_journ.tex`](./Paper/paper_ieee_journ.tex)
  contains the LaTeX code.
  As of now, the paper is only available in the
  [IEEE journal article format](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/authoring-tools-and-templates/tools-for-ieee-authors/ieee-article-templates/).
- [`paper_ieee_journ.pdf`](./Paper/paper_ieee_journ.pdf)
  is the compiled PDF file of the paper.
- [`references.bib`](./Paper/references.bib)
  contains the bibliographic information.
- [`figures.pptx`](./Paper/figures.pptx)
  is basically a makeshift "figure manager" where most of the figures in the paper are created and prepared.

**Note:** As this project is currently an on-going effort,
the paper is not yet final and will continually be updated throughout the duration of the course.

### Datasets

Data files and regarding the datasets are in [`./Dataset/`](./Dataset/).
Aside from the paper, documentation pertaining to the datasets are also avaialable in the following files:

- [`Preparation.ipynb`](./Dataset/Preparation.ipynb)
  contains codes used in building the datasets.
- [`Exploratory Analyses.ipynb`](./Dataset/Exploratory%20Analyses.ipynb)
  contains codes used in performing quantitative analysis on the datasets.
- [`Benchmarks.ipynb`](./Dataset/Benchmarks.ipynb)
  contains codes used in benchmark tests on the datasets.

### Others

[`./Miscellaneous`](./Miscellaneous) contains some supporting files
that are not directly used in the paper, in the datasets, or in the experiments.

Much of the work is performed in a conda environment with the following key packages:

- Python 3.8.0
- Matplotlib 3.3.2
- NumPy 1.19.2
- pandas 1.1.2

To replicate the environment, use [`calols.yml`](./Miscellaneous/calols.yml);
*e.g.*, via

```pwsh
(base) PS C:\WINDOWS\system32> conda env create --file calols.yml
```

We use [MathType](http://www.wiris.com/mathtype) to typeset equations
and mathematical symbols in [`figures.pptx`](./Paper/figures.pptx).
Preferences (*e.g.*, fonts) are stored in
[`Default MathType Preferences.eqp`](./Miscellaneous/Default%20MathType%20Preferences.eqp),
which can then be loaded in MathType.

---

## Updates

This project is under active development.

<!-- ## Paper

Lorem ipsum

For specific questions about the paper, please contact
<a href="mailto:christian.cahig@g.msuiit.edu.ph">Christian Cahig</a>.

--- -->
