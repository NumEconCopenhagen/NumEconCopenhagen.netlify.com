---
title: "Creating an interactive version of your code (mybinder.org)"
---
[mybinder.org](https://mybinder.org/)^[The documentation is available [here](https://mybinder.readthedocs.io/en/latest/index.html)] is an awesome way of sharing you python code and jupyter notebook within an interactive environment where other people can run your code, change your code without affecting the actual code. 

## The most simple setup

1. Go to mybinder.org
2. Paste the link to the github repository
3. Wait and a Jupyter Notebook will launch

## Including dependencies

The above setup works fine, and as you know it is possible to install dependencies in a Jupyter Notebook using the syntax `!pip install [package1 ...]` or `!conda install [package1 ...]`. Thought, you can do this it is better to supply an environment.yml file that contains all the projects dependencies^[You can read more about `environment.yml` [here](https://www.earthdatascience.org/workshops/setup-earth-analytics-python/setup-python-anaconda-earth-analytics-environment/#about-the-conda-environment) and here is an example of an [`.environment.yml`](https://github.com/NumEconCopenhagen/lectures-2019/blob/master/binder/environment.yml) file].

The way you let _mybinder.org_ know about your dependencies is to do the following:

1. Create a folder named `/mybinder` in your root directory. 
2. In the folder create the file `/mybinder/environment.yml` add your channels, add pip and conda dependencies.

If your are interested in a more advanced configuration than above please see [Docs - configuration files](https://mybinder.readthedocs.io/en/latest/config_files.html)

### Examples

First we will fire up a Jupyter Notebook using _mybinder.org_ where no `Python` packages is installed other than those which ships with `Python`.

{{< figure src="installing-packages.gif" width="100%" class="text-center">}}

The second example we show how we can install the packages used in the first example before the Jupyter Session is launched using a `environment.yml` file.

{{< figure src="env.gif" width="100%" class="text-center" >}}