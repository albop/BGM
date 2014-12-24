*Monopoly Power and Endogenous Product Variety: Distortions and Remedies* : production of welfare graphs.
========================================================================================================

Installation
------------

Required programs to produce the graphs are
- a recent distribution of scientific Python for instance [Anaconda Python](https://store.continuum.io/cshop/anaconda/)
- the [dolo](https://github.com/EconForge/dolo) modeling package

Producing the graphs
--------------------

The code is contained in a [IPython](http://ipython.org/) notebook. To view and execute it:
- Open a terminal and change the working directory so that it contains the `Produce Graphs.ipynb` file.
- Launch `ipython notebook`. This should open a list of notebooks in a web browser. Click on `Produce Graphs.ipynb`.
- Perform the computations using menu item `Cell/Run all` or execute each cell one by one with `shift+enter`.

The notebook will solve three versions of the baseline model (with CES-benassy, translog and exponential specifications) with
several values of the parameters. The models are coded using `dolo` specifications in the `model_ces.yaml`, `model_translog.yaml` and `model_exponential` files.
The welfare computations are based on a second order Taylor expansion of the decision-rule.

Output
------

The resulting graphs are stored in the `BGM_welfare_gains.*` files.
