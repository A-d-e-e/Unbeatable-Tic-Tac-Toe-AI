# Unbeatable Tic Tac Toe AI

Welcome to **Unbeatable Tic Tac Toe AI** – a classic game reinvented with a twist! This project showcases a GUI-based tic tac toe game where you can challenge an artificial intelligence that leverages the powerful minimax algorithm to guarantee an unbeatable opponent.

## Overview

Tic Tac Toe is more than just a simple game—it's a fun way to learn about decision-making algorithms and game theory. In this project, the AI always makes the optimal move, making it impossible for you to win (or even draw if you’re not careful!). Built with Python's Tkinter library, this project offers a sleek graphical interface, making it accessible and engaging for all skill levels.

## Features

- **Unbeatable AI:** The minimax algorithm ensures that the AI never loses, giving you a true challenge every time.
- **Interactive GUI:** The game uses Tkinter to provide an easy-to-use and visually appealing interface.
- **Simple Game Mechanics:** Just click on the grid to place your move and watch the AI respond instantly.
- **New Game Option:** Restart the game at any time with a simple button click.
- **Readable and Educational Code:** The project is structured to help you understand how the minimax algorithm works in a real-world application.

## Getting Started

### Prerequisites

Make sure you have Python installed on your computer. This project is compatible with Python 3.x versions. Additionally, the Tkinter library is required (it usually comes bundled with standard Python installations).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/A-d-e-e/Unbeatable-Tic-Tac-Toe-AI.git
   cd unbeatable-tic-tac-toe-ai
   ```

2. **Run the Application:**

   Simply execute the main Python file:

   ```bash
   python main.py
   ```

   The game window will appear, and you’re ready to play!

## How It Works

The core of this project is the **minimax algorithm**, a recursive function used to determine the optimal move by simulating all possible game outcomes. Here’s a quick breakdown:

- **Game Board:** Represented as a dictionary to keep track of player moves.
### Screenshot:
| Game Board |
|------------|
| <img src="https://github.com/user-attachments/assets/48a3d148-af1b-4458-b449-16fb5af429dd" alt="Game Board" width="300"> |

- **Turn Management:** The game alternates turns between the human player ('x') and the AI ('o').
- **Winner Check:** After every move, the game checks for a win condition or a draw.
- **Minimax Implementation:** The algorithm explores every possible move (for both maximizing and minimizing players) and assigns scores to board states, ensuring that the AI always picks the best possible move.

## Code Structure

- **GUI Setup:** The Tkinter framework creates buttons and labels to build the interactive board.
- **Game Logic:** Functions like `playGame`, `Winner`, and `GameDraw` manage game progression and outcomes.
- **AI Decision Making:** The `playAI` function integrates the minimax algorithm, while `minimax` handles the recursive decision process.

## Contributing

Contributions are welcome! If you have ideas for enhancements or spot any issues, feel free to open an issue or submit a pull request. Let’s make this project even better together.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Final Thoughts

Whether you’re here to challenge the AI, study a classic algorithm in action, or simply explore Python GUI programming, **Unbeatable Tic Tac Toe AI** is a fun and educational project. Enjoy the game and happy coding!

---

Feel free to adjust the sections or add further details as your project evolves. Happy coding!
