# Student-Portal-Chatbot-in-C-
```
# UCP-DataScience-Semester1-Chatbot

This C++ console application serves as a basic information portal specifically designed for Data Science Semester 1 students at the University of Central Punjab (UCP).

## Features

* **Student Profiles:** Allows users to search for and view basic student profiles by entering their roll number. Profiles include a formatted ID and the student's name. Students are pre-assigned to sections DA1, DA2, or DA3.
* **Marks Display:** Enables students to view their midterm, quiz, and assignment marks for all six core subjects: ITC, BE, IDE, ENG, ITC LAB, and BE LAB. The marks are initialized with deterministic values for demonstration purposes.
* **Reminders:** Provides subject-specific reminders for each section (DA1, DA2, DA3) to help students stay organized with upcoming tasks and deadlines.
* **Final Exam Schedule:** Displays the final examination schedule for all six subjects, tailored to each section.
* **Class Schedule:** Shows the regular class schedule for all six subjects, specific to each section.
* **Interactive Menu:** Features a simple command-line interface with a numbered menu for easy navigation through the different functionalities.
* **User-Friendly Prompts:** Includes conversational prompts to enhance the user experience.

## Purpose

This project was created as a simple demonstration of how basic student information could be organized and accessed through a command-line interface. It targets the specific needs of Data Science Semester 1 students at UCP by providing quick access to relevant academic information.

## How to Run

1.  Ensure you have a C++ compiler (like g++) installed on your system.
2.  Save the provided code as a `.cpp` file (e.g., `student_portal.cpp`).
3.  Open your terminal or command prompt.
4.  Navigate to the directory where you saved the file.
5.  Compile the code using the command: `g++ student_portal.cpp -o student_portal`
6.  Run the executable with the command: `./student_portal` (on Linux/macOS) or `student_portal.exe` (on Windows).

## Limitations

* **Static Data:** All student names, section assignments, marks, reminders, schedules are hardcoded within the application. There is no external data source or database integration.
* **Deterministic Marks:** The marks are generated using a simple deterministic formula and do not represent actual student performance.
* **Limited Functionality:** This is a basic implementation and does not include features like adding/editing data, more detailed student information, or advanced search capabilities.
* **Console-Based:** The user interface is purely text-based.

## Potential Future Enhancements

* Integrate with a database or external data source to store and manage student information dynamically.
* Implement features for adding, editing, and deleting student records, marks, and schedules.
* Develop a more sophisticated user interface (e.g., a graphical user interface or a web-based application).
* Add functionality for calculating grades and generating reports.
* Incorporate user authentication and authorization.
* Make the chatbot more interactive and capable of answering more diverse questions.

