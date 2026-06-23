# Logic Programming with Prolog — LLP Exercises 🧠🧩

A centralized repository containing solutions, knowledge bases, and inference scripts developed for the practical exercise lists during the **Programming Languages Laboratory (LLP)** course in the Computer Engineering curriculum at CEFET-MG.

---

## 👥 Authorship & Faculty

* **Professor:** Dr. Andrei Rimsa Álvares
* **Student:** Matheus Thiago de Souza Ferreira

---

## 📂 Repository Scope & Core Paradigms

The scripts inside this repository explore the core concepts of **Logic Programming**, moving away from standard control flow loops into a declarative environment driven by formal logic, facts, and relations. The topics covered include:

* **Facts & Knowledge Bases:** Defining explicit relational truths and structural predicates.
* **Rules & Logical Inference:** Engineering conditional rules to deduce new implications using Horn clauses.
* **Unification & Backtracking:** Leveraging Prolog's native pattern-matching engine and automatic deep search tree exploration.
* **Recursion over Lists:** Processing collection structures through structural separation (`[Head | Tail]`) without explicit counters.
* **Cut (`!`) & Negation-by-Failure:** Managing search-space optimization and pruning the evaluation resolution tree.

---

## 🚀 Execution & Interactive Environment

You can query your knowledge bases individually using an interactive Prolog top-level interpreter, such as **SWI-Prolog**.

### 1. Prerequisites
Ensure you have **SWI-Prolog** installed on your local workstation. It can be downloaded from the official [SWI-Prolog downloads page](https://www.swi-prolog.org/).

### 2. Loading a Script in the Interactive Shell
Open your terminal window inside the project directory and launch the SWI-Prolog interpreter directly with your source target file:
```bash
swipl name_of_exercise_file.pl
```

### 3. Querying the Knowledge Base
Once inside the interactive environment, you can run queries by ending the statement with a period (`.`):
```bash
% Example query inside the top-level shell
ancestor(X, matheus).
```
* Press `;` to ask the compiler to find alternative solutions via backtracking.
* Press `Enter` to halt searching once a valid result satisfies the constraint.

### 4. Reloading Changes
If you modify your source code facts or rules in your external editor, reload the environment instantly inside the shell without quitting:
```bash
make.
```
* To exit the active SWI-Prolog interactive process, type halt..

## 🔧 Core Tech Stack
* Language Platform: Prolog (ISO Standard)
* Compiler Engine: SWI-Prolog Interpreter
