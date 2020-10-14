# MLFlowDemoEstafet
Jupyter notebooks of the 14.10.2020 presentation of MLFlow'. MLFlow is a python framework designed to manage, log and deploy machine learning mocels.

## Setup
Clone the code to your local machine (git clone). Once there, you need to install jupyter lab (https://jupyter.org/install) and anaconda (https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to be able to start the environment (jupyter-lab + conda) in which you will be able to run the notebooks (ipynb files).

### Dependencies 
The code needs the following python libraries to work properly:
* numpy (1.19.2)
* pandas (1.1.3)
* scikit-learn (0.23.2)
* mlflow (1.11.0)

### Starting the Jupyter Lab
First, launch a new anaconda prompt. Once the command invite appeared, install all the dependences listed above (**pip install 'package'=='version'**) if they are not already installed. If you have other versions, use the command **pip install -Iv 'package'=='version'** instead.

Once you have installed all the dependencies, run the command **jupyter-lab** in your anaconda prompt.

## Running the notebooks
The notebooks have a prefix, ranging from 1 to 3. Then need to be executed in increasing order. The first notebook will walk you through the creation of a ML model and its optimization. The second notebook will display how to serve a model (expose it to the world through an API) and the third notebook explains some useful additional features of MLFlow.

## Test
If you want to test your deployment from outside your local machine, you will need to route the port 1234 and your local ip address. These extra steps are not covered in that project.

## Final notes

This project follows the MLFlow tutorial and extends it. You can find the original at this URL: https://www.mlflow.org/docs/latest/tutorials-and-examples/tutorial.html.
The data set used in this example is from http://archive.ics.uci.edu/ml/datasets/Wine+Quality,
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.,
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

