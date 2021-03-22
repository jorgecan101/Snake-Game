# Snake-Game

This is our final project

Created by:
Hyun Guk Yoo
Jorge Cancino
Shivam Sharma 
Marin Budic

imports
	pygame	(need to be installed)
	yaml	(might need to be installed)
	random
	itertools
	dataclasses
	mathplotlib
	numpy

Using Reinforcement Learning with Snake

The code is seperated into three different python files. 
1)qInitializeVal.py , 2)Learner.py and 3)snake.py

*run it in that order*

This is because qInitializeVal.py creates a yaml file that 
is used for the program


snake.py is the main code that runs the program, and it calls
Learner.py to implement the q-learner algorithm. 

Running the code should open up a small window that plays the 
snake game automatically. It shows the current game's score,
and the highest score out of all the games. 

The algorithm will train for 20 games untill it implements 
q-learning(this can be changed in the code)

It will run forever untill terminated
(by pressing the esc key at the start of a new round).
