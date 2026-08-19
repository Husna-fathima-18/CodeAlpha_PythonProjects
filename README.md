# CodeAlpha Python Programming Projects

## 📌 Overview

This repository contains three Python programming projects completed as part of the **CodeAlpha Python Programming Internship**.

The projects demonstrate fundamental Python programming concepts including:

* Variables and data types
* Lists and dictionaries
* Strings
* Conditional statements
* Loops
* User input and output
* Random selection
* File handling
* Directory handling
* Python automation

The three completed tasks are:

1. **Task 1 – Hangman Game**
2. **Task 2 – Stock Portfolio Tracker**
3. **Task 3 – Task Automation with Python**

---

# 🎮 Task 1 – Hangman Game

## 📖 Description

The Hangman Game is a simple text-based Python game where the player attempts to guess a randomly selected word one letter at a time.

The game uses **5 predefined words** and allows the player a maximum of **6 incorrect guesses**.

This follows the CodeAlpha Task 1 requirements.

## ✨ Features

* Randomly selects a word.
* Uses 5 predefined words.
* Displays the hidden word using underscores.
* Allows the player to guess one letter at a time.
* Tracks previously guessed letters.
* Allows a maximum of 6 incorrect guesses.
* Validates user input.
* Displays the final result.
* Shows the correct word when the player loses.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* `random` library

## 🧠 Concepts Used

* Lists
* Strings
* `random.choice()`
* `while` loop
* `for` loop
* `if-else`
* User input

## ▶️ How to Run

Using Jupyter Notebook:

1. Open `CodeAlpha_Task1_Hangman.ipynb`.
2. Run the Python cells.
3. Enter one letter at a time when prompted.
4. Continue until you guess the word or use all 6 incorrect guesses.

Using Python:

```bash
python hangman.py
```

## 📂 Files

```text
Task1_Hangman/
├── CodeAlpha_Task1_Hangman.ipynb
└── hangman.py
```

---

# 📈 Task 2 – Stock Portfolio Tracker

## 📖 Description

The Stock Portfolio Tracker is a Python program that allows users to enter stock names and quantities and calculates the total investment based on predefined stock prices.

The project uses a hardcoded dictionary for stock prices and also saves the portfolio report to a text file.

This follows the CodeAlpha Task 2 requirements.

## ✨ Features

* Displays available stocks and their prices.
* Accepts stock symbols from the user.
* Accepts the number of shares.
* Calculates the value of each stock.
* Calculates total investment.
* Handles invalid stock names.
* Handles invalid quantities.
* Prevents zero or negative quantities.
* Saves the portfolio report as `portfolio.txt`.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* File handling

## 🧠 Concepts Used

* Dictionaries
* User input
* Arithmetic operations
* Loops
* Conditional statements
* Exception handling
* File handling

## 📊 Example Calculation

```text
AAPL = 10 shares × $180 = $1800

TSLA = 5 shares × $250 = $1250

Total Investment = $3050
```

## ▶️ How to Run

Using Jupyter Notebook:

1. Open `CodeAlpha_Task2_StockPortfolio.ipynb`.
2. Run the cells.
3. Enter stock symbols and quantities.
4. Enter `done` when finished.
5. The program calculates the total investment.
6. A `portfolio.txt` report is generated.

Using Python:

```bash
python stock_portfolio.py
```

## 📂 Files

```text
Task2_StockPortfolio/
├── CodeAlpha_Task2_StockPortfolio.ipynb
├── stock_portfolio.py
└── portfolio.txt
```

---

# 📁 Task 3 – Automated JPG File Organizer

## 📖 Description

The Automated JPG File Organizer is a Python automation script that automatically identifies `.jpg` and `.jpeg` files in a source folder and moves them to a separate destination folder.

This project is based on one of the automation options provided in CodeAlpha Task 3.

## ✨ Features

* Automatically checks the source folder.
* Identifies JPG and JPEG files.
* Creates the destination folder if necessary.
* Moves image files automatically.
* Leaves other file types unchanged.
* Displays the number of files moved.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* `os`
* `shutil`

## 🧠 Concepts Used

* File handling
* Directory handling
* `os` module
* `shutil` module
* Loops
* Conditional statements
* Automation

## 📂 Folder Structure

```text
Task3_FileAutomation/
│
├── CodeAlpha_Task3_FileAutomation.ipynb
├── file_organizer.py
│
├── source_folder/
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── document.pdf
│
└── jpg_files/
```

After running the program:

```text
Task3_FileAutomation/
│
├── CodeAlpha_Task3_FileAutomation.ipynb
├── file_organizer.py
│
├── source_folder/
│   └── document.pdf
│
└── jpg_files/
    ├── photo1.jpg
    └── photo2.jpg
```

## ▶️ How to Run

Using Jupyter Notebook:

1. Open `CodeAlpha_Task3_FileAutomation.ipynb`.
2. Make sure the `source_folder` exists.
3. Place JPG/JPEG files inside `source_folder`.
4. Run the Python code.
5. The JPG/JPEG files will automatically be moved to `jpg_files`.

Using Python:

```bash
python file_organizer.py
```

---

# 🧰 Tools and Technologies

| Tool / Technology | Purpose                       |
| ----------------- | ----------------------------- |
| Python            | Programming language          |
| Jupyter Notebook  | Development and testing       |
| Git               | Version control               |
| GitHub            | Source code repository        |
| `random`          | Random word selection         |
| `os`              | File and directory operations |
| `shutil`          | Moving files                  |
| Text files        | Saving portfolio results      |

No external Python packages are required for these basic implementations.

---

# 📋 Internship Tasks Completed

| Task   | Project                 | Status      |
| ------ | ----------------------- | ----------- |
| Task 1 | Hangman Game            | ✅ Completed |
| Task 2 | Stock Portfolio Tracker | ✅ Completed |
| Task 3 | JPG File Automation     | ✅ Completed |

CodeAlpha requires completion of a minimum of **two or three tasks** for internship completion.

---

# 🎯 Learning Outcomes

Through these projects, I gained practical experience in:

* Python programming fundamentals
* Problem solving
* Working with lists and dictionaries
* Loops and conditional logic
* Handling user input
* File and directory management
* Python automation
* Creating reusable Python scripts
* Testing Python programs using Jupyter Notebook
* Managing projects using GitHub

---

# 🚀 Future Improvements

Possible future improvements include:

### Hangman Game

* Add difficulty levels.
* Add categories.
* Add a scoring system.
* Add ASCII-art Hangman graphics.
* Add a larger word database.

### Stock Portfolio Tracker

* Add more stocks.
* Add live stock prices.
* Add graphical portfolio analysis.
* Add CSV export.
* Add profit/loss calculation.

### File Automation

* Support additional file types.
* Organize files by extension.
* Add duplicate-file detection.
* Add automatic date-based folders.
* Create a graphical user interface.

---

# 👨‍💻 Author

**PATHAN HUSNA FATHIMA**

B.Tech – Computer Science and Engineering (ECE)

## 📌 Internship

**CodeAlpha Python Programming Internship**

---

## ⭐ Repository Structure

```text
CodeAlpha_PythonProjects/
│
├── README.md
│
├── Task1_Hangman/
│   ├── CodeAlpha_Task1_Hangman.ipynb
│   └── hangman.py
│
├── Task2_StockPortfolio/
│   ├── CodeAlpha_Task2_StockPortfolio.ipynb
│   ├── stock_portfolio.py
│   └── portfolio.txt
│
└── Task3_FileAutomation/
    ├── CodeAlpha_Task3_FileAutomation.ipynb
    ├── file_organizer.py
    ├── source_folder/
    └── jpg_files/
```

---

## 📜 Acknowledgement

This project was completed as part of the **CodeAlpha Python Programming Internship**. The tasks are based on the internship task requirements provided by CodeAlpha.
