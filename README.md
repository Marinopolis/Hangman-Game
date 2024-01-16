# Hangman Game

A Java-based Hangman game with a graphical user interface implemented using Swing.

## Description

Hangman Game is a classic word-guessing game where players try to guess a hidden word by suggesting letters. The game features a visually appealing interface, custom fonts, and utility methods provided by the `CustomTools` class for handling images, fonts, and word hiding.

## Features

- **Image Handling:** The game uses the `CustomTools` class to load and update images for visual elements.
- **Font Customization:** Custom fonts are applied to enhance the visual experience.
- **Word Database:** The `WordDB` class manages a collection of words categorized by different themes.

## Word Database

The `WordDB` class is responsible for loading word challenges from a data file. It provides functionality to randomly select a category and a word from that category for each game round.

### Data File Format

The data file (`resources/data.txt`) used by `WordDB` follows a CSV format, where each line represents a category followed by a list of words. For example:

```plaintext
Animals,elephant,lion,tiger
Countries,canada,india,usa
Animes,OnePeach,Naruto
```
## How To Play
To play the Hangman Game:

   1. Launch the game by running the App class.
   2. A new game will start with a random word challenge.
   3. Click on letter buttons to guess the word.
   4. Guess the word before running out of attempts.

## Screenshots
![image](https://github.com/Marinopolis/Hangman-Game/assets/133904605/7edd9f72-8c5f-46c6-a972-6ea57aa0eeca)

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or create a pull request.

