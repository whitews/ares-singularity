# ares-singularity
Singularity recipe for running the ARES neural network described in the paper:

Townshend RJL, Eismann S, Watkins AM, Rangan R, Karelina M, Das R, Dror RO. Geometric deep learning of RNA structure. Science. 2021 Aug 27;373(6558):1047-1051. doi: [10.1126/science.abe5650](https://doi.org/10.1126/science.abe5650). PMID: 34446608.

## Source Code

Original source code and example data can be found here:

https://zenodo.org/record/5088971

The ARES-compatible E3NN library can be found here:

https://zenodo.org/record/5090151

## Build

`singularity build ares-singularity.sif ares-singularity.def`

## Run

`singularity run ares-singularity.sif`
