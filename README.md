🎯 Number Guessing Game (Python)

A simple yet interactive number-guessing game written in Python.
The program generates a random number between 1 and 100, and the player must guess it in the fewest attempts.
The game also tracks and stores the high score in a hiscore.txt file.

🚀 Features

Random number generation (1–100)

Validates each guess and provides hints:

“Enter a smaller number”

“Enter a larger number”

Counts the number of attempts

Stores & updates a high score

Uses basic file handling (hiscore.txt)

📂 Project Structure
/GuessGame
│
├── main.py
└── hiscore.txt


hiscore.txt should contain an integer.
If you're running for the first time, put a large number like 9999.

▶️ How to Run
1. Clone or download the project
git clone <your-repo-link>
cd GuessGame

2. Make sure Python is installed
python --version

3. Run the game
python main.py

📘 How the Game Works

Program generates a random number.

You guess until you get it right.

Game counts guesses.

If your attempts are fewer than the stored high score:

It updates hiscore.txt.

📝 Example Gameplay
Enter your guess: 50
You guessed it wrong! Enter a smaller number
Enter your guess: 25
You guessed it wrong! Enter a larger number
Enter your guess: 32
You guessed it right!
You guessed the number in 3 guesses
You have just broken the high score!

🛠 Future Improvements (Optional)

If you want to make this project stronger:

Add input validation (handle non-numbers)

Add difficulty levels

Add a replay option

Create a GUI using Tkinter

Convert it to a CLI game with color output
