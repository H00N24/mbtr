Introduction
============

MBTR is a python package for multivariate boosted tree regressors trained in parameter space.
The package can handle arbitrary multivariate losses, as long as their gradient and Hessian are known.
Gradient boosted trees are competition-winning, general-purpose, non-parametric regressors, which exploit sequential
model fitting and gradient descent to minimize a specific loss function. The most popular implementations are tailored
to univariate regression and classification tasks, precluding the possibility of capturing multivariate target
cross-correlations and applying conditional penalties to the predictions. This package allows to arbitrarily regularize
the predictions, so that properties like smoothness, consistency and functional relations can be enforced.

Installation
************
The package can be installed via pip:

.. code-block:: bash

    pip3 install mbtr

or cloned from the offical repository `mbtr`_



.. _mbtr: https://github.com/supsi-dacd-isaac/mbtr

Citation
********
If you make use of this software for your work, we would appreciate it if you would cite us:

.. code-block:: bibtex

    @article{nespoli2020multivariate,
      title={Multivariate Boosted Trees and Applications to Forecasting and Control},
      author={Nespoli, Lorenzo and Medici, Vasco},
      journal={arXiv preprint arXiv:2003.03835},
      year={2020}
    }

Aknowledgments
**************
The authors would like to thank the Swiss Federal Office of Energy (SFOE) and the
Swiss Competence Center for Energy Research - Future Swiss Electrical Infrastructure (SCCER-FURIES),
for their financial and technical support to this research work.

