# Part 2: Numerical integration and the SIR model

This part will teach us about numerical integration, specifically [Euler's method](https://en.wikipedia.org/wiki/Euler_method), and the [SIR model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SIR_model_without_vital_dynamics).

Download `part2_nb.ipynb`.
For downloading and opening Jupyter notebooks, see the explanation in [Part 1](https://github.com/StatPhysBio/biophysics/blob/main/part1/README.md#downloading-a-jupyter-notebook).
Also download `custom.mplstyle` the same way you downloaded the Jupyter notebook.
`custom.mplstyle` is a file which changes the default settings in Matplotlib and makes things arguably prettier and easier to see.
To enable it, use

```python
import matplotlib.pyplot as plt
plt.style.use('/PATH/TO/custom.mplstyle')
```

where you replace `/PATH/TO/` with where `custom.mplstyle` was saved.