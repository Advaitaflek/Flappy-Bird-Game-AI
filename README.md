Flappy Bird NEAT AI Project

This project implements a Flappy Bird game using Python, Pygame, and NEAT (NeuroEvolution of Augmenting Topologies) AI. The AI learns how to play the game by evolving through multiple generations, gradually improving its performance.

Demo

![image](https://github.com/user-attachments/assets/473d0836-2512-49ce-9fae-efb51f832f37)

Features

Pygame: The game engine used to build the Flappy Bird game.

NEAT: AI that learns to play the game using evolutionary algorithms.

Dynamic Pipes: Randomly generated pipe heights to challenge the bird.

Fitness Evaluation: AI performance measured based on survival and progress.


Setup

Prerequisites

Python 3.6+

Pygame

NEAT-Python


How It Works

The AI uses NEAT, which evolves a neural network to control the bird. The bird learns to avoid pipes through trial and error, gradually improving over generations.


Key components include:

Bird Class: Handles bird movement and drawing.

Pipe Class: Manages pipe movement and collision.

NEAT Integration: Connects the neural network to control the bird’s actions.
