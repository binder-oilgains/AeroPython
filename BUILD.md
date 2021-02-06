# BUILD

[toc]

-----



## Add URL links to run Binder

1.  Open the folder `lessons`
2.  Open what is in the branch `master`. 

```
* Open index.ipynb: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/binder-oilgains/AeroPython/master?filepath=lessons)

* Open Jupyter main: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/binder-oilgains/AeroPython/master)
```





## Add Anaconda

```
name: aeropython

channels:
  - conda-forge

dependencies:
  - python=3.7
  - numpy
  - notebook
  - pandas
  - mastplotlib
```

