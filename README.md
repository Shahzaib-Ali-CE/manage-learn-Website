# 📚 Study Ledger

A clean, lightweight study management web app built with **HTML, CSS, and Vanilla JavaScript**.

Study Ledger helps you organize subjects, create flashcards, review material using a spaced-repetition system, track your study streak, and monitor your overall learning progress — all directly in your browser.

## ✨ Features

* 📊 **Dashboard**

  * Cards due for review
  * Overall mastery percentage
  * Current study streak
  * Review activity for the last 7 days
  * Seven-day review forecast
  * Mastery progress by subject

* 📖 **Subject Management**

  * Create and delete subjects
  * Add an optional topic/focus for each subject
  * View cards belonging to each subject
  * Track mastery percentage per subject

* 🧠 **Flashcards**

  * Create custom question-and-answer cards
  * Optional multiple-choice questions
  * Delete cards when no longer needed

* 🔄 **Spaced Repetition**

  * Uses an **SM-2-lite** scheduling algorithm
  * Cards are rescheduled based on how well they were remembered
  * Review intervals increase as cards become easier
  * Difficult cards return sooner

* 🎯 **Study Sessions**

  * Study all due cards or cards from a specific subject
  * Multiple-choice questions are automatically evaluated
  * Rate your recall using:

    * Again
    * Hard
    * Good
    * Easy
  * Session results are displayed at the end

* 🔥 **Study Streak**

  * Tracks consecutive days of study activity
  * Encourages consistent daily revision

* 📅 **Planner**

  * Shows cards due today by subject
  * Displays upcoming review workload for the next seven days
  * Helps distribute your study workload

* 💾 **Local Data Storage**

  * Your subjects, cards, reviews, and statistics are saved using browser `localStorage`
  * No account or backend is required

* 📱 **Responsive Design**

  * Desktop sidebar navigation
  * Mobile-friendly navigation
  * Responsive layouts for different screen sizes

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **Web Storage API (`localStorage`)**
* **Google Fonts**

  * Inter
  * Fraunces

No frameworks, libraries, build tools, or backend server are required.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/study-ledger.git
```

### 2. Open the project

Navigate into the project folder:

```bash
cd study-ledger
```

### 3. Run the application

Since Study Ledger is a standalone web application, you can simply open the HTML file in your browser.

```text
index.html
```

No installation or build process is required.

## 📂 Project Structure

```text
study-ledger/
│
├── index.html
└── README.md
```

The application is currently contained in a single HTML file with its CSS and JavaScript included directly in the file.

## 🧠 How Spaced Repetition Works

Study Ledger uses a lightweight implementation of the **SM-2 spaced-repetition approach**.

When reviewing a card, you can rate your recall:

| Rating | Meaning                           |
| ------ | --------------------------------- |
| Again  | You didn't remember it            |
| Hard   | You remembered it with difficulty |
| Good   | You remembered it reasonably well |
| Easy   | You remembered it easily          |

Cards rated poorly are scheduled sooner, while cards that are consistently remembered receive longer review intervals.

The application stores information such as:

* Repetition count
* Review interval
* Ease factor
* Due date
* Last reviewed date
* Correct answers
* Incorrect answers

## 💾 Data & Privacy

Study Ledger stores application data locally in your browser using `localStorage`.

There is currently:

* No backend
* No database
* No user account
* No login system
* No external API required

Your study data remains in the browser where you use the application.

## 🔄 Resetting Data

The application includes a **Reset all data** option.

Resetting restores the original starter subjects and flashcards and removes your existing study records.

⚠️ This action cannot be undone.

## 🎨 Design

The interface uses a minimal academic aesthetic with:

* Warm paper-inspired background
* Moss green accents
* Gold highlights
* Serif headings
* Clean card-based layouts
* Responsive components

The goal is to make studying feel organized without making the interface unnecessarily complicated.

## 📌 Future Improvements

Possible improvements for future versions include:

* [ ] Import/export study data
* [ ] Dark mode
* [ ] Search and filter cards
* [ ] Edit existing cards
* [ ] More detailed analytics
* [ ] Custom study sessions
* [ ] Customizable review intervals
* [ ] Keyboard shortcuts
* [ ] Cloud synchronization
* [ ] User accounts
* [ ] PWA/offline installation support

## 👨‍💻 Author

**Shahzaib Ali**

Computer Engineering Student
Pakistan

---

⭐ If you find this project useful, consider giving the repository a star!
