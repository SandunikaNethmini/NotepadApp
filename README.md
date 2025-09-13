# NotepadApp
Simple Notepad App is a Java based text editor developed as part of the Advanced Programming Techniques course assignment in third year of my univercity life. This lightweight application provides a clean and familiar Notepad style interface while demonstrating key Java concepts such as GUI development, event driven programming, and file handling. 

A simple Java Swing Notepad application with the following features (assignment requirements):

* Edit menu → Cut, Copy, Paste
* Help menu → About dialog (contains name & ID — replace placeholders)
* (Optional) Font chooser and Color chooser for text

## Files included
* `NotepadApp.java` — main entry point
* `NotepadUI.java` — builds the Swing user interface
* `NotepadActions.java` — menu action handlers
* `LICENSE` — MIT license


## Setup Requirements
* **Java JDK 8** or later installed.
* A command-line terminal (Command Prompt / PowerShell / Terminal).

## Setup & Run (compile & run)
1. Put the three `.java` files in a single folder, e.g. `SimpleNotepadProject/src/`.
2. Open a terminal/command prompt and `cd` to that folder.
3. Compile:
```bash
javac *.java


## Assumptions / Special Notes
* This is a standalone desktop application — no database is required.
* The application provides:
* File operations (New, Open, Save)
* Edit operations (Cut, Copy, Paste)
* Help → About dialog (shows your Name & Student ID)
* Optional Font and Color choosers.
* The code is split into three main classes for clarity:
* NotepadApp – Main entry point
* NotepadUI – Builds GUI and menus
* NotepadActions – Handles user actions
