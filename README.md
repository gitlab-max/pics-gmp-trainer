# PIC/S GMP Trainer

A free, open‑source, scenario‑based quiz tool for Good Manufacturing Practice (GMP) based on PIC/S guidelines.  
Designed for QA professionals to train teams and create custom question banks.

## 🔗 Live Demo
[Click here to try it](https://gitlab-max.github.io/pics-gmp-trainer/)

## ✨ Features
- 📚 Covers PIC/S Part I (and optionally Part II, Annexes)
- ✏️ **Edit mode** – modify questions, add topics, change answers without coding
- 💾 Progress saved automatically in your browser
- 📥 Export your edited question bank as JSON
- 🔁 Separate storage per reference (Part I, Part II, Annexes)

## 🧪 How to use
1. Select a reference (Part I, Annex 1, etc.)
2. Choose a chapter and answer scenario‑based multiple‑choice questions
3. Click **Edit Mode** to adapt questions to your company’s own procedures

## 📁 File structure for local use
If you want to run it on your own computer, place the HTML and JSON files in the same folder and start a local web server:
```bash
python -m http.server 8000
