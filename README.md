# Quiz App 🧠

A simple interactive quiz application built with **HTML, CSS, and JavaScript**. Test your knowledge by answering multiple-choice questions, track your score, and play multiple attempts using a limited number of lives.

## ✨ Features

* 🧠 **Multiple-Choice Questions** — Answer a series of predefined quiz questions.
* ✅ **Answer Validation** — Immediately see which answer is correct and whether your selected answer was wrong.
* 📊 **Score Tracking** — Your score is calculated based on the number of correct answers.
* ❤️ **3 Lives / Attempts** — Players start with three chances to complete the quiz.
* 📈 **Attempt Statistics** — Previous attempt scores are displayed in the statistics panel.
* 🔄 **Reset & Replay** — Restart the quiz after completing an attempt.
* 🎉 **Game Over** — The game ends when all three chances have been used.
* 🔔 **Toast Notifications** — Displays a message when the selected answer is correct.
* 🎨 **Modern UI** — Gradient background, card-based layout, hover effects, and color-coded answers.

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **DOM Manipulation**
* **JavaScript Arrays & Objects**
* **Event Handling**

## 🎮 How It Works

The quiz questions are stored in a JavaScript array. Each question contains:

```javascript
{
  q: "What is 2+2?",
  answers: ["3", "4", "5", "6"],
  correct: 1
}
```

The `correct` value represents the index of the correct answer in the `answers` array.

### Answer Selection

When the user selects an answer:

1. All answer buttons become disabled.
2. The correct answer is highlighted in green.
3. If the selected answer is incorrect, it is highlighted in red.
4. The score increases when the selected answer is correct.
5. The **Next** button appears.

### 📊 Score System

At the end of each quiz, the application displays the user's score:

```text
You scored 3 of 4
```

The score is also stored in the attempts panel.

### ❤️ Lives System

The player starts with **3 lives**.

Each completed quiz attempt can be restarted using the Reset button. The number of remaining chances is displayed in the top-right statistics panel.

When all lives are used:

```text
Game Over!
```

is displayed and the quiz stops.

## 📋 Current Questions

The application currently includes questions about:

* Basic mathematics
* Geography
* JavaScript
* HTML

More questions can easily be added to the `questions` array.

## 🎨 UI Design

The interface includes:

* Purple/blue gradient background
* Centered quiz card
* Large question display
* Four answer buttons
* Color-coded answer feedback
* Next and Reset buttons
* Attempt statistics panel
* Toast notification for correct answers

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HaninMaarouf/Quiz-app.git
```

### 2. Open the project

```bash
cd quiz-app
```

### 3. Run the application

This is a standalone HTML, CSS, and JavaScript project, so you can simply open the HTML file in your browser.

You can also use **VS Code + Live Server** for easier development.

## 📂 Project Structure

```text
quiz-app/
│
├── index.html
└── README.md
```

## 🎯 Project Purpose

This project was created to practice fundamental **JavaScript concepts**, including:

* Variables and arrays
* Objects
* Functions
* DOM manipulation
* Event listeners
* Conditional statements
* Loops
* Dynamic HTML element creation
* Managing application state

## 👩‍💻 Author

**Hanin Maarouf**

GitHub: [HaninMaarouf](https://github.com/HaninMaarouf)

