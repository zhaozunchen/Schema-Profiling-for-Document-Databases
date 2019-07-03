# Schema-Profiling-for-Document-Databases

## Install
This program is run in Jupyter Notebook. Please install Anaconda and all related packages. 

## Install Anaconda
Please refer to Anaconda official documentation to install Anaconda https://docs.anaconda.com/anaconda/install/windows/

## Use Anaconda and jupyter notebook

When you install Anaconda, it will also install jupyter notebook. Launching jupyter notebook can be done in different ways:
You can lunch it through Anaconda Navigator (Windows).
* Launch it by Anaconda Prompt (Windows):
  * Open Anaconda Prompt
  * Type: 
  ```sh
  jupyter notebook
  ```
  * hit Enter
  * wait jupyter notebook pop up
* Launch it by Terminal (Linux):
  * Open Terminal
  * Type: 
  ```sh
  jupyter notebook
  ```
  * hit Enter
  * wait jupyter notebook pop up

You will see a pop up website which host in local host.

## How to use?
* Download research.ipynb
* After you launch the jupyter notebook, Looking for the downloaded research.ipynb in the launched website
* Click the research.ipy to open it.
* In order to run a code cell, you should select that code cell and click Shift + Enter.
* Import packages:
  * In this section, run the cell with all packages
* Load data:
  * In this section, we provided couple ways to load dataset
  * Choose one of the ways to load your dataset
  * Also you can create your own way to load dataset
  * After Load data, the data variable is a list of dictionary which contains all data
* Get Number of Schemas:
  * In this section, you need to run the cells which define some methods, the last code cell is the driven method, You will see the number of schemas and number of documents
* Algorithm:
  * In this section, there are some methods which will be used in the algorithm. You should run each code cell
* Run:
  * In this section, there are three code cells. You need to run it in order
    * The first code cell bruilds the initial node
    * The second code cell is the driven methods which call necessery methods
    * The third code cell gives you some related informations like number of function calls
* Visualization:
  * In this section, you need to run those code cells in order
  * You will get the final decision tree figure
If you change your dataset, you don't havet to run all code cells, after run Load data section which load different dataset, run Run section to process the algorithm and Visualization section to get the decision tree figure.

