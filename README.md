# Dota-2-Match-Predictor-using-Tensorflow-and-OpenDota-API

This is a script that uses neural network with tensorflow to determine the winning team of a game of Dota 2 from the choices of each player's heroes.

In a game of Dota 2, each player forms a team with 4 other teammates. Each player can choose a hero from a pool of 128 heroes with unique abilities and strengths. 

The goal of the game is to destroy the enemy base by strengthening your heroes by completing side objectives, earning gold from killing minions and enemy heroes. 

This neural network model uses two hidden layers with 128 neurons each (to account for 128 heroes) and a final activation layer with Softmax function for binary classification (radiant team win vs. loss).

