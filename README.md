Here’s a **README.md** file for your project:


#Password Strength Analyzer with Custom Wordlist Generator

## 📌 Overview

This project provides a **Password Strength Analyzer** and a **Custom Wordlist Generator**.
It helps users:

* Test the strength of their passwords.
* Generate custom wordlists for penetration testing or research purposes.

Built using **Python** with optional support for `zxcvbn` for advanced password strength scoring.

---

##  Features

* ✅ Analyze password strength (entropy, guesses, crack time).
* ✅ Save analysis reports to `reports/`.
* ✅ Generate **custom wordlists** from user inputs like names, pets, dates.
* ✅ Supports common patterns (leetspeak, years, numbers, symbols).
* ✅ Export wordlist as `.txt` file in `wordlists/`.
* ✅ Works as **CLI tool**, with optional GUI support.

---

## 🛠️ Requirements

* Python 3.7+
* Optional libraries:

  ```bash
  pip install zxcvbn nltk
  ```

---

## 📂 Project Structure

```
Password-Tool/
│── password_tool.py    # Main script
│── reports/            # Stores password analysis reports
│── wordlists/          # Stores generated wordlists
│── README.md           # Project documentation
```

---

## ⚡ Usage

### 1. Analyze Password Strength

```bash
python password_tool.py --password "MyPassw0rd!"
```

* Output will be shown in terminal.
* Report saved in `reports/` folder.

### 2. Generate Custom Wordlist

```bash
python password_tool.py --genlist
```

* Enter details (name, pet, year, favorite word).
* Wordlist saved in `wordlists/`.

---


### Password Analysis:

Password: MyPassw0rd!
Strength: Strong
Estimated crack time: 10 years
Report saved in reports/password_report.txt


### Wordlist Example:

alex1999
alex@123
Puppy2023
alex!pet




**step-by-step installation guide with screenshots** in this README so even beginners can follow easily?
# Password-Strength-Analyzer-with-Custom-Wordlist-Generator
