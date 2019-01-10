---
title: "Creating an interactive version of your code (mybinder.org)"
---
[mybinder.org](https://mybinder.org/)^[The documentation is available [here](https://mybinder.readthedocs.io/en/latest/index.html).] is an awesome way of sharing your Python code and Jupyter notebooks in a GitHub repository by creating an interactive environment, where other people can run (but not change) your code without having Python installed.

## The most simple setup

1. Go to mybinder.org
2. Paste the link to the GitHub repository
3. Save the resulting mybinder.org link 
4. Press launch - wait and a Jupyter notebook will launch
6. Share the mybinder.org link with other

## Including dependencies

The above setup works fine, and as you know it is possible to install dependencies in a Jupyter Notebook using the syntax `!pip install [package1 ...]` or `!conda install [package1 ...]`. Thought, you can do this it is better to supply an environment.yml file that contains all the projects dependencies^[You can read more about `environment.yml` [here](https://www.earthdatascience.org/workshops/setup-earth-analytics-python/setup-python-anaconda-earth-analytics-environment/#about-the-conda-environment) and here is an example of an [`.environment.yml`](https://github.com/NumEconCopenhagen/lectures-2019/blob/master/binder/environment.yml) file].

The way you let _mybinder.org_ know about your dependencies is to do the following:

1. Create a folder named `/binder` in your root directory. 
2. In the folder create the file `/binder/environment.yml` add your channels, add pip and conda dependencies.

If your are interested in a more advanced configuration than above please see [here](https://mybinder.readthedocs.io/en/latest/config_files.html)

### Examples

First we will fire up a Jupyter motebook using _mybinder.org_ where no `Python` packages is installed other than those which ships with `Python`.

{{< figure src="installing-packages.gif" width="100%" class="text-center">}}

In the second example we show how we can install the packages used in the first example before the Jupyter session is launched using a `environment.yml` file.

{{< figure src="env.gif" width="100%" class="text-center" >}}