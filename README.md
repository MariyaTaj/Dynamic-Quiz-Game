# Python Projects
**Dynamic Quiz Game**

This repository contains a concise Jupyter Notebook (`Dynamic Quiz Game.ipynb`) for a dynamic quiz game written in Python. Users are prompted to play the game and, upon agreement, they answer a series of questions. Their responses are evaluated against predefined answers, and a final score is provided at the end.

### Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/dynamic-quiz-game.git
```
2. Open the Jupyter Notebook `Dynamic Quiz Game.ipynb`.
3. Run each cell in the notebook to play the game.
4. Answer each question and see your final score.

**Password Manager**
This Python script serves as a basic password manager. It allows users to store and retrieve passwords securely using the Fernet encryption algorithm.

### Features
Encryption: Passwords are encrypted using the Fernet symmetric encryption algorithm, ensuring security.
Master Password: Users are required to enter a master password to access stored passwords, adding an additional layer of security.
Add and View Passwords: Users can add new passwords or view existing ones.
Persistent Storage: Passwords are stored in a file (passwords.txt) and encrypted, allowing for persistence between sessions.

### How to Use
1. Set Up: Before running the script, ensure you have the cryptography library installed (pip install cryptography).
2. Master Password: When prompted, enter your master password. This will be used along with the key to encrypt and decrypt passwords.
3. Options:
   view: View existing passwords stored in passwords.txt.
   add: Add a new password to the manager.
   q: Quit the program.

### Requirements

- Jupyter Notebook
- Python 3.x
