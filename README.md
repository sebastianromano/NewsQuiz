# News Quiz
### A simple quiz game for the command line, written in Java

## Installation
1. Download the latest release from the [releases page](link)

2. Unzip the file

3. Open a terminal and navigate to the folder

4. Run the following command:
```
javac NewsQuiz.java
```

5. Run the following command:
```
java NewsQuiz
```

6. Enjoy!

## Usage

### Main Menu
When you first run the program, you will be presented with the *language menu*. Select your language and press enter. 

Henceforth, you will be presented with the *main menu*. From here, you can enter the quiz, view high scores, reset the high scores, change the language or exit the program. 

Please note that the high scores are saved depending on the language you selected. If you change the language, the high scores will be reset. Please note that choosing a different language changes both the news sources and the menus. 

### Quiz
Upon starting the quiz, you will be presented with a series of 10 questions. You can choose from 4 possible answers. If you get the question right, you will be presented with the next question. If you get the question wrong, you will be presented with the correct answer.

After 10 questions, you will be presented with your score. If you have a high score, you will be asked to enter your name. If you do not have a high score, you will be presented with the main menu.

### News Sources
The news sources are currently hard-coded into the program. At this time, it is not possible to add further news sources. If there's a need I will add the functionality at a later date (you can, however, edit the `newsSources` array in the `NewsQuiz` class and try your luck with a different outlet).