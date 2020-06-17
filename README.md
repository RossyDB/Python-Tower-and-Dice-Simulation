# Python-Tower-and-Dice-Simulation
## A short script used to simulate a random walk simulator for a python dice game

### The simulation.py file is used to model a dice game with the following restrictions:

  1) Starting at step 50 of a tower a dice is rolled (random seed is 123)
  2) If a 1 or a 2 is rolled the player must move one step down tower
  3) If a 3, 4 or 5 is rolled the player must take a step up the tower
  4) If a 6 is rolled the dice the player must take the amount of steps of a new roll up the tower
  5) The player wins if he reaches step 60 of the tower and loses if step 0 is reached

### The chance of winning the game, the average final step placed and a plot of the distribution was calculated.

### Distribution:
![Alt text](./output/Figure_1.png?raw=true "Distribution of walks")

### Console output for seed 123:
![Alt text](./output/output.PNG?raw=true "Console output")


