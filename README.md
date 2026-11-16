# Ateninha

A Java Swing desktop app built to help the administrative office of CEAP, the school where I took the Computer Technician course. It keeps track of items and rooms lent to teachers.

## Features

- **Loan register:** a form with code, item or room, number of items, teacher and time slot.
- **Table view:** every loan appears in a `JTable`.
- **Status:** mark each loan as delivered or pending.
- **Editing:** remove any entry from the table.
- **Period report:** "Encerrar período" saves the whole table as a timestamped `Relatório.txt` in a folder you choose.

## Project structure

```
src/
├── Ateninha.java         # main window and loan table
└── Atividade_word.java   # report export (save dialog + text file)
imagens/                  # logos and illustrations
```

## Run

Requires a JDK (8 or newer). From the repository root:

```bash
javac -encoding UTF-8 -d out src/*.java
java -cp out Ateninha
```

Run it from the repository root, because the images load from the relative `imagens/` folder.

---

Made by [Heleno Matos](https://portfolio.helenomatos.com) during the Computer Technician course at CEAP (2019–2021).
