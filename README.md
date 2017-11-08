# Facial-Recognition
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
![](https://img.shields.io/badge/maintained-yes-green.svg?style=flat)

:hourglass: *Work in Progress*

built with :heartpulse:

:lock: Signed using GPG

Facial Detection using Eigenfaces

## Motivation

Trying to apply what I learned in class about Principal Component Analysis and 
Singular Value Decomposition and create a C-library for a set of functions that
will determine whether a given image contains a humanly-recognizable face or not,
and if recognized if it is a face that is in the dataset.
## How to Run

`make`
to build for release

`make debug`
to build for debugging

## TODOs

### Design Decisions

how to represent an image?
double**?

Catastrophic cancellation when normalizing?

### Linear Algebra functions

matmat_subtract()

matmat_multiply()

vecmat_multiply()

matvec_multiply()

matscalar_multiply()

mat_transpose()

### Libtiff



