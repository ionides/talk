# Pypomp: Inference for partially observed Markov process models using GPUs and automatic differentation with JAX

[High Performance Statistical Computing (HSPC)](https://hpsc4science.org/)

Wed 9/2, 9am ET
Friday, November 13, 2026, at 11:00 AM ET

## Slides: [pdf](https://ionides.github.io/talk/hpsc26/slides.pdf)

## Abstract

Model development and parameter estimation for non-Gaussian partially observed Markov process (POMP) mechanistic models are fundamental challenges in a variety of fields including epidemiology, ecology, and finance. Particle filter methods can provide statistically efficient inference for highly nonlinear POMP models, but their practical application is limited by high computational demands. We introduce Pypomp, a high-performance Python library for statistical inference using POMP models. Pypomp includes state-of-the-art particle filtering algorithms to take advantage of GPU hardware, just-in-time computation, and automatic differentiation accessed using JAX. Basic inference algorithms run up to 1000 faster than on a CPU, and advanced algorithms provide further acceleration. Pypomp provides a comprehensive interface that streamlines model construction, fitting, and analysis, allowing practitioners to develop and evaluate complex models with minimal implementation overhead. We discuss case studies using Pypomp to investigate ecological and epidemiological systems.

## Reproducibility

```
source ~/git/talk/hpsc26/.venv/bin/activate
make slides.pdf

```
