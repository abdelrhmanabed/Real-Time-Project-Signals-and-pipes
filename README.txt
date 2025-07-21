Real-Time Bungee-Jumping Game Simulation

This project is a real-time bungee-jumping game simulation implemented in C, featuring OpenGL for visual rendering. The game simulates multiple teams, each with players competing in a bungee jump, with energy levels and scores updated dynamically. It employs multi-processing with signals and pipes for communication between processes.

Files:

main.c: The main logic for the game simulation, containing functions for game management, process control, and communication.
opengl.c: Handles the rendering of players, teams, and game events using OpenGL for dynamic visual representation.
header.h: Contains necessary includes, data structures (for players and teams), and function prototypes.
opengl.h: Header file for OpenGL functionalities.
load_config.txt: Configuration file containing game parameters, such as game duration and maximum score.
makefile: Automates the build process for compiling the program.
run.sh: Shell script to run the compiled game, loading configuration from load_config.txt.
