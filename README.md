# Student Record Management Using Python Classes

## 📌 Overview

This project demonstrates the use of classes and objects in Python to store and display student information. It defines a `Student` class with attributes for a student's name, roll number, and marks, and creates an object to access and display these details.

## 🚀 Features

- Demonstrates object-oriented programming (OOP) in Python.
- Uses a class to represent student information.
- Initializes object attributes using a constructor.
- Displays student details in a formatted output.
- Simple and beginner-friendly implementation.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Concepts:** Classes, Objects, Constructors, Instance Attributes
- **Platform:** Google Colab / Python IDE

## 📂 Code

```python
class Student:
    def __init__(self, name, roll, marks):
        self.name = name
        self.roll = roll
        self.marks = marks


s1 = Student("Ravi", 101, 87.5)

print("Name:", s1.name)
print("Roll:", s1.roll)
print("Marks: {:.1f}".format(s1.marks))
```

## 🧠 How It Works

1. **Define the class:** The `Student` class acts as a blueprint for creating student objects.
2. **Create the constructor:** The `__init__()` method initializes the object's attributes when a new object is created.
3. **Assign attributes:** The `self.name`, `self.roll`, and `self.marks` attributes store the student's name, roll number, and marks.
4. **Create an object:** The statement `s1 = Student("Ravi", 101, 87.5)` creates a student object with the specified details.
5. **Display information:** The `print()` statements access the object's attributes and display them.
6. **Format marks:** The `"{:.1f}".format(s1.marks)` expression displays marks up to one decimal place.

## ▶️ Example Output

```text
Name: Ravi
Roll: 101
Marks: 87.5
```

## 📖 Concepts Explained

### 1. Class
A class is a blueprint used to create objects. In this program, `Student` defines the structure of a student record.

### 2. Object
An object is an instance of a class. Here, `s1` is an object of the `Student` class.

### 3. Constructor
The `__init__()` method is called automatically when an object is created. It initializes the object's attributes.

### 4. `self` Keyword
The `self` parameter refers to the current object and allows its attributes to be accessed and initialized.

### 5. Instance Attributes
The attributes `name`, `roll`, and `marks` store information specific to each student object.

## ⚙️ How to Run

1. Clone or download this repository.
2. Open the Python file in Google Colab or a Python IDE.
3. Run the program.
4. Modify the values passed to `Student()` to display information for another student.

## 🔮 Possible Improvements

- Accept student details as user input.
- Create multiple student objects.
- Add methods to calculate grades or determine pass/fail status.
- Store and display records for multiple students.
- Validate roll numbers and marks.

## ⏱️ Complexity Analysis

- **Time Complexity:** \(O(1)\) for creating one student object and displaying a fixed number of attributes.
- **Space Complexity:** \(O(1)\) for storing one student object's attributes, assuming the attribute values have constant size.

## 👨‍💻 Author

**Vanshraj Singh**

## 📄 License

This project is intended for educational purposes and for learning the fundamentals of Python and object-oriented programming.
