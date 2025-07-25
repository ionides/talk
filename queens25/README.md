# Toward automatically differentiable particle filters for phylodynamic inference

## Slides: [pdf](slides.pdf)

## Abstract

Recently developed particle filters enable simulation-based likelihood calculation for a general class of compartment models observed via dynamic tree-valued data. In many areas of machine learning and statistical inference, automatic differentiation and GPU computation have enabled the development of algorithms capable of using large amounts of data to fit complex models. For technical reasons, practical particle filter methodology has been slow to incorporate these advanced tools. We present a new approach to automatic differentiation of particle filters applicable to a broad class of partially observed dynamic systems. We discuss the application to phylodynamic inference.


## Reproducibility

```
cd ~/git/talk/queens25
rm -rf .venv
python3.12 -m venv .venv
source ~/git/talk/queens25/.venv/bin/activate
pip install --update pip
pip install -r requirements.txt

make slides.pdf

```
