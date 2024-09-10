# Quiz-App-II

A simple and interactive quiz application built with HTML, CSS, JavaScript, and Bootstrap. This app features a countdown timer, dynamic color changes based on the time left, and a scoring system.

# Features

  - Loading Screen: Displays a start button and the highest score from previous attempts (if have).
  - Quiz Gameplay:
      - Questions are displayed one at a time with multiple-choice options.
      - Countdown timer for each question with dynamic color changes based on remaining time.
      - User can select an answer, which is then validated.
      - Results are displayed at the end of the quiz with option to retry.
  - Scoring System:
      - Tracks correct and incorrect answers.
      - Updates highest score based on the current quiz performance.
  - Dynamic Styling:
      - Background and button colors change based on the time remaining in the countdown.
      - Answer options are visually marked as correct or wrong based on the user’s selection.
  
# Technologies Used

  - HTML: Structure and content of the quiz application.
  - CSS: Styling of the quiz application.
  - JavaScript: Functionality, including quiz logic, timer, and DOM manipulation.
  - Bootstrap: For responsive design and UI components.

# Code Explanation

  - DOM Caching: Caches frequently accessed DOM elements for performance.
  - Quiz State Management: Keeps track of the current question index, scores, and timer duration.
  - Countdown Timer: Changes background and button colors based on remaining time (15 seconds and 5 seconds thresholds).
  - Question Loading: Loads new questions and options, and resets the UI for each new question.
  - Answer Handling:
      - Marks selected options as correct or wrong.
      - Highlights the correct answer if the selected answer is wrong.
  - Result Display: Shows the final score with a percentage breakdown and option to retry the quiz.    

  
