# Part 6: Population dynamics with the Moran model

This part introduces us to the Moran model, a forward-in-time population dynamics model, implemented using the Gillespie algorithm.
We will study neutral evolution as well as evolution that incorporates selection and mutation processes.
Besides looking at realizations of these processes, we will compute easily interpretable statistics to understand the different regimes of evolution.

Download `tutorial6.ipynb`.
For downloading and opening Jupyter notebooks, see the explanation in [Part 1](https://github.com/StatPhysBio/biophysics/blob/main/part1/README.md#downloading-a-jupyter-notebook).
This notebook also uses `custom.mplstyle`. (You can download it from [Part 2](https://github.com/StatPhysBio/biophysics/tree/main/part2) and see tips in [Part 3](https://github.com/StatPhysBio/biophysics/tree/main/part3#part-3-statistical-distributions-statistics-and-the-central-limit-theorem) on how to have it used by this notebook.)

## Texts on population genetics

- *Evolutionary Dynamics: Exploring the Equations of Life*, Nowak
	- An accessible textbook which discusses population genetics theory using game theory and discusses the Moran model in discrete time
- [*From biophysics to evolutionary genetics: statistical aspects of gene
regulation*, section "Evolution of regulatory DNA," Lässig](https://bmcbioinformatics.biomedcentral.com/counter/pdf/10.1186/1471-2105-8-S6-S7.pdf#page=10)
	- A clear, brief derivation of the Langevin and Fokker-Planck (diffusion) equations for population dynamics with fitness and mutations along with a useful section on theory related to substitution events
- [*Probability models for DNA sequence evolution*, Durrett](https://services.math.duke.edu/~rtd/Gbook/PM4DNA_0317.pdf)
	- An intermediate text on population genetics theory and modeling
- Coalescent Theory: An Introduction, Wakeley
	- An accessible textbook about the coalescent, a backward-in-time model for population dynamics