# 🧮 Algebra Adventure

**Algebra Adventure** is a single-file, kid-friendly web game built with plain **HTML**, **CSS**, and **JavaScript**.  
Designed for students (grades 4–7), it teaches basic algebra through three fun sections: **Learn**, **Practice**, and **Test**.

---

## 🚀 Live Preview
Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari) to play locally.

---

## ✨ Features
- 📚 **Learn** — Interactive lessons covering variables, addition, subtraction, multiplication and division with visual aids and examples.
- 🎮 **Practice** — Randomized equations, multiple-choice answers, score tracking, progress bar and sound/visual feedback (confetti for wins).
- 🧪 **Test** — Timed quiz mode (10 questions) with results, star ratings and replay option.
- 🔊 Sound toggle, cute robot character, and mobile-responsive layout.
- Pure front-end — no build tools, no dependencies.

---

## 🗂️ Project Structure

algebra-adventure/
├─ index.html        # Single-file app (HTML + CSS + JS)
└─ README.md         # This file

````

> The entire app is contained in `index.html` for easy sharing and deployment.

---

## 🛠️ How to Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/Shadab-2604/algebra-adventure.git
   cd algebra-adventure
````

2. Open `index.html` in a browser:

   * Double-click the file, or
   * Serve with a static server (optional):

     ```bash
     # using Python 3
     python -m http.server 8000
     # then open http://localhost:8000
     ```

---

## 🧩 How It Works (brief)

* Lessons are defined in a `lessons` array inside the file — each lesson contains `title` and `html`.
* Practice and Test modes generate equations randomly (add/subtract/multiply/divide) and produce 4 answer options.
* Scoring, timers and UI state are managed by vanilla JS functions inside `index.html`.

---

## ✍️ Customize

* Add or edit lessons: modify the `lessons` array.
* Change difficulty: tweak random ranges in `generateEquation()` (inside the script).
* Adjust the number of practice/test questions by editing `maxPracticeQuestions` / `maxTestQuestions`.
* Replace emoji visuals with images or SVGs if desired.

---

## ✅ Browser Compatibility

Tested on modern browsers. Works offline as it is a static file.

---

## ♿ Accessibility & Improvements (ideas)

* Add keyboard navigation for options (Left/Right/Enter).
* Provide ARIA labels for screen readers.
* Add localized text (translations) for other languages.
* Add levels and user profiles / persistent scores (localStorage).

---

## 🧑‍💻 Contributing

Contributions are welcome!

* Fork the repo
* Create a feature branch: `git checkout -b feature/your-feature`
* Commit and open a Pull Request
  I'll review and merge improvements, bug fixes, and new lessons.

---

## 📜 License

This project is free to use — **MIT License** (add LICENSE file if you want a formal license).

---

## ❤️ Credits

Made with ❤️ for young learners. Inspired by playful teaching methods and interactive learning games.

---

If you want, I can:

* Generate a ready-to-add `LICENSE` file (MIT).
* Create a small `CONTRIBUTING.md`.
* Turn this README into the repo's actual `README.md` file for you (I can produce the file content).

```

Would you like me to also create a `LICENSE` (MIT) and a `CONTRIBUTING.md` file now?
```
