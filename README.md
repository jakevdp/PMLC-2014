PMLC-2014
=========

Lecture materials for Microsoft Practice of Machine Learning Conference, Oct 23-24 2014.

This is a one-hour introductory tutorial to the scikit-learn package.

You can follow along by installing Python and several dependencies, numpy, scipy, matplotlib, ipython, and (of course) scikit-learn. See the **Setup and Installation** section below.

If you do not have this Python stack installed on your system, you can follow-along with a static view of this material on nbviewer [here](http://nbviewer.ipython.org/urls/raw.github.com/jakevdp/PMLC-2014/master/Scikit-Learn-Intro.ipynb).

## Setup and Installation
To get Python up and running across multiple platforms, I recommend the [Anaconda](http://continuum.io/downloads) installer (or, for a lighter-weight install, use [miniconda](http://conda.pydata.org/miniconda.html))
If you're using Anaconda, you can assure that you're using the latest scikit-learn release by running:

```
$ conda update conda
$ conda install scikit-learn
```

If your system has a suitably set-up ``C`` compiler, scikit-learn can be installed using ``pip``:

```
$ pip install scikit-learn
```

You can have a little more control by installing scikit-learn from source. The source is available using the ``git`` version management tool:

```
$ git clone https://github.com/scikit-learn/scikit-learn.git
$ cd scikit-learn
$ python setup.py install
```

Scikit-learn requires ``NumPy`` and ``SciPy``, and examples require ``Matplotlib``.

**Note**: some examples below require the scripts in the ``fig_code`` directory, which
can be found within the Github repository at http://github.com/jakevdp/PMLC-2014