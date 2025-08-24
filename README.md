# German Flashcards (Deutsch → Arabic) – Flask

A simple **flashcard web app** built with Flask.  
The app shows a German word on the front side of the card, and its **Arabic translation** on the back.

Features include card flipping, next/previous navigation, marking words as known/unknown, progress tracking, and importing your own custom word lists.

---

## ✨ Features

- Flip cards (German → Arabic).
- Next / Previous navigation.
- Mark words as ✅ _Known_ or ❓ _Unknown_.
- Progress tracking with counters and a progress bar.
- Import your own custom deck directly in the browser.
- Built-in sample deck (basic German words).
- Text-to-Speech (TTS) for German words (front/back).

---

## 📦 Requirements

- Python **3.10+**
- [Flask](https://flask.palletsprojects.com/)

Install dependencies:

```bash
pip install -r requirements.txt
```

🚀 Run locally
python app.py
Open your browser at: http://127.0.0.1:5000

## 📥 Import custom deck

Use the 📥 Import Deck button in the UI.
Paste lines in the format:

arbeiten – to work
Freund, friend
billig – cheap; inexpensive

One line = one flashcard.
Separator can be either a dash (– or -) or a comma ,.

## 🔧 Modify default deck

The built-in deck is defined in app.py inside the variable:

DEFAULT_DECK = [
{"front": "tragen", "back": "لَبِسَ"},
{"front": "billig", "back": "رَخِيصٌ"},
{"front": "glücklich", "back": "سَعِيدٌ"},
...
]

You can edit this list to preload your own vocabulary.
