# QuizApp

QuizApp is a React application that presents a series of questions to users, allows them to answer or skip questions, and displays a summary of their results upon completion. This project demonstrates state management, component interaction, and dynamic rendering in a React application.

## Features

- **Dynamic Quiz Management:** Displays questions one at a time and tracks user responses.
- **Answer and Skip:** Users can select an answer or skip a question.
- **Randomized Answers:** Answers are shuffled to provide a different order each time.
- **Timer for Questions:** A timer is set for each question to encourage quick responses.
- **Summary Display:** Shows the number of questions answered correctly, incorrectly, and skipped.

## Components

- `Quiz`: Manages the overall state of the quiz and renders `Question` or `Summary` based on progress.
- `Question`: Displays a single question with shuffled answers and handles user interaction.
- `Answer`: Renders the list of possible answers and handles answer selection.
- `QuestionTimer`: Displays a countdown timer for each question.
- `Summary`: Displays the summary of the user's responses at the end of the quiz.

