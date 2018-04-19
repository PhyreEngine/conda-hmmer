This repository contains a [conda][conda] recipe for building [HMMER][hh], a
suite of tools for biosequence analysis using profile hidden Markov models.

The HMMER distribution is packged with Easel: this recipe builds backages for
both HMMER and Easel.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `./build`.
This recipe will build several variants, one for each supported CPU
architecture.

[conda]: https://conda.io
[miniconda]: https://conda.io/miniconda.html
[hh]: http://hmmer.org/
