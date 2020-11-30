# tasks2020
My GMIT Fundamentals of Data Analysis tasks

## Introduction
This repository contains four tasks in a single jupyter notebook given in the Fundementals of Data Analysis module in Gmit HDip data analytics. 

### [Jupyter Notebook](https://jupyter.org/)
-is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. It is best installed with [Anaconda](https://www.anaconda.com/). 
Anaconda simplifies package management and deployment by having the most popular python packages installed on your machine even before you know you will be using them. 
Jupyter can also be installed separately from its website.

### Launching Jupyter Notebook App
The Jupyter Notebook App can be launched by clicking on the Jupyter Notebook icon installed by Anaconda in the start menu or by typing 'Jupyter Notebook' in a terminal.
### How do run/save this jupyter notebook
- First click on Raw.
- Then, press ctrl+s to save it as tasks2020.ipynb (files from GitHub are saved as text files as default, so you'll have to manually type '. ipynb' after the file name to make this work.)
- Open CMDER and type in Jupyter Notebook
- Jupyter notebook should appear in your browser 
- Go to the file location where you saved the tasks2020.ipynb
- Open file.
-[Jupyter beginners Guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

## Task 1 : October 5th, 2020:
~~~ 
"Write a Python function called counts that takes a list as
input and returns a dictionary of unique items in the list as keys and the number of
times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A']
should have output {'A': 3, 'B': 1, 'C': 1} . Your code should not depend
on any module from the standard library or otherwise. You should research the task
first and include a description with references of your algorithm in the notebook."
- Tasks 2020 by Ian McLoughlin
~~~
## Task 2: November 2nd, 2020:
~~~
Write a Python function called dicerolls that simulates
rolling dice. Your function should take two parameters: the number of dice k and
the number of times to roll the dice n. The function should simulate randomly
rolling k dice n times, keeping track of each total face value. It should then return
a dictionary with the number of times each possible total face value occurred. So,
calling the function as diceroll(k=2, n=1000) should return a dictionary like:
{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}
- Tasks 2020 by Ian McLoughlin
~~~
 ## Task 3. November 16th, 2020: 
 ~~~
"The numpy.random.binomial function can be used to
simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a
coin is flipped many times then the number of heads is well approximated by a
bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of
getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively
low, and the chances of getting any other number of heads decreases as you move
away from 50 in either direction towards 0 or 100. Write some python code that
simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track
of the number of heads in each of the 1,000 simulations. Select an appropriate
plot to depict the resulting list of 1,000 numbers, showing that it roughly follows
a bell-shaped curve. You should explain your work in a Markdown cell above the
code."
- Tasks 2020 by Ian McLoughlin
~~~

## Task 4.  November 30th, 2020:
~~~
"Simpson’s paradox is a well-known statistical paradox
where a trend evident in a number of groups reverses when the groups are combined
into one big data set. Use numpy to create four data sets, each with an x array
and a corresponding y array, to demonstrate Simpson’s paradox. You might
create your x arrays using numpy.linspace and create the y array for each
x using notation like y = a * x + b where you choose the a and b for each
x , y pair to demonstrate the paradox. You might see the Wikipedia page for
Simpson’s paradox for inspiration."
- Tasks 2020 by Ian McLoughlin
~~~

Tasks are answered in the jupyter notebook below; 
### Tasks 2020: [tasks2020.ipynb](https://github.com/AineNicD/tasks2020/blob/main/tasks2020.ipynb)



### References

* Ian McLoughlin course material 

* [Python library](https://docs.python.org/3/library/functions.html)

* [Python community](https://www.python.org/community/).

* [Jupyter Notebook](https://jupyter.org/)


