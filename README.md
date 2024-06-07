# QuizzlerApp

## Overview
Quizzler is a fun and interactive quiz application designed to test your knowledge on various topics. Built using Object-Oriented Programming (OOP) principles in Python, Quizzler presents multiple-choice questions to the user and provides immediate feedback on their answers. The app features a graphical user interface (GUI) for an enhanced user experience.

## Project Structure

quizzler-app-start/
├── images/                         # Image assets used in the UI
├── data.py                         # Module for managing question data
├── main.py                         # Main application entry point
├── question_model.py               # Defines the Question class
├── quiz_brain.py                   # Contains the core logic for the quiz
└── ui.py                           # Manages the graphical user interface


### Detailed Description of Key Files:
- *data.py*: This module is responsible for fetching and managing the quiz questions. It typically includes functionality to load questions from an API or a static file.
- *main.py*: The starting point of the application. It initializes the quiz and starts the user interface.
- *question_model.py*: Defines the Question class, which represents a single quiz question, including its text and the correct answer.
- *quiz_brain.py*: Implements the logic for the quiz. It keeps track of the current question, checks the user's answers, and updates the score.
- *ui.py*: Handles the graphical user interface using a library like Tkinter. It displays questions, manages user interactions, and shows feedback on answers.

## Getting Started

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Installation
1. *Clone the repository*:
    sh
    git clone https://github.com/your-username/quizzler-app.git
    
2. *Navigate to the project directory*:
    sh
    cd quizzler-app
    
3. *Install the required dependencies*:
    sh
    pip install -r requirements.txt
    

### Usage
To run the application:
sh
python main.py

This command will launch the quiz app, displaying the first question in the GUI. You can interact with the app by selecting your answers and navigating through the questions.

## How It Works
1. *Start the Quiz*:
    - When you run main.py, the quiz app initializes the QuizBrain and UI classes.
2. *Display Questions*:
    - The UI module fetches a question from QuizBrain and displays it to the user with multiple-choice options.
3. *User Interaction*:
    - The user selects an answer, and the app checks if it's correct.
4. *Feedback and Scoring*:
    - The app provides immediate feedback (correct/incorrect) and updates the score.
5. *Progression*:
    - The quiz continues to the next question until all questions are answered.

