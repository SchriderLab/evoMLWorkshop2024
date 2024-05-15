This exercise uses a `jupyter` notebook, so you should already have `jupyter` installed on your system.

To get started, we need to load the right environment, which in this case is `msprime-env`:

`conda activate msprime-env`

But, it turns out I forgot a few additional packages that need to be added to this environment, so after activating it, do the following:

1) Install `scikit-allel` using either:

   `conda install -c conda-forge scikit-allel`

   or

   `pip install scikit-allel`

2) Install `matplotlib`:

   `conda install matplotlib`

3) Install `scipy`:

   `conda install scipy`

Now you should be good to go! Load `jupyter` as follows:

`jupyter notebook`

This should open `jupyter` in a browser window, and you should then be able to open the `sweep_detection.ipynb` file and complete the exercise.
