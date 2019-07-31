Getting started.

The eaiest way to get started is by downloading Anaconda, and creating a Python 3.7 "mlbc" environment.
  
https://www.anaconda.com/distribution/
(which python version, 3.x [as in 3.something, like 3.7])

1. Go to Anaconda command prompt and create an enviornment:

>> conda create -n mlbc anaconda python=3.7

Here we have created a python 3.7 environment named "mlbc", that contains all packages 
available at Anaconda such as Numpy, Scipy, etc.

You have now created the environment. To view the jupyter notebook do the following:

2. Go to Anaconda Prompt and activate mlbc environment
>> activate mlbc

3. Run jupyter
>> jupyter notebook

4. This launches in your browser, now naviate to the folder and select the .ipynb file.
---------------------------------------------------------------------------------------------

For .py scripts:
1. Go to anaconda command prompt and activate mcg environment
>> activate mcg

2. Run Spyder IDE (or change this to PyCharm or whichever IDE you prefer/have installed.)
>> spyder

3. Open the .py (or drag and drop into the Spyder IDE)

Done
-----------------------------------------------------------------------------------------
More 
Install a library like this if you find that a library is not recognised.
>> pip install biosppy

list conda environments
>> conda env list

See this too:
https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf

