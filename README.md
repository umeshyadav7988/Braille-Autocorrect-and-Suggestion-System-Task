# 🔠 Braille Autocorrect and Suggestion System

A smart autocorrect and word suggestion system for users typing Braille using a standard QWERTY keyboard. This tool improves accessibility for visually impaired individuals by correcting mistyped Braille input in real time.

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Contact](https://img.shields.io/badge/Contact-umeshyadav7988@gmail.com-red)](mailto:umeshyadav7988@gmail.com)

---

## 📌 Features

- ✅ Supports QWERTY-based Braille typing using keys `D W Q K O P` (dots 1 to 6)
- ✅ Auto-corrects input based on **Levenshtein distance**
- ✅ Suggests the closest matching word from a predefined dictionary
- ✅ Handles missing, extra, or incorrect key inputs
- ✅ Designed for real-time performance and scalability
- 🏆 Extensible for larger dictionaries and multi-language support

---

## 🧠 How It Works

Braille characters are formed using a 2x3 dot grid. On a QWERTY keyboard:

| Dot | Key |
|-----|-----|
| 1   | D   |
| 2   | W   |
| 3   | Q   |
| 4   | K   |
| 5   | O   |
| 6   | P   |

Users enter multiple keys simultaneously to create a Braille character. The system then:
1. Converts the key presses to Braille dot patterns
2. Translates dot patterns to letters
3. Forms the typed word
4. Compares it against a dictionary using Levenshtein distance
5. Suggests the closest matching word

---

## 🖥️ Sample Run

```

Enter Braille characters one by one.
For each character, type the keys (D W Q K O P) space-separated.
Press Enter on an empty line when done.

> D K
> D W
> D Q

Typed word: cat
Suggested word: cat

````

---

## 📁 Files

- `braille_autocorrect.py` - Core script for input, translation, and autocorrection
- `Braille_Autocorrect_Test_Cases.pdf` - ✅ Colorful PDF of test cases
- `README.md` - Project documentation

---

## 🧪 Sample Test Cases

Test inputs and results for 10 Braille word simulations are provided in a downloadable PDF:

📄 [Download Sample Test Cases PDF](https://github.com/umeshyadav7988/Braille-Autocorrect-and-Suggestion-System-Task/blob/main/Braille_Autocorrect_Test_Cases.pdf)

---

## Future Enhancements

- Multi-language support
- Braille contractions (Grade 2 Braille)
- Adaptive learning from user corrections
- Trie-based lookup for faster suggestions

---

## 🛠️ Requirements

- Python 3.6+
- No external dependencies (optional: `fpdf` for PDF generation)

Install FPDF if needed:
```bash
pip install fpdf
````

---

## 📬 Contact

Created with ❤️ by [Umesh Yadav](mailto:umeshyadav7988@gmail.com)
Feel free to open issues or suggest improvements!

---

