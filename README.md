# Hogwarts House Sorting Quiz

Welcome to the **Hogwarts House Sorting Quiz** repository! This program helps users discover which Hogwarts house they belong to based on their personality traits, preferences, and values. The quiz presents a series of questions and, based on the user's choices, assigns them to one of the four Hogwarts houses: **Gryffindor**, **Slytherin**, **Hufflepuff**, or **Ravenclaw**.

## Features
- A fun and interactive quiz that determines which Hogwarts house you belong to.
- Based on 12 different personality questions, with options linked to various house traits.
- Handles invalid inputs by prompting the user to reselect an option if they enter an incorrect one.
- Provides a detailed description of the house the user is sorted into, with a personalized message.

## Houses
- **Gryffindor**: Known for bravery, daring, nerve, and chivalry.
- **Slytherin**: Known for ambition, cunning, and resourcefulness.
- **Hufflepuff**: Known for loyalty, fairness, and hard work.
- **Ravenclaw**: Known for wisdom, wit, and a quest for knowledge.

## How to Use
1. Clone or download this repository to your local machine.
2. Open a terminal or IDE and navigate to the folder where the code is stored.
3. Compile and run the program using any C++ compiler.
   - Example: If using `g++`, run:
     ```bash
     g++ main.cpp -o hogwarts_quiz
     ./hogwarts_quiz
     ```
4. Answer the questions by entering one of the provided options (a, b, c, or d).
5. After completing the quiz, the program will display which Hogwarts house you are sorted into based on your responses.

## Code Explanation
The program works by asking the user a series of questions. For each question, the user selects an option. Based on the user's choices, the program tallies up scores for each house. After all questions are answered, the house with the highest score is selected. In case of a tie, the program asks an additional question to break the tie.

### Key Functions:
- `invalid(char ch)`: Ensures the user selects a valid option. If an invalid choice is entered, the function prompts the user to enter a valid one.
- `gryffindor()`, `slytherin()`, `hufflepuff()`, `ravenclaw()`: These functions display a personalized welcome message based on the user's assigned house.
- The main function handles the quiz flow, including input collection, tallying the scores, and displaying the final result.

<!DOCTYPE html>
<html>
<body>

<img src="file:///Users/_kodiko_/Downloads/Hat.jpg" alt="Sorting Hat">


</body>

</html>
