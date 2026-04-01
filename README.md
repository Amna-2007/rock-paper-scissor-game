# rock-paper-scissor-game
This repository contain rock , paper, scissor game
# ✂️ Rock Paper Scissors Game

A fun and interactive **Rock Paper Scissors** game built with **Python**! Challenge the computer and see if you can outsmart it — right from your terminal! 🖥️

---

## 🎮 How to Play

1. Run the game in your terminal
2. Choose your move by entering:
   - `1` for 🪨 Rock
   - `2` for 📄 Paper
   - `3` for ✂️ Scissors
3. The computer randomly picks its move
4. Winner is decided by the classic rules:
   - 🪨 Rock beats ✂️ Scissors
   - ✂️ Scissors beats 📄 Paper
   - 📄 Paper beats 🪨 Rock
   - Same move = **Draw!**
5. Keep playing until you decide to quit!

---

## 🕹️ Features

- 🤖 Play against the computer (random AI)
- 🏆 Live score tracking — Player vs Computer
- 🔄 Play multiple rounds in one session
- 🚪 Quit anytime by pressing `q`
- 💻 Runs directly in the terminal — no browser needed!

---

## 🛠️ Built With

- **Python 3** — Core language
- **`random` module** — For computer's move (built-in, no install needed)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- Check with:
  ```bash
  python --version
  ```

### Run the Game

```bash
# Clone the repository
git clone https://github.com/your-username/rock-paper-scissors.git

# Navigate into the project folder
cd rock-paper-scissors

# Run the game
python game.py
```

---

## 📁 Project Structure

```
rock-paper-scissors/
│
├── game.py       # Main game logic
└── README.md     # Project documentation
```

---

## 🧠 Game Logic (Quick Overview)

```python
import random

choices = ["Rock", "Paper", "Scissors"]

player_choice = choices[int(input("Enter your choice (1/2/3): ")) - 1]
computer_choice = random.choice(choices)

# Winner is decided based on classic rules
```

---

## 📸 Sample Output

```
=== Rock Paper Scissors ===
1. Rock
2. Paper
3. Scissors

Enter your choice: 1
You chose: Rock
Computer chose: Scissors

🎉 You Win!

Score → You: 1 | Computer: 0
Play again? (y/q): 
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create a new branch (`git checkout -b feature/your-feature`)
- Commit your changes (`git commit -m 'Add some feature'`)
- Push to the branch (`git push origin feature/your-feature`)
- Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and share!

---

## 👤 Author

**Amna kabeer**
- GitHub: [Amna-2007](https://github.com/Amna-2007)


---

> *"Simple game. Pure Python. Endless fun!"* 🐍🎉
