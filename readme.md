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


### Exercise completion

| Chapter | Ex1  | Ex2  | Ex3  | Ex4  | Ex5  | Ex6  | Ex7  | Ex8  | Ex9  | Ex10 | Ex11 |
| ------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1       |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 2       |    - |    V |    V |    V |    V |    - |    - |    - |    - |    - |    - |
| 3       |    V |    V |    V |    V |    V |    - |    - |    - |    - |    - |    - |
| 4       |    V |    V |    V |    V |    V |    V |    * |    * |    - |    - |    - |
| 5       |    V |    V |    V |    V |    V |    V |    V |    V |    V |    V |    ! |
| 6 N. 2  |    V |    * |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 7       |    V |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 8       |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 9       |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 10      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 11      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 12      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 13      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 14      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 15      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 16      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 17      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 18      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 19      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 20      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 21      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 22      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 23      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 24      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |
| 25      |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |    - |

#### Legend: 

```
X - not started
* - in progress
V - completed
! - blocked
```

#### Notes

1. Ex 5.11 is blocked due to the dataset from the website has different structure from the examples in the book.
2. Some models for chapter 6 are not present in statsmodels or sklearn. I'll skip it for now as the general approaches and ideas are clear so far.
