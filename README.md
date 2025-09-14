Got it 👍 Here’s a **ready-to-use README description** you can put in your GitHub repo:

---

# 📘 MCQ Based Online Exam Application

## 📌 Overview

This project is a **Multiple Choice Question (MCQ) Based Online Exam Application** developed in **Python**.
It simulates an online test system where questions are loaded from a CSV file, participants attempt the exam, and their answers are evaluated automatically.

---

## 📂 Project Files

* **`question.csv`** → Contains the list of questions, options, and correct answers.
* **`question_master.py`** → Responsible for reading and managing questions from the CSV file.
* **`exam_client.py`** → Provides an interactive exam experience for the participant.

---

## 📑 Sample `question.csv` Format

```csv
num,question,option1,option2,option3,option4,correctoption
1,10+20 ans is,op1=20,op2=30,op3=40,op4=10,op2
2,20-10 ans is,op1=20,op2=30,op3=40,op4=10,op4
3,2*2 ans is,op1=4,op2=5,op3=6,op4=7,op1
4,5/2 ans is,op1=2.5,op2=3,op3=6,op4=7,op1
5,capital of india,op1=delhi,op2=blr,op3=mum,op4=chn,op1
6,linux is a,op1=os,op2=app,op3=game,op4=antivirus,op1
```

---

## 🚀 Features

* Load questions dynamically from a CSV file
* Display multiple-choice questions to the user
* Accept user responses and validate answers
* Display final score at the end of the exam

---

## 🛠️ Technologies Used

* **Python 3**
* **CSV module** (for reading questions)

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mcq-exam-app.git
   cd mcq-exam-app
   ```
2. Ensure `question.csv` is in the project folder.
3. Run the exam:

   ```bash
   python exam_client.py
   ```

---

## 📌 Future Improvements

* Add exam timer for each question
* Save scores in a results file
* Build a GUI (Tkinter / Flask web version)
* Add login and user management


