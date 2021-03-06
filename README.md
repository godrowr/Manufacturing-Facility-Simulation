# Manufacturing Facility Simulation
## SYSC 4005 Project
### By: Ryan Gaudreault, Omar Imran, Marcel LeClair
## Milestone Changes
In the final milestone, the alternative policy was implemented. In main.py, there is an instance variable called "alternate" 
that allows the alternate policy to be run. It is default set to True. The alternate policy changes 
the priority of where C1 is sent in the case of a tie.
## Summary 
The Manufacturing Facility Simulation was conducted in Python.
There are two Python files associated with the simulation. The 
classes.py contains all the classes needed to run the simulation 
(i.e. Inspector, Workstation, Product, Component). The simulation should be run 
on Python 3.7 or above. 

## Installation Instructions
Python needs to be downloaded in order for the simulation to run. 
When downloading Python, it will ask to install "pip"  as well which 
should be installed, so the external libraries can be downloaded.
The simulation relies on the libraries NumPy, SciPy, MatPlotLib SimPy in order to run. 
To install these libraries, you need to have "pip" downloaded when downloading 
Python. </br>

Installation on Ubuntu (Debian) 
```
$ apt-get install pip
$ pip install simpy
$ pip install numpy
$ pip install matplotlib 
$ pip install scipy
```

Once pip is installed, in your terminal/command prompt, you need to 
type *pip install simpy* , *pip install scipy*, *pip install matplotlib* 
*pip install numpy* to install these libraries as shown above. 

## Running The Simulation 
 The simulation can be run by using a Python IDE (i.e. PyCharm) or by typing
 *python main.py* in the terminal/command prompt while in the same folder as 
 main.py. This will run the main script and run the simulation until 3300 minutes for 50 replications. 
 
 Running on Ubuntu (Debian)
 ```
$ cd Manufacturing-Facility-Simulation
$ python main.py
```
 
## Resources 

How to Install Python: https://realpython.com/installing-python/ </br>
How to Install NumPy: https://numpy.org/install/ </br>
How to Install SimPy: https://simpy.readthedocs.io/en/latest/simpy_intro/installation.html </br>
How to Install SciPy: https://www.scipy.org/install.html </br>
How to Install MatPlotLib: https://matplotlib.org/stable/users/installing.html
