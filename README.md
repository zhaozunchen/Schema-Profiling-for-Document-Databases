# Schema-Profiling-for-Document-Databases

## Install
This program is run in Jupyter Notebook. Please install Anaconda and all related packages. 

## Install Anaconda
Please refer to Anaconda offical documentation to install Anaconda https://docs.anaconda.com/anaconda/install/windows/

## Use Anaconda and jupyter notebook

When you install Anaconda, it will also install jupyter notebook. Lunching jupyter notebook can be done in different ways:
You can lunch it through Anaconda Navigator (Windows).
* Lunch it by Anaconda Prompt (Windows):
  * Open Anaconda Prompt
  * Type: 
  ```sh
  jupyter notebook
  ```
  * hit Enter
  * wait jupyter notebook pop up
* Lunch it by Terminal (Linux):
  * Open Terminal
  * Type: 
  ```sh
  jupyter notebook
  ```
  * hit Enter
  * wait jupyter notebook pop up

## Install packages

I reconmmend install packages through Anaconda Prompt (Windows) or Terminal(Linux). The following code cell is all packages you need to install. Please search the package name in the search bar at https://anaconda.org/. Click the correct package. You will find a command that you need to enter to install those package. Please refer to https://github.com/cpcloud/ipython-autotime to install autotime package.
Load all needed packages

```sh
%load_ext autotime
import pymongo
import json
import copy
import math
import statistics
import time
import collections
import random 
import csv
import pandas as pd
import pydot
from IPython.display import Image, display
from tqdm import tqdm_notebook, tnrange
import pprint
from graphviz import Graph
from random import shuffle
```
