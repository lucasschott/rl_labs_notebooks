
This repository contains labs for understanding and coding basic reinforcement learning concepts based on jupyter notebooks.

The labs are intended for being available to anyone through internet, so the assignments should be self-explanatory.

Most of the work was done by Yasmine Hamdani (https://github.com/Yasmine-H ) during a one month master internship

This is a fork of the repository https://github.com/osigaud/rl_labs_notebooks.git

## Getting Started


### Download 

Get this repository using

```
git clone https://github.com/lucasschott/rl_labs_notebooks.git
```

### Prerequisites

* Conda (See at the bottom of the page https://www.anaconda.com/products/individual to install it)


### Installation

In a shell terminal at the root of the rl_labs_notebooks directory run

```
conda deactivate

conda create --name rl_lab python=3.6 pip

conda activate rl_lab

pip install -r requirements.txt
```

If you don't want to work in the rl_labs for now run 

```
conda deactivate
```

### Running the labs

In a shell terminal run at the root of the rl_labs_notebooks directory run

```
conda activate rl_lab

jupyter lab
```

* copy/paste one of the given url in your web browser

* and follow instructions from lab_instructions.ipynb

When you stop working on the rl_labs

* Termiate the jupyter lab process

* And run

```
conda deactivate

```

### Note

In order to enable the imports between notebooks, we used the [ipynb library](https://github.com/ipython/ipynb). 

The syntax to import a function, say sarsa() from the reinforcement_learning notebook, is as follows:

``` 
from ipynb.fs.defs.reinforcement_learning import sarsa
```


### Code

<br> 

There are 10 *.ipynb files to open on Jupyter Notebook.

* lab_instructions.ipynb : Summary of the lab. It contains the links to the different assignments, from Dynamic Programming to Reinforcement Learning algorithms. This is the file you will refer to when doing these labs.

* mdp.ipynb contains 4 classes :

		- maze : used to describe a maze like environment 
		
		- simple_actspace : used to describe an action space
		
		- mdp : generic class used to define a Markov Decision Process

		- maze_mdp : a class used to define a maze like Markov Decision Process

* maze_plotter.ipynb : used to show the states value functions and policies processed by the algorithms as well as the agent postion in RL algorithms.

* toolbox.ipynb : contains a few constants and functions used in most of the algorithms.
		

* the other notebooks are the different assignments of these labs, look at lab_instructions for more information.


### Contact

To contact me : lucas.schott97@gmail.com

To contact the author of the original repo : Olivier.Sigaud@upmc.fr
