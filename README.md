[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/lffbZTJD)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15585739)
# Python I/O Assessment

## Assignment Overview

In this exercise, you will implement a function that generates a greeting message. Your task is to complete the `greet_user` function in the `main.py` file.

## Task Description

You need to implement the `greet_user` function to return a greeting message in the format: `Hello, <name>!`. The function should handle different cases, including when the `name` is an empty string.

### Instructions

1. **Open the Assignment in GitHub Codespaces**

   Open this repository in GitHub Codespaces by clicking the green "Code" button at the top right of this page and selecting "Open with Codespaces."

2. **Implement the Function**

   In Codespaces, open the `main.py` file and complete the `greet_user` function. Ensure that the function:
   - Takes a single argument, `name`, which is a string.
   - Returns a string in the format: `Hello, <name>!`

   For example:
   - `greet_user("Alice")` should return `"Hello, Alice!"`
   - `greet_user("")` should return `"Hello, !"`

   Here’s the skeleton code you need to complete:

   ```python
   # main.py

   def greet_user(name):
       # TODO: return a greeting string "Hello, <name>!"
       pass

   if __name__ == "__main__":
       name = input("Enter your name: ")
       print(greet_user(name))
