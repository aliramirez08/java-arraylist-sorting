# Sorting ArrayList Project (Java)

This project was developed to strengthen my understanding of data structures and sorting algorithms in Java. It demonstrates how to manage Student objects using an ArrayList and implement a custom selection sort algorithm without relying on built-in sorting methods.

## Features
- Stores 10 Student objects with roll number, name, and address
- Sorts students alphabetically by name using a Comparator
- Sorts students numerically by roll number using a Comparator
- Implements a custom selection sort algorithm (no built-in sorting methods used)
- Validates input (roll number must be positive)
- Demonstrates object-oriented design and separation of concerns

## Concepts Covered
- ArrayLists
- Custom sorting algorithms (Selection Sort)
- Comparators
- Object-Oriented Programming (OOP)
- Input validation

## Project Structure
- **Student.java** — defines the Student class with validation
- **NameComparator.java** — comparator for sorting by name
- **RollnoComparator.java** — comparator for sorting by roll number
- **SelectionSorter.java** — custom selection sort implementation
- **Main.java** — entry point for execution

## How to Run
1. Open the project directory in terminal
2. Compile all files:

    ```bash
    javac *.java
    ```
3. Run the main program:
    ```bash
    java Main
    ```

## Source Code Screenshots

### Student.java Source Code
![Student.java Source Code](Screenshots/Student.png)

### NameComparator.java Source Code
![NameComparator.java Source Code](Screenshots/NameComparator.png)

### SelectionSorter.java Source Code
![SelectionSorter.java Source Code](Screenshots/SelectionSorter.png)

### RollnoComparator.java Source Code
![RollnoComparator.java Source Code](Screenshots/RollnoComparator.png)

### Main.java Source Code
![Main.java Source Code](Screenshots/Main.png)

## Program Output Screenshot

### Source Code Output
![Program Output](Screenshots/MainOutput.png)
