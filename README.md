🃏 Blackjack Game — Python Console Edition

Welcome to Blackjack, a simple yet fully functional command-line game written in Python!
This project is part of your Python learning journey and demonstrates conditionals, loops, functions, and game logic.

📌 Features

🎴 Deal cards to the user and computer

🧠 Smart score calculation (handles Ace as 11 or 1)

🃙 Automatic dealer logic (hits until 17+)

🏆 Detects Blackjack, busts, draws

🔁 Play multiple rounds

🎨 Includes optional ASCII art logo

🧱 Beginner-friendly, clean structure

🧩 How the Game Works

Both user and computer start with two cards

User can choose to Hit (y) or Stand (n)

Dealer automatically draws cards until score ≥ 17

Game ends when:

Someone hits Blackjack (21 with 2 cards)

Someone busts (> 21)

Both players stand

Winner is decided using custom comparison logic.

🛠️ Technologies Used

Python 3

random library

Command-line interface

📂 Project Structure
📦 blackjack-game
 ┣ 📜 main.py
 ┣ 📜 logo.py   (optional ASCII art)
 ┗ 📜 README.md

🚀 How to Run

Make sure you have Python 3 installed.

Clone the repository:

git clone https://github.com/your-username/blackjack-game.git
cd blackjack-game


Run the game:

python main.py

🎨 ASCII Logo (Optional)

If you're using a separate logo.py, include this:

logo = r"""
 ____  _            _            _            _    
| __ )| | __ _  ___| | __   __ _| | __ _  ___| | __
|  _ \| |/ _` |/ __| |/ /  / _` | |/ _` |/ __| |/ /
| |_) | | (_| | (__|   <  | (_| | | (_| | (__|   < 
|____/|_|\__,_|\___|_|\_\  \__,_|_|\__,_|\___|_|\_|
"""

📖 Learning Purpose

This project helped practice:

Writing reusable functions

Understanding return values

Handling lists

Implementing game loops

Using while loops + conditionals

Basic game mechanics

Perfect for anyone following Angela Yu’s Python Bootcamp or learning Python fundamentals.

🤝 Contribution

Want to improve the game?
Feel free to submit a PR or open an issue! Suggestions like betting systems, card graphics, or OOP versions are welcome ✨

⭐ If you like this project

Give the repo a star ⭐ on GitHub — it motivates more cool projects!