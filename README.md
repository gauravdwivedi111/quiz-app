# Dynamic Quiz Application — Vanilla JS & JSON Data

An interactive, client-side quiz application featuring dynamically loaded questions, distinct evaluation mechanics per question type, and score compilation dashboarding.

---

## Key Features

*   **JSON-Driven Data Loader**: Parses quiz categories and configurations directly from `quiz-data.json` at run time, enabling easy additions of new questions without touching JavaScript files.
*   **Multi-Format Question Evaluation**: Automatically builds and validates inputs for multiple formats:
    *   *Multiple Choice (MCQ)*: Renders interactive option cards.
    *   *Text Fill-in*: Case-insensitive string matching.
    *   *Numeric Fill-in*: Exact integer/float checking.
*   **Progressive Navigation**: Provides a step-by-step navigation wizard showing progress indicators, timer countdowns, and summary score logs.

---

## Tech Stack

*   **Frontend**: HTML5, CSS3, ES6 JavaScript.
*   **Data Format**: JSON (Structured data mapping sections, question types, choices, and answers).

---

## Setup and Running Locally

To run the application:

1.  Navigate to the project directory:
    ```bash
    cd "quiz app"
    ```
2.  Open `index.html` in any web browser.
3.  Alternatively, host it locally using a simple HTTP server:
    ```bash
    # Using python 3
    python -m http.server 8000
    ```
    Then visit: `http://localhost:8000`

---

## Project Structure

```text
quiz-app/
├── index.html                   # Grid layouts, timer frames, score displays
├── quiz-data.json               # Configured quiz sections & questions
├── script.js                    # Parsing, navigation controller, scoring logic
├── style.css                    # Grid structures, visual variables, animations
└── README.md                    # Root Documentation (this file)
```

---

## Author
*   **Gaurav Dwivedi** - [GitHub Profile](https://github.com/gauravdwivedi111)

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.
