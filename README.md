#Quiz Application
This Python program conducts a simple quiz based on the provided questions and checks the user's knowledge by asking multiple-choice questions. It utilizes the question_model, data, and quiz_brain modules to execute the quiz functionality.

##How it Works
The program imports necessary modules: Question from question_model, question_data from data, and QuizBrain from quiz_brain.

It creates a question_bank by iterating through the question_data, creating Question instances, and storing them in the bank.

A QuizBrain object quiz is created, initializing it with the question_bank.

The program runs a loop using quiz.next_question(), presenting questions from the bank to the user until there are no more questions left.

After the quiz ends, it displays the user's final score.

##Usage
To run the quiz application:

Ensure all necessary modules (question_model, data, and quiz_brain) are present and accessible.

Execute the main script:
python main.py

##Modules Used
question_model: Contains the Question class defining question and answer attributes.
data: Holds the question_data used to populate the quiz.
quiz_brain: Manages the quiz mechanics, handling questions, user responses, and scoring.
