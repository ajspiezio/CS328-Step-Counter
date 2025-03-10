[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/HkmFqC0I)
# Assignment1-StepCounting

CS328: Assignment 1 Part 1

Note: This is a GROUP assignment.

## Deadlines:
You have three deadlines for the assignment.

Function 1 - 3 (**due: 11:59 23 February 2025**)

Function 4, 5 (**due: 11:59 02 March 2025**) 

The Github Classroom will stop accepting submissions after only the final deadline. However, we will grade each functions only on what was done prior to its respective deadlines.

No late submissions will be accepted.

## Part 1: Git, Github Classroom etc.

Cloning the repository: Please clone the starter repository to your computer by following the instructions below. DO NOT download the repo as a .zip folder - doing so will create an unattached copy of the repository to your computer and it will be harder for you to commit and push changes.

Click the ```Clone or Download``` button on the top-right corner. Copy the link under ```Clone with HTTPS```.

On your computer, open Terminal or GitBash for Windows (you would have downloaded GitBash while downloading Git for Windows). Navigate to the folder in which you want your assignment folder to be.

Clone the repo by running 
```
git clone <link you copied earlier>
```
This will create a new folder with the assignment files in it.

### Submitting your code

You need to complete the code in the files named `step_counting.ipynb` and commit and push it back to Github for us to be able to grade it.

Make changes to your file and save them. Then, using Terminal or GitBash, navigate to the assignment folder.

To add any changes to a commit, you need to run either
```bash
git add <filename> 
```
to add individual files or
```bash
git add . 
```
to add all files in the current directory.

Then, commit these changes by running:
```
git commit -m “<commit message>”
```

Use a concise commit message that describes the changes you have made since the last commit.

Lastly, push these changes back to Github by running:
```
git push origin master
```

Commit and push your changes periodically. A general good practice is to commit code after each substantial update with a message describing that update. Note that we will only grade your last commit before the deadline.


## Part 2: The Assignment

The assignment contains two Jupyter notebooks. You are required to add your own code in these notebooks wherever mentioned. Make sure you read each notebook carefully so you don’t miss any part of the assignment.

Notebook 1: step_counting
Apply frequency filters and plot signals. Also design and implement  an algorithm to count steps from filtered accelerometer data.

More details are provided in the notebooks at the exact places where your code would go.

During the demo, you must be able to explain the algorithms you use for step counting and the reasoning behind the filter parameters you used.
