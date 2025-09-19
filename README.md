# Group-13-python-advance-cohort-28
![Tests](https://github.com/Ajayikx/Group-13-Digital-Quiz-App-python-advance-cohort-28-/actions/workflows/python-app.yml/badge.svg)

#  Digital Quiz App  

A simple digital quiz application built with **Python**.  
The app supports multiple-choice and true/false questions, with automatic scoring and test coverage using **pytest**.  


Our project aims to develop a Digital Quiz App that allows users to author, run, and analyze quizzes with multiple question types. Using object-oriented programming, we will create a base Question class with subclasses for different types, each implementing an is_correct () method for scoring. The app will provide a user-friendly GUI for quiz creation, timed quiz execution with a progress bar, and per-question feedback. Quizzes can be imported and exported as JSON, with validation to ensure correctness. Stretch goals include randomizing question order and tracking per-student histories. By the end, users will be able to create quizzes, take them, and view accurate results, demonstrating strong quiz logic, usability, and proper exception handling.
---

##  Features  

- Multiple-choice questions  
- True/False questions  
- Automatic scoring system  
- Unit tests with `pytest`  
- Dependency management with `pipenv`  
- Graphical User Interface (Tkinter)  
- Import/Export quizzes from JSON  
- Save user results and history  

---

##  Project Structure  

## Group-13-Digital-Quiz-App-python-advance-cohort-28-/
- │── quiz/
- │ └── question.py # Core question classes
- │── tests/
- │├── test_questions.py # Tests for MultipleChoiceQuestion
- │ └── test_truefalse.py # Tests for TrueFalseQuestion
- │── Pipfile # Dependency management
- │── Pipfile.lock
- │── main.py # Entry point (to be expanded with UI)
- │── README.md # Project documentation


---

##  Installation  

Make sure you have **Python 3.10+** and **pipenv** installed.  


# Clone the repo
     git clone https://github.com/Ajayikx/Group-13-Digital-Quiz-App-python-advance-cohort-28-.git
     cd Group-13-Digital-Quiz-App-python-advance-cohort-28-

# Install dependencies
     pipenv install
     
## Usage
  Run the quiz app
           pipenv run python main.py

##  Contributing

- 1.Fork the repository
- 2.Create a new branch (git checkout -b feature-name)
- 3.Commit changes (git commit -m "Add feature name")
- 4.Push to your branch (git push origin feature-name)
- 5.Open a Pull Request


Test run at Fri Sep 19 00:42:12 WCAST 2025
