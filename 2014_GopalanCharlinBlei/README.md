Content-based recommendations with Poisson factorization

by Prem Gopalan, Laurent Charlin, and David Blei, NIPS 2014.

Abstract
--------

We develop collaborative topic Poisson factorization (CTPF), a
generative model of articles and reader preferences. CTPF can be used
to build recommender systems by learning from reader histories and
content to recommend personalized articles of interest.  In detail,
CTPF models both reader behavior and article texts with Poisson
distributions, connecting the latent topics that represent the texts
with the latent preferences that represent the readers.  This provides
better recommendations than competing methods and gives an
interpretable latent space for understanding patterns of readership.
Further, we exploit stochastic variational inference to model massive
real-world datasets. For example, we can fit CPTF to the full arXiv
usage dataset, which contains over 43 million ratings and 42 million
word counts, within a day.  We demonstrate empirically that our model
outperforms several baselines, including the previous state-of-the art
approach.


Paper
-----

2014_GopalanCharlinBlei.pdf

Code
----

The C/C++ for CTPF is available here:
https://github.com/premgopalan/collabtm

Paper Source
------------

Source of the papers is in tex/

All figures in the papers are available from fig/. The raw data used to
generate figure that contain experimental results are in fig/dat/. They
can be generated using the R-scripts in fig/R/.