# IT23842212 - IT3040 ITPM Assignment 1

## 📌 Project Title

**Automated Testing of Singlish to Sinhala Transliteration System**

---

## 📁 Project Structure

```
IT23842212/
│
├── IT23842212_test_automation.py
│   → Playwright automation script
│
├── IT23842212 - Assignment 1 - Test cases.xlsx
│   → Excel file with test cases and results
│
├── IT23842212_requirements.txt
│   → Python dependencies and repository reference
│
└── IT23842212_README.md
    → Project documentation
```

---

## 🛠 Technologies Used

* Python
* Playwright (UI Automation)
* OpenPyXL (Excel Handling)

---

## ⚙️ How to Run the Project

### 1. Open Terminal

Navigate to the project folder.

---

### 2. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install playwright openpyxl
python -m playwright install
```

---

### 3. Run the Automation Script

```bash
python IT23842212_test_automation.py --excel "IT23842212 - Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## 📊 Output

* Results are automatically written to the Excel file

### Updated Columns:

* Actual Output
* Status (PASS / FAIL)

---

## 🧪 Test Case Details

* Total Test Cases: **50+**
* Test Type: **Negative Testing**

### Covered Scenarios:

* Question forms
* Command forms
* Greetings
* Requests and responses
* Repeated words
* Inputs with punctuation
* Romanization / spelling variations
* English words embedded in Singlish
* Multi-word English phrases
* Digital terms and platform names
* Abbreviations and acronyms
* Clipped forms
* Place and person names
* Numerical inputs and suffixes
* Currency formats
* Time and date formats
* Units of measurement
* Slang and casual language
* Online identifiers
* Emoji-containing inputs

---

## ⚠️ Important Notes

* The system uses **strict output comparison**
* Even minor differences (spacing, spelling, formatting) may result in **FAIL**

### Some failures are expected due to:

* Transliteration inconsistencies
* Mixed-language complexity
* UI timing delays

---

## 👨‍🎓 Student Information

* **Student ID:** IT23842212
* **Module:** IT3040
* **Assignment:** Assignment 1 (Option 1)

---

## ✅ Final Status

✔ Automation script successfully implemented
✔ Excel-based validation completed
✔ Wide range of edge cases covered

---

## 📌 Submission Notes

* All required files are included
* Project is fully functional and runnable
