

## 🩺 MedicoBot: Your Health System Checker

Welcome to **MedicoBot** — an interactive, console-based health diagnosis tool written in C++. While it's *not a substitute for a real doctor*, it can guide you through a decision tree of symptoms and give you a friendly, bot-style diagnosis based on your answers.

> ⚠️ **Disclaimer:** This project is for educational purposes only. It does **not** provide real medical advice.

---

### 📌 Features

* 🌿 Symptom-based diagnosis using a decision tree.
* 🧠 Intelligent backtracking — go back to previous questions using `back`.
* 📝 Records and saves diagnosis history per patient.
* 🔎 View all past diagnoses or filter by patient name.
* 🧹 Option to clear all saved history.
* 💾 Diagnosis history is stored in a local file (`diagnosis_history.txt`) so it persists between runs.
* 🧪 Fun responses to make the diagnosis feel more conversational.

---

### 📷 Demo (Console Output)

```
=======  Welcome to the MedicoBot-Your health System Checker  =======

Disclaimer: I'm not a doctor, but I did pass a few Google searches!

Answer questions with yes/no. Type 'back' to go to previous question.

Menu:
1. Start new diagnosis
2. View past diagnoses for a patient
3. View all
4. Clear all saved diagnosis history
5. Exit
Choose: 
```

---

### 🛠️ Tech Stack

* **Language:** C++
* **Concepts used:**

  * Linked Lists
  * Stacks
  * File I/O
  * Decision Trees
  * Structs and Classes

---

### 🔄 How It Works

1. The program uses a binary decision tree where each node is a symptom-related question.
2. Your answers (`yes`, `no`, or `back`) guide the traversal down the tree.
3. At the end, a final diagnosis is printed along with a summary of all your answers.
4. The result is saved with your name in a file for future reference.

---

### 📁 File Structure

```
📦MedicoBot
 ┣ 📄 main.cpp                 # Main program file
 ┣ 📄 diagnosis_history.txt   # Auto-generated file storing diagnosis records
 ┗ 📄 README.md                # You're here!
```

---

### 🧪 Example Diagnoses

* *"You might have COVID-19. Please get tested."*
* *"You seem healthy!"*
* *"You might be experiencing a Migraine."*

Each diagnosis is accompanied by a summary of the questions and your answers.

---

### 🧽 Clear Diagnosis History

To clear all previous records:

* Choose option `4` from the menu.
* This deletes both the linked list in memory and clears the contents of the `diagnosis_history.txt` file.

---

### ✨ Future Improvements (Optional Ideas)

* Add support for more complex conditions and branching.
* GUI interface using Qt or a web frontend.
* Add patient age/gender-based custom paths.
* Encrypt or password-protect diagnosis history.

---

### 🙌 Contributing

Pull requests are welcome! If you have suggestions to improve this bot (features, refactor, new symptoms), feel free to fork and submit a PR.

---


