# Interacting-Cells

<img src="https://img.shields.io/liberapay/gives/techmatt01.svg?logo=liberapay">

## Target
This project aims to create a Jupyter interactive file to do simulations and in general, modelling and science about a simple biological model.
Simulations have always fascinated me for their ability to predict real phenomena and modelling is an essential part of it.
But the fundamental goal of this project is to share opinions, hints and knowledge about the particular realm of research that I'm trying to bring here: simulation of living-like entities:
what they do? How they interact? How the population change according to their behaviour? And many other questions.

## The model
The model that I'm trying to implement is largely explained in the Jupyter notebook file but I will shortly explain it here.

The model consists of a variable number of cells (the user can change the value) that have an energy level. The code is structured so every time step the cells lose a few energy (cause they are mantaining their system and doing some activities, so they are using energy). Also they wander around searching for food, so there is a chance to find something; this will allow them to earn extra energy. When a cell ends its energy, it dies. The cells can also decide to attack another cell. The winner will earn a portion of the other cell energy. Cells can also cooperate, so the chanche of finding food will rise (and maybe also the chanche of winning fights, but this will be implemented later on). There are also other aspects that are discussed on the jupyter file.

## Installation and Dependencies
Jupyter notebook is an interactive enviroment where you can code Python (and other programming languages) in a very unique way. You can alternate text and code and still be capable of running the whole program. So to run this project you need jupyter and a Python enviroment to code in it.

So the first step is installing Anaconda. This is a packet with Python and some major libraries for Data Science and simulations. You can follow these guides:

- If you have Linux: download Anaconda [here](https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh "here") and follow instructions.

- If you have Windows: download Anaconda [here](https://repo.anaconda.com/archive/Anaconda3-2020.07-Windows-x86_64.exe "here") and follow instructions.

- If you have OSX: download Anaconda [here](https://repo.anaconda.com/archive/Anaconda3-2020.07-MacOSX-x86_64.pkg "here") and follow instructions.

Okay so now we have a Conda Enviroment where we can test our script and Jupyter file. But wait, we need Jupyter!

Open up your terminal or command prompt and write:
`conda install -c conda-forge jupyterlab`

And we are done. We have now set up the enviroment where we can view and edit the project.


## Running the project

 Okay, so download the GitHub repo either using the *Code* button in the upper-right, and then *Download zip* or type the following command in the terminal / command prompt (make sure you have Git installed):

 `git clone https://github.com/Tech-Matt/interacting-cells.git`

 At the end of this process you should have a directory with all the files in the repository.
 Open up now a terminal / command prompt into the folder and then type:

 `jupyter notebook`

 Hopefully a window will open up with some files in it.Double click on *cell_simulation.ipynb* and the project should open.
