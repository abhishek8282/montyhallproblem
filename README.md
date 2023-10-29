# Monty Hall Simulation

## Overview

This Python script creates a graphical user interface (GUI) application to simulate the famous Monty Hall problem. The Monty Hall problem is a probability puzzle based on a game show scenario. The user can input the number of simulation trials to see the results of both sticking with the initial choice and switching choices.

## Prerequisites

To run this script, you need to have Python installed on your system. Additionally, you need the `tkinter` library, which is included in most standard Python installations.

## Usage

1. **Download**: Download the script (`monty_hall_simulation.py`).

2. **Run the Script**: Open a terminal or command prompt.

3. **Navigate**: Navigate to the directory where the script is located.

4. **Execute**: Run the script using the following command:

   ```bash
   python monty_hall_simulation.py


## How It Works
The script simulates the Monty Hall problem as follows:
Three doors are initially presented, one with a "gold" prize and the others with "goat" and "bed."
The user makes an initial choice.
A door with a "goat" behind it is revealed (not the user's initial choice).
The user is given the option to either stick with their initial choice or switch to the other unopened door.
The script counts the number of times the user would win if they stick with their initial choice and if they switch.

## Logic
The script uses a random selection of doors and simulates the user's choices. It keeps track of how many times the user would win by sticking with their initial choice and how many times they would win by switching.

## Disclaimer
The script uses randomization to simulate the Monty Hall problem. It may not provide precise results with a small number of trials. To get accurate probabilities, you should run a large number of trials.  