🪨📄✂️ Rock, Paper, Scissors — AI Opponent
A desktop Rock, Paper, Scissors game built with Python and Tkinter, featuring a simple predictive AI that learns from your last move.
📸 Preview
A clean GUI with buttons for each move, showing your choice, the computer's choice, and the result after each round.
🚀 Features

Graphical UI built with Python's built-in tkinter library — no extra installs needed
Predictive AI that counters your previous move instead of playing randomly every round
Instant win/lose/tie feedback after each round

🧠 How the AI Works
The AI uses a simple pattern-exploitation strategy:

First round: picks randomly
Subsequent rounds: assumes you'll repeat your last move and picks the counter to it

Your Last MoveAI's Next MoveRockPaperPaperScissorsScissorsRock
This makes the AI beatable with a little strategy — try varying your moves!
🛠️ Requirements

Python 3.x
tkinter (included in the Python standard library)


On some Linux distros, you may need to install tkinter separately:
bashsudo apt-get install python3-tk

▶️ How to Run
bashgit clone https://github.com/your-username/rock-paper-scissors-ai.git
cd rock-paper-scissors-ai
python rps_game.py
No virtual environment or pip install needed.
📁 Project Structure
rock-paper-scissors-ai/
│
└── rps_game.py    # Main game file (UI + AI logic)
🔮 Possible Improvements

Score tracker across multiple rounds
More advanced AI (e.g., frequency analysis or Markov chains)
Difficulty levels
Sound effects or animations

📄 License
MIT License — free to use, modify, and distribute.
