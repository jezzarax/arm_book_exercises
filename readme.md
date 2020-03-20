## Yet another repository with book exercises

Solutions to exercises from a great book [Data analysis using regression and multilevel hierarchical models](http://www.stat.columbia.edu/~gelman/arm/). 

The book implies it to be in R, but due to python being my main tool for dealing with data, I wanted to work on both, the book exercises and improving my python statistical toolbox skills.

Also, the book is awesome, goes into subtle details of linear methods making them much more powerful and interpretable. Makes a lot of modern ML less magical :)

I was doing it with jupyterlab. Some charts, formulae and layouts might be broken in github viewer or normal jupyter.


### Installation and running the examples

* Ensure that your system has python 3.7 and [pipenv](https://github.com/pypa/pipenv) installed. I'm pretty opinionated about environment management in python, pipenv provided me the best experience out of all tools I tried.
* Clone the repository and enter the directory with it.
* Run `pipenv --three install`.
* After pipenv finishes creating the environment, enter it with `pipenv shell` while still being inside of the repository directory.
* Run `jupyter lab` and explore the notebooks.