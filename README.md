1. Introduction 
The Mini Game Collection is a suite of five Python-based mini
games that showcase various game mechanics and programming 
techniques. Each game is designed to be simple yet engaging, 
providing a unique challenge for the player. The collection includes 
a Quiz Game, Hangman, Tic-Tac-Toe with AI, Number Guessing 
Game, and Word Scramble. Leaderboards track high scores across 
games, encouraging players to aim for higher achievements. The 
goal of the project was to collaborate effectively as a team, applying 
core programming skills to create modular, maintainable, and user
friendly mini games. 
2. Game Overview and Core Mechanics 
• Quiz Game: A multiple-choice quiz where the player answers 
randomly selected questions. The player has 3 lives and loses 
a life for every incorrect answer. Scores are saved when all 
lives are lost. 
• Hangman: A word-guessing game where the player guesses 
letters to form a word. Incorrect guesses are visualized using 
ASCII art. Players can retry after losing. Scores are saved when 
all lives are lost. 
• Tic-Tac-Toe (with AI): A classic grid-based game where the 
player can choose to compete against AI opponent that makes 
random moves. The game detects win conditions, ties, and 
allows retries. 
• Number Guessing Game: The computer selects a number, 
and the player has 3 attempts to guess it, with hints provided 
(higher or lower). The player can retry after losing. 
• Word Scramble: The player is presented with a scrambled 
word and must guess the correct version within 3 tries. A retry 
option is available after each game. 
3. Code Flow: 
• Quiz Game: 
1. Load questions from a file. 
2. Randomly select a question and present multiple-choice 
options. 
3. If the player answers correctly, they earn points; otherwise, 
they lose a life. 
4. The game ends when all lives are lost, and the score is 
saved to the leaderboard. 
5. Offer a retry option. 
• Hangman: 
1. Select a random word from a list. 
2. Display underscores for each letter and allow the player to 
guess letters. 
3. If a guess is incorrect, update the ASCII art. 
4. The game ends when the word is guessed, or the figure is 
fully drawn. 
5. Offer a retry option. 
• Tic-Tac-Toe (with AI): 
1. Allow the player to play human vs. AI. 
2. Display the Tic-Tac-Toe grid and alternate turns. 
3. The AI randomly selects a move. 
4. Detect wins, losses, or ties. 
5. Offer a retry option. 
• Number Guessing Game: 
1. The computer selects a random number within a range. 
2. The player guesses the number, and hints (higher/lower) 
are provided. 
3. The game ends after 3 incorrect guesses or a correct guess. 
4. Offer a retry option. 
• Word Scramble: 
1. Select a random word and scramble it. 
2. The player guesses the unscrambled word. 
3. The game ends after 3 incorrect attempts or a correct 
guess. 
4. Offer a retry option. 
4.Task Division 
1. Youssef El gazar: Implemented the Quiz Game, focusing on 
input handling and score tracking. 
2. Ahmed El khereby: Developed the main for calling all the 
games and developed Tic-Tac-Toe game with AI, including AI 
logic and win/tie detection. 
3. Mohamed Hisham: Worked on the Number Guessing Game 
and Word Scramble. Built the leaderboard system managing 
file handling for high scores and contributed to game-wide 
features like retry options. 
4. Ahmed Emad: Worked on the Hangman Game. focusing on 
input handling and score tracking managing file handling for 
reading files according to game difficulty. 
5. Lessons Learned 
• Teamwork: Effective communication and task division were 
essential for our success. 
• Technical Skills: gained valuable experience in Python, game 
development techniques, and version control systems. 
• Problem-Solving: Enhanced our ability to troubleshoot and 
resolve technical challenges effectively. 
• Project Management: Learned the importance of meticulous 
planning and managing time efficiently throughout the project. 
Conclusion 
The Mini Game Collection project was an enriching experience that 
allowed us to apply core Python skills in a collaborative 
environment. Each game presented unique coding challenges, from 
implementing AI in Tic-Tac-Toe to designing a file-based 
leaderboard system. The project not only strengthened our 
programming abilities but also improved our teamwork and project 
management skills.
