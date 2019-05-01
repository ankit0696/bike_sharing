# bike-sharing

We develop a neural network from scratch (only NumPy) for predicting how many bikes to keep, so that an organization neither looses potential customers nor wastes money on bikes that are just sitting around.

## Getting Started

* clone the repository to your local machine or download it.
* make sure that relative ordering of the files are maintained
* run all the cells in _Your_first_neural_network.ipynb_

### Prerequisites

Following packages are required to reproduce result of this project

```
python                    3.7.2
numpy                     1.15.4
pandas                    0.24.0
matplotlib                3.0.2
jupyter                   1.0.0
```

### Installing

Create a virtual environment (i have used and given examples of _anaconda_ as package manager on linux feel free to use other package managers and OS)

* [install mini-conda](https://docs.conda.io/en/latest/miniconda.html) 

  run `conda --v` 
  
  output `conda x.x.x`
* create a virtual environment

  `conda create -n myenv python=3.7`
  
   Note: remove _myenv_ with the name of your environment
   
   activate the environment by `source activate myenv`
   
   deactivate the environment by `source deactivate`
* install the above mentioned packages by following commands
  ```
  source activate myenv   
  conda install -c anaconda numpy
  conda install -c anaconda pandas
  conda install -c anaconda matplotlib
  conda install -c anaconda jupyter
  source deactivate
  ```
* to ensure everything is installed properly
    
    activate the virtual environment
    
    run `conda list`
    
## reproducing the result

* activate the virtual environment
* run `jupyter notebook` 
* from the browser go to the project-directory 
* run _Your_first_neural_network.ipynb_
* execute all the cells in order
* finally a graph will be shown that compares your prediction with the test values
  ![prediction plot](https://github.com/ashunigion/bike-sharing/blob/master/_4_2.png)

* [the blog](https://medium.com/@ashunigion/bike-sharing-pattern-prediction-using-neural-network-developed-with-numpy-9b9516f1b598) elaborate on the steps of creating the model


## Acknowledgments

* i thank udacity for their deeplearning nanodegree
* i thank facebook for granting me this scholarship

