# Part 3: Statistical distributions, statistics, and the central limit theorem

This part will introduce us to statistics, specifically the [binomial distribution](https://en.wikipedia.org/wiki/Binomial_distribution), [mean](https://en.wikipedia.org/wiki/Mean), [variance](https://en.wikipedia.org/wiki/Variance), [Gaussian/normal distribution](https://en.wikipedia.org/wiki/Normal_distribution), and [central limit theorem](https://en.wikipedia.org/wiki/Central_limit_theorem). Additionally, we get to become more acquainted with what we can do using NumPy.

Download `tutorial3.ipynb`.
For downloading and opening Jupyter notebooks, see the explanation in [Part 1](https://github.com/StatPhysBio/biophysics/blob/main/part1/README.md#downloading-a-jupyter-notebook).
This notebook also uses `custom.mplstyle`. (You can download it from [Part 2](https://github.com/StatPhysBio/biophysics/tree/main/part2).)
You can do at least three things for it to be utilized:

1. Save `tutorial3.ipynb` where `custom.mplstyle` was saved.
2. Copy `custom.mplstyle` to where you saved `tutorial3.ipynb`
3. Change `/PATH/TO/` in

	```python
	import matplotlib.pyplot as plt
	plt.style.use('/PATH/TO/custom.mplstyle')
	```
to where `custom.mplstyle` is saved.