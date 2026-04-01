[Back to Portfolio](./)

Project 1 Hang man 
===============

-   **Class:CSCI-235 Procedural Programming** 
-   **Grade:98/100** 
-   **Language(s):C++** 
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:ppotisom@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project Description

This project is a console-based implementation of the classic Hangman game, developed in C++. The program allows a user to guess letters in order to uncover a hidden phrase. The game dynamically updates the display after each guess and visually represents incorrect attempts using an ASCII-based gallows.

The system reads phrases from an external file and organizes them based on difficulty. Difficulty is determined by the number of unique letters in each phrase, allowing the game to scale from easy to hard levels. The program uses a structured approach with modular functions to handle tasks such as phrase loading, sorting, game logic, and user interaction.

## How to compile and run the program

How to compile (if applicable) and run the project.

### Using Visual Studio (Windows)
```bash
cl Hangman.cpp
.\Hangman.exe
```

If the programming language does not require compilation, the update the heading to be “How to run the program.” If your application is deployed on a remote service, including instructions on how to deploy it.

## UI Design

This is a command-line interface (CLI) application that interacts with the user through text prompts.

User Tasks:
Select a difficulty level (Easy, Medium, Hard)
Input letter guesses one at a time
View progress of the phrase as letters are revealed
Track incorrect guesses
Choose whether to replay the game
System Behavior:
Displays the phrase as underscores for unguessed letters
Reveals correctly guessed letters in their correct positions
Tracks incorrect guesses and updates the hangman drawing
Ends the game when:
The player guesses the full phrase (win)
The maximum number of incorrect guesses is reached (loss)

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
