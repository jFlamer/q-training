# 🎮 Quizz App

A simple web-based quiz application built using **HTML**, **CSS**, and **JavaScript**. Users can customize quiz settings such as number of questions, category, difficulty, and time per question. Questions are fetched dynamically from the [Open Trivia Database](https://opentdb.com/).

---

## 🚀 Features

- Start screen with customizable quiz settings
- Dynamic question and answer generation
- Timed questions with a progress bar
- Feedback on selected answers (correct / wrong)
- Final score display and restart option

---

## 📂 File Structure

```
/
├── index.html         # Main HTML file
├── style.css          # CSS styling
├── script.js          # JavaScript functionality
```

---

## 🔄 How to Use

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Select your desired quiz settings:
   - Number of questions
   - Category (e.g. general knowledge, video games, science)
   - Difficulty (easy, medium, hard)
   - Time limit per question
4. Click **"Start Quizz"** to begin.
5. Select an answer and submit. At the end, view your score and optionally restart the quiz.

---

## 🔗 External API

This app uses the [Open Trivia Database API](https://opentdb.com/api_config.php) to fetch quiz questions:

```
https://opentdb.com/api.php?amount=<NUM>&category=<CATEGORY>&difficulty=<DIFFICULTY>&type=multiple
```

---

## ⚡ Customization

You can easily expand or customize the app by:
- Adding more answer types (true/false)
- Improving mobile responsiveness
- Animating transitions between screens
- Storing high scores with `localStorage`

---


## ⚖️ License

This project is open-source and free to use for educational or personal projects.

---

## 📚 Credits

Quiz data provided by: [Open Trivia DB](https://opentdb.com/)

Created with ❤️ using vanilla HTML/CSS/JS.

