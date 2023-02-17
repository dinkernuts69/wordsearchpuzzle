# README FILE
This is a word search game that allows you to generate puzzles with random words. The program uses the tkinter module to create a graphical user interface (GUI) that displays the puzzle grid and the list of words to find.

# Requirements
.'Python 3.x'
.'tkinter module'

# Prerequisites
This program requires Python 3 and the following packages:

'tkinter'
'random'
'string'

# Installation
Clone the repository: 'git clone https://github.com/your-username/word-search-puzzle.git'
Navigate to the project directory: 'cd word-search-puzzle'
Run the program: 'python word_search.py'

# How to Run
Open a terminal window.
Navigate to the directory where the file word_search.py is saved.
Run the command python word_search.py.
A new window will open, displaying the puzzle and the list of words to find.

# Usage
Run the program using the command above.
A new window will open showing the word search puzzle.
Find the words in the grid by clicking and dragging with the mouse.
Click the "Solve" button to see the solution.
Click the "Shuffle" button to rearrange the letters in the grid.
Click the "New Word" button to generate a new set of words.
Click the "Undo" button to unhighlight the last highlighted word.

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


8. Program Files
word_search.py
This is the main program file that generates the word search puzzle, creates the GUI, and handles user input.

# textfile.txt
.This is the file that contains the list of words that can be used in the word search puzzle. The file should contain one word per line.

# Code Structure
Global Variables
.puzzle_labels: A list that stores the puzzle labels.
.words: A list that stores the words to be used in the puzzle.
.root: The main tkinter window.
.button_pressed: A boolean variable that indicates whether a button has been pressed.
.puzzle_grid: A tkinter frame that contains the puzzle labels.
.word_list: A tkinter frame that contains the list of words to find.
.button_grid: A tkinter frame that contains the game buttons.

# Functions
.'read_words_file(file_path)': Reads a file and returns a list of words.
.'newWords(wordFileContent)': Returns a list of random words from the given list of words.
.'generate_puzzle(words, rows, columns)': Generates a puzzle grid with the given list of words.
.'display_puzzle(puzzle, words)': Displays the puzzle and the list of words to find in the GUI.
.'label_click_handler(row, col)': Handles a mouse click on a label in the puzzle grid.
.'undo_highlight()': Unhighlights the last highlighted word.

# Customization
To use your own set of words, edit the 'textfile.txt' file and save it in the project directory. Each word should be on a separate line.
