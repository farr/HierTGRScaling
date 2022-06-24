<p align="center">
<a href="https://github.com/showyourwork/showyourwork">
<img width = "450" src="https://raw.githubusercontent.com/showyourwork/.github/main/images/showyourwork.png" alt="showyourwork"/>
</a>
<br>
<br>
<a href="https://github.com/farr/HierTGRScaling/actions/workflows/build.yml">
<img src="https://github.com/farr/HierTGRScaling/actions/workflows/build.yml/badge.svg?branch=main" alt="Article status"/>
</a>
<a href="https://github.com/farr/HierTGRScaling/raw/main-pdf/arxiv.tar.gz">
<img src="https://img.shields.io/badge/article-tarball-blue.svg?style=flat" alt="Article tarball"/>
</a>
<a href="https://github.com/farr/HierTGRScaling/raw/main-pdf/ms.pdf">
<img src="https://img.shields.io/badge/article-pdf-blue.svg?style=flat" alt="Read the article"/>
</a>
</p>

# Accumulation of Bayesian Evidence In Hierarchical Population Models

We consider how evidence accumulates from repeated observations in models that introduce a continuous deformation parameter to an underlying physical theory.  We imagine that the true deformation of the theory is constant from observation to observation, and explore models where the deformation is assumed constant but unknown from observation to observation or where the deformation is drawn independently from a Gaussian with unknown mean and variance for each observation.  Both these models can recover the true data generating process at specific parameter values, but also admit parameter values that do not match the true data generating process.  As expected in the limit of a large number of independent observations, these models have reduced Bayesian evidence relative to the true model for the data generating process.  But we find that the log evidence for these models is reduced by a term that grows only *logarithmically* in the number of observations relative to the true model; the model with a constant deformation parameter for each observation suffers half the (logarithmic) reduction relative to the model where the deformation parameter is normally distributed across observations.  But both models suffer much less reduction in log evidence compared to a model where the deformation is fixed to an incorrect value for each observation, for which the log evidence relative to the true model decreases *linearly* in the number of observations.  Thus we conclude that both models are about equally "efficient" at detecting or ruling out deformations from the underlying physical theory; but we advocate for the model with normally distributed deformation parameters across observations because it is robust to true data generating processes where the deformation *is not* constant from observation to observation.