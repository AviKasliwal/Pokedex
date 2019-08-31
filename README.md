# Pokedex
#### PokeDex - a Pokemon Detector Device which classifies  Pokemons using SVM

## Problem Statement : 
You are going on a trip to Dudhsagar Falls, Goa. To reach the falls you have to cross a huge forest in Collem, so you thought of entering the forest. While you are on your route you spotted multiple Pokemons like Bulbasaur, Pikachu, and Charmender. After coming back, you thought of making a PokeDex - a Pokemon Detector Device which classifies these Pokemons. Write an algorithm that classifies these PokeMon's.

## About the dataset :
There are two folders Test and Train.

**Train :** The train folder consists of a folder named Images which contains the images of three types of pokemon and a csv file which maps the images in the image folder to the name of that pokemon, The csv contains the field ImageId which is nothing but unique name given to each image and other field is NameOfPokemon which gives the pokemon name associated with that image.

**Test :** Test also contains an image folder on which your model will be tested on and also there is a test csv file which only contains the name or ImageId of the image and gives the order in which each image is to be labelled .

**Submission :** This file will be a csv file that will be submitted by you it will contain the same fields as that of sample submission the order of the ImageId should match that of sample submission or test csv.

**The three categories of Pokemon to be classified are Pikachu,Bulbasaur and Charmander.**


## Result :
Using GridSearchCV best hyperparameters for SVM were found and a score of <mark>**96%**</mark> was received on classifying test images.
