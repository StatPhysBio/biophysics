# Part 5: Poisson distribution, exponential distribution, and Gillespie algorithm

This part will introduce us to the Gillespie algorithm, an efficient method for creating realizations of stochastic processes to solve master equations, as well as give us the necessary statistical background to understand the underlying models and assumptions.

Download `tutorial5.ipynb`.
For downloading and opening Jupyter notebooks, see the explanation in [Part 1](https://github.com/StatPhysBio/biophysics/blob/main/part1/README.md#downloading-a-jupyter-notebook).
This notebook also uses `custom.mplstyle`. (You can download it from [Part 2](https://github.com/StatPhysBio/biophysics/tree/main/part2) and see tips in [Part 3](https://github.com/StatPhysBio/biophysics/tree/main/part3#part-3-statistical-distributions-statistics-and-the-central-limit-theorem) on how to have it used by this notebook.)

## Texts on statistical distributions and the Gillespie algorithm

- [Chapter 2](http://dna.ac/filogeografia/PDFs/Wakeley/Wakeley_06_Chapter_2.pdf) of *Coalescent Theory: An Introduction*, Wakeley
	- Clear, effective derivations of Poisson and exponential distributions
- [*Exact Stochastic Simulation of Coupled Chemical Reactions*](https://www.caam.rice.edu/~cox/gillespie.pdf)
	- The paper on the Gillespie algorithm
- *Stochastic Modeling for Systems Biology (3rd edition)*, Wilkinson
	- A terrific book on modeling and inference which details algorithms clearly and includes R code as examples for implementation