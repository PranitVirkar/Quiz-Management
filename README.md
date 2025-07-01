# 🎓 Quiz Management System using Java

A Java-based desktop application that allows users to take multiple-choice quizzes in an interactive GUI environment. This application includes essential features like login, timer-based questions, scoring, and result display.

---

## 📌 Features

- **🔐 Login System**
  - Users enter their name to start the quiz.
  - Simple user validation.

- **📜 Rules Display**
  - Shows quiz rules before the quiz begins.
  - "Start Quiz" and "Back" buttons for navigation.

- **❓ Quiz Questions**
  - Displays one multiple-choice question at a time.
  - Each question has 4 options (radio buttons).

- **⏱️ Timer**
  - Each question is time-bound (e.g., 15 seconds).
  - Automatically moves to the next question on timeout.

- **🧮 Score Tracking**
  - Correct answers are rewarded with points.
  - No negative marking.

- **📊 Result Display**
  - Final score is shown with the user’s name.
  - Option to **Play Again** or **Exit**.

---

## 🛠️ Technologies Used

- Java
- Java Swing
- AWT
- JFrame, JLabel, JButton, JRadioButton, Timer

---

## 📂 Project Structure

QuizManagementSystem/
│
├── src/
│ ├── Login.java # Name input and validation
│ ├── Rules.java # Rules and instructions
│ ├── Quiz.java # Question panel, options, timer, navigation
│ ├── Score.java # Final result and replay
│
├── assets/
│ └── images/ # Optional GUI images
│
└── README.md # Project description
