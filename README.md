# Guess-The-State
This  Game is a Python program that lets you interactively guess the names of U.S. states on a map. This educational game is built using the Turtle graphics library and utilizes state data from a CSV file.

## Output


https://github.com/sarvesh-2109/Guess-The-State/assets/113255836/b0669e67-699e-4234-a9e7-bb05ee1c87dc



## How to Play

1. When you run the program, a map of the U.S. states will be displayed.
2. You can click on any state on the map to see its coordinates (latitude and longitude), but this feature is currently commented out in the code.
3. To start guessing states, a dialog box will prompt you for a state's name.
4. Type the name of a U.S. state and press Enter.
5. If you guessed correctly, the program will display the state's name on the map, and you'll see the count of correct guesses.
6. Keep guessing until you've correctly identified all 50 U.S. states.
7. To exit the game at any time, simply type "Exit" when prompted for a state's name.
8. Once you exit, the program will generate a CSV file named "States_to_learn.csv" containing the names of states you haven't guessed yet.

## Prerequisites

- Python 3.x
- pandas library (for reading state data from the "50_states.csv" file)

## How to Run

1. Clone this repository to your local machine.
2. Make sure you have Python and pandas installed.
3. Run the script using `python us_states_game.py`.

## Data Source

The program uses state data from the "50_states.csv" file, which includes information about the U.S. states' names, abbreviations, and coordinates (x and y) on the map.

## Contributions

Feel free to contribute to or modify this project as needed. Happy learning and gaming!
