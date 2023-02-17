# README FILE
This is a word search game that allows you to generate puzzles with random words. The program uses the tkinter module to create a graphical user interface (GUI) that displays the puzzle grid and the list of words to find.

# Requirements
.'Python 3.x'
.'tkinter module'

# Prerequisites
This program requires Python 3 and the following packages:

1. 'tkinter'
2. 'random'
3. 'string'
4. 'os'

# Installation
1. Clone the repository: 'git clone https://github.com/your-username/word-search-puzzle.git'
2. Navigate to the project directory: 'cd word-search-puzzle'
3. Run the program: 'python word_search.py'

# How to Run
1. Open a terminal window.
2. Navigate to the directory where the file word_search.py is saved.
3. Run the command python word_search.py.
4. A new window will open, displaying the puzzle and the list of words to find.

# Usage
1. Run the program using the command above.
2. A new window will open showing the word search puzzle.
3. Find the words in the grid by clicking and dragging with the mouse.
4. Click the "Solve" button to see the solution.
5. Click the "Shuffle" button to rearrange the letters in the grid.
6. Click the "New Word" button to generate a new set of words.
7. Click the "Undo" button to unhighlight the last highlighted word.

# How to Play
1. To select a word, click on the first letter of the word and drag to the last letter of the word.
2. If the word is correct, it will be highlighted in yellow.
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmU2ODZhMzFmMTNjMmM2N2NhMTlhNjM5MmI1MDk2NDMyMGJjZDRmNiZjdD1n/CKkG45QwWmpN2ArRlX/giphy.gif" alt="gif" width="250" height="250">

3. To undo a selection, click the "Undo" button or click on the first letter of the selected word.
<img src="https://media.giphy.com/media/JOpSM4fu6Gjm1HT0sM/giphy.gif" alt="gif" width="250" height="250">

4. To shuffle the puzzle grid, click the "Shuffle" button.
<img src="https://media.giphy.com/media/vZuyCGh3iTSLLMzycz/giphy.gif" alt="gif" width="250" height="250">

5. To solve the puzzle, click the "Solve" button.
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTk0ZWRmZTJhNDRkZWUwMjlmNGZmYzdhZWU4ZWQ0YTZkNGY4ODIzZiZjdD1n/4hjFAMkZvKpkB7MWVB/giphy.gif" alt="gif" width="250" height="250"> 

6. To generate a new puzzle, click the "New Word" button.
<img src="https://media.giphy.com/media/f7ztzi4cjdS1tgTnD5/giphy.gif" alt="gif" width="250" height="250"> 

7. To exit the game, click the "X" button in the top right corner of the window.
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTFmZGY5NTY5OWM3YzAxZGQ3MjE4ZTdmOWVlODQ0MGQ4NWE0NTU3NCZjdD1n/aQpgxBrpTJ8NqpiaEL/giphy.gif" alt="gif" width="250" height="250">

8. Program Files
word_search.py
This is the main program file that generates the word search puzzle, creates the GUI, and handles user input.

# textfile.txt
.This is the file that contains the list of words that can be used in the word search puzzle. The file should contain one word per line.

# Code Structure
Global Variables
1. .puzzle_labels: A list that stores the puzzle labels.
2. .words: A list that stores the words to be used in the puzzle.
3. .root: The main tkinter window.
4. .button_pressed: A boolean variable that indicates whether a button has been pressed.
5. .puzzle_grid: A tkinter frame that contains the puzzle labels.
6. .word_list: A tkinter frame that contains the list of words to find.
7. .button_grid: A tkinter frame that contains the game buttons.

# Functions
1. .'read_words_file(file_path)': Reads a file and returns a list of words.
2. .'newWords(wordFileContent)': Returns a list of random words from the given list of words.
3. .'generate_puzzle(words, rows, columns)': Generates a puzzle grid with the given list of words.
4. .'display_puzzle(puzzle, words)': Displays the puzzle and the list of words to find in the GUI.
5. .'label_click_handler(row, col)': Handles a mouse click on a label in the puzzle grid.
6. .'undo_highlight()': Unhighlights the last highlighted word.

# Customization
To use your own set of words, edit the 'textfile.txt' file and save it in the project directory. Each word should be on a separate line.
