
# WordPy
## Description
    1)Similar to the game 'Wordle'.
    2)The game engine generates a hidden 5 letter word called the target word.
    3)The bot attempts to guess that word. It will get up to six tries.
    4)The bot will be given the location of a datafile which has a list of allowable words (one per line). The bot will read in this datafile and only make guesses from this datafile.
    5)After each guess the system provides feedback indicating if each character is in the correct position for the target word, and if not, if the character is in the target word but in the wrong position.
    6)The bot will try to be "smart" in that once it has identified the correct location of a letter in a word, it will only guess future words where that letter is in the same position.
    




## Installation
Required modules: Python Imaging Library (PIL) and random

```bash
    pip install PIL
```
    
## Tech Stack

Python

