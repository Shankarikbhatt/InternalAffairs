# 🎓 InternalAffairs

> *"Because your marks are nobody else's business."*

**InternalAffairs** is a student-built, student-focused internal marks calculator designed for university students. Enter your internal assessment scores and instantly find out exactly how much you need in your semester exam to hit your target grade — no spreadsheets, no manual math, no panic.

Live Demo Link: https://shankarikbhatt.github.io/InternalAffairs/
---

## ✨ Features

- 🎯 **Smart Mark Calculator** — Supports J Component, Math, and Tamil subject types with automatic conversion formulas (CAT ÷ 50, Unit Test ÷ 25)
- 📊 **Target Grade Engine** — Pick your desired grade (O, A+, A, B+, B, C) and get the exact semester exam score you need out of 100
- 🎨 **4 Built-in Themes** — Switch between Original Mint, The Curious Mix, Mocha & Gold, and Midnight Amethyst with one click
- 🧘 **Calming Breath Guide** — 7-cycle breathing exercise to calm pre-exam nerves
- 🎵 **Focus Soundscape** — Brown noise and white noise generator for deep focus sessions
- ✅ **Exam Packing Checklist** — Never forget your hall ticket again
- 📝 **Syllabus Scratchpad** — Quick notes that auto-save in your browser
- 💾 **Snapshot Save** — Save your current mark inputs and restore them anytime
- 💡 **Cram Mode** — Low-light overlay to reduce eye strain during late-night sessions
- 📱 **Fully Responsive** — Works on desktop, tablet, and mobile

---

## 🏫 Supported Subject Types

| Subject | Internal Max | External Max | Components |
|---|---|---|---|
| J Component | 50 | 50 | CAT 1, CAT 2, Lab + Record |
| Math | 40 | 60 | CAT 1, CAT 2, Unit 1, Unit 2, Assignment, G.P |
| Tamil | 40 | 60 | CAT 1, CAT 2 |

---

## 📐 Grade Table

| Marks | Grade | Grade Point |
|---|---|---|
| 90 – 100 | O | 10 |
| 80 – 89 | A+ | 9 |
| 70 – 79 | A | 8 |
| 60 – 69 | B+ | 7 |
| 50 – 59 | B | 6 |
| 40 – 49 | C | 5 |
| 0 – 39 | U | 0 |

> Minimum passing marks: **40 (Grade C)**

---

## 🚀 How to Run

### Option 1 — Run via Python (Recommended)
1. Make sure Python is installed on your system ([Download Python](https://www.python.org/downloads/))
2. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/InternalAffairs.git
   ```
3. Navigate into the project folder:
   ```bash
   cd InternalAffairs
   ```
4. Run the script:
   ```bash
   python internal_affairs.py
   ```
5. The calculator will automatically launch in your default browser!

### Option 2 — Open HTML directly
Simply open `index.html` in any modern browser — no installation needed.

---

## 🛠 Tech Stack

- **Python 3** — Launcher script
- **HTML5 / CSS3 / Vanilla JavaScript** — Full frontend, zero dependencies
- **Web Audio API** — Built-in noise generator (no external files needed)

---

## 📁 Project Structure

```
InternalAffairs/
│
├── internal_affairs.py   # Python launcher
├── index.html            # Standalone HTML version
└── README.md             # You're reading this!
```

---

## 🙋 Who is this for?

Built specifically for students at **SRM Institute of Science and Technology** (or any university following a similar internal marks structure). Shared with batchmates so nobody has to manually calculate their marks ever again.

---

## 🤝 Contributing

Found a bug? Want to add your department's subject type? Pull requests are welcome!

1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Built with 💛 by a student, for students.<br><i>Stop guessing. Start scoring.</i></p>
