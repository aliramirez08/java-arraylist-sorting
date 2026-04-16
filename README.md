## Java ArrayList Sorting

This project was developed to strengthen my understanding of data structures and sorting algorithms in Java. It demonstrates how to manage Student objects using an ArrayList and implement a custom selection sort algorithm without relying on built-in sorting methods. Selection sort was implemented to demonstrate understanding of sorting logic without relying on built-in Java methods.

## Features
- Stores 10 Student objects with roll number, name, and address
- Sorts students alphabetically by name using a Comparator
- Sorts students numerically by roll number using a Comparator
- Implements a custom selection sort algorithm (no built-in sorting methods used)
- Validates input (roll number must be positive)
- Demonstrates object-oriented design and separation of concerns

## Concepts Demonstrated
- ArrayLists
- Custom sorting algorithms (Selection Sort)
- Comparators
- Object-Oriented Programming (OOP)
- Input validation

## Technologies Used
- Java
- JDK 11+

## Project Structure
- `Student.java` – Student class definition
- `NameComparator.java` – Sort by name
- `RollnoComparator.java` – Sort by roll number
- `SelectionSorter.java` – Custom sorting algorithm
- `Main.java` – Program entry point

## How to Run

### Prerequisites
- Java Development Kit (JDK 11+)

### Steps
1. Clone or download the repository
2. Navigate to the project directory
3. Compile all Java files:
```bash
javac *.java
```
4. Run the main program:
```bash
java Main
```

## Example

```text
Before Sorting:
[John, Roll: 3]
[Alice, Roll: 1]

After Sorting by Name:
[Alice, Roll: 1]
[John, Roll: 3]
```

## What I Learned
This project strengthened my understanding of how sorting algorithms work internally. Implementing selection sort manually helped me understand how data is compared and rearranged step by step.

## Future Improvements
- Add more sorting algorithms (Bubble Sort, Merge Sort)
- Improve performance for larger datasets
- Add user input for dynamic data
  
## Screenshots

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

### Source Code Output
![Program Output](Screenshots/MainOutput.png)
