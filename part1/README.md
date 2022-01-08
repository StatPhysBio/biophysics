# Part 1: Python tutorial

The best way to learn programming is by doing. 
Here, we begin to learn what tools are at our disposal and how to use them.

## Downloading a Jupyter notebook
1. Click `init_tutorial.ipynb` and then click `raw`.
2. Right-click, select `Save page as`.
A new window should pop up.
3. Specify which folder you want the file to be downloaded to. Perhaps 
4. There should also be a dropdown menu near the bottom center called "Format" or something similar.
Make sure you select the format as "All Files" instead of "Text Files" otherwise `init_tutorial.ipynb` will be saved as `init_tutorial.ipynb.txt`.

## Opening the Jupyter notebook


1. Start `Anaconda prompt`/`Terminal`.
2. Type ```conda activate biophys2022```.
3. Type `jupyter lab`. A browser window should appear, and JupyterLab should be running.
4. On the left side of your browser, you should see a file system which shows you directories and files in your home directory. Navigate to where you saved `init_tutorial.ipynb`.
5. Double click `init_tutorial.ipynb`.
6. Which kernel the notebook is using is shown near the bug-looking button, all the way to the right of the save button. Ensure the kernel is `biophys2022`. 


## Python basics

There are many tutorials for learning Python.
A quick Google search will show you Python documentation, open courses, YouTube videos, Stack Overflow threads, etc.
If you have any questions, know that there is most likely a solution or answer on the web somewhere.
(See [Guideline 3](https://github.com/StatPhysBio/biophysics/tree/main/part0#guidelines).)
While what you can do with Python is practically limitless and so is the amount of information on the web about Python, we will learn specifically about Python in the context of scientific computing.
What you learn here is not by any means exhaustive, but it should be enough to do some interesting things in biophysics.

A nice tutorial that's easy to follow and is thorough enough for our purposes is [Introduction to Programming in the Biological Sciences Bootcamp](https://justinbois.github.io/bootcamp/2021/index.html) by Justin Bois.
We will attempt to go over as much of the relevant basics as we can in class.
**I expect you to go through lessons 3 through 10 if you do not have any prior Python experience.**

## Numpy and plotting tutorials

[Numpy](https://numpy.org/) is a package which lays the foundation for performing scientific computing using Python.
Numpy is developing their own [tutorials](https://numpy.org/numpy-tutorials/index.html).
Tutorials on Numpy basics can be found elsewhere ubiquitously. 
For instance, [Machine Learning with Python](https://machine-learning-with-python.readthedocs.io/en/latest/#) by Tirthajyoti Sarkar provides a nice [notebook](https://github.com/tirthajyoti/Machine-Learning-with-Python#essential-tutorial-type-notebooks-on-pandas-and-numpy) for getting a handle on the basics and conventions of Numpy.

There are many plotting packages for Python.
We will largely be using [Matplotlib](https://matplotlib.org/).
(Other good packages include [Seaborn](https://seaborn.pydata.org/), [plotly](https://plotly.com/python/), and [plotnine](https://plotnine.readthedocs.io/en/stable/).)
Matplotlib provides a nice [page](https://matplotlib.org/stable/tutorials/index) which points you to many tutorials.
Again, the best way to learn is by doing.
To become familiar with how to plot using Matplotlib (or other packages), devise a question (story), produce or obtain some numbers, and ask yourself how can you answer that question (tell that story).

There are many ways to tell stories through data visualization.
Producing the optimal visual isn't necessarily an easy problem.
It's easy to make a visual for the story you *think* you're telling, but that visual may not actually communicate the story you'd like it to tell.
Additionally, even if you do choose the optimal type of plot for your story, it's easy to create an ugly plot that no one will want to look at.
Below are some useful texts on how you can tell stories through data visualization and on making good choices when plotting.

## Texts on visualization

- *Envisioning Information*, Tufte
- *Fundamentals of Data Visualization*, Wilke
- *The Visual Display of Quantitative Information*, Tufte
- *Visual Explanations*, Tufte
