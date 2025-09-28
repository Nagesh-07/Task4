# Task4
NotesManager



📒 Notes Manager (Java – FileWriter & BufferedReader):-

A simple text-based Notes Manager written in Java that demonstrates how to read and write data to files using FileWriter and BufferedReader.
It lets you add notes, save them to a file, and view all saved notes in the console.

✨ Features:-

➕ Add Notes: Enter any text and save it to notes.txt.

📂 View Notes: Reads each line from the file and displays it with numbering.

📝 Persistent Storage: All notes are stored in notes.txt, so they remain even after the program is closed.

🖥️ Console-based Menu: Simple menu-driven interface for easy navigation.

💾 Uses Core Java I/O Classes: Demonstrates FileWriter, FileReader, and BufferedReader instead of advanced libraries.


🛠️ How It Works:-

Adding a Note:

Uses FileWriter in append mode to add new text lines to notes.txt.

Each note is stored on a new line.

Viewing Notes:

Uses BufferedReader with FileReader to read the file line by line.

Displays each note with a serial number.

File Handling:

If notes.txt does not exist, it is automatically created when you save the first note.
