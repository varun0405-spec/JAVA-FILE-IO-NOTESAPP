# Java File I/O - Notes App

This project is a simple text-based Notes App developed in Java.

The application allows users to add notes and view previously saved notes. The notes are stored in a text file so that the data can be persisted.

## Features

- Add a new note
- Save notes to a text file
- View saved notes
- Simple menu-based interface
- File input/output handling
- Exception handling for file operations

## Technologies Used

- Java
- VS Code
- Java File I/O
- FileWriter
- FileReader
- BufferedReader
- Scanner
- IOException

## How It Works

When a user selects **Add Note**, the application uses `FileWriter` to save the note into `notes.txt`.

When the user selects **View Notes**, the application uses `FileReader` and `BufferedReader` to read and display the saved notes.

The notes are stored using append mode so that new notes can be added without deleting the previous notes.
