# 🐍 Python Data Structures & Conditional Statements

## 📌 Project Title

**Python Assignment 2 – Data Structures: List, Dictionary, Set & Conditional Statements**

---

## 📖 Project Overview

This project is part of the **Data Analytics (DA) – Module 4** Python assignment.

The purpose of this assignment is to develop a practical understanding of Python's fundamental data structures and decision-making statements.

The project covers **Lists, Dictionaries, Sets, and Conditional Statements**, along with common operations used to create, modify, access, and process data.

---

## 🎯 Objectives

The main objectives of this assignment are:

- Understand Python Lists and their operations.
- Create, modify, and access list elements.
- Perform indexing and slicing operations.
- Work with Dictionaries using key-value pairs.
- Add and update dictionary elements.
- Access dictionary keys, values, and items.
- Understand Sets and their uniqueness property.
- Perform Set Union and Intersection operations.
- Understand why Sets do not support indexing.
- Implement conditional statements using `if`, `elif`, and `else`.
- Process user input using Python.

---

# 📋 Tasks Performed

## 1. Lists – Creation, Modification & Access

### List Creation

Created two lists containing age and name values.

```python
age_list = [24, 25, 27, 28, 29]

name_list = ["Arun", "Bala", "Divya", "Kavya", "Meena"]

print("Age List:", age_list)

print("Name List:", name_list)


List Operations / Modifications
The following operations were performed on the age_list and name_list.

Append
Added "Yazhini" to the name_list.

name_list.append("Yazhini")
print("After append:", name_list)

Insert
Inserted the age 26 at index 2 in the age_list.

age_list.insert(2, 26)
print("After inserting 26:", age_list)

Remove
Removed "Yazhini" from the name_list.

name_list.remove("Yazhini")
print("After removing Yazhini:", name_list)

Pop
Removed the last element from the age_list using pop().

age_list.pop()
print("After popping last element:", age_list)

Extend
Added additional ages [31, 30, 32] to the age_list.

age_list.extend([31, 30, 32])
print("After extending:", age_list)

Sort
Sorted the age_list in descending order.

age_list.sort(reverse=True)
print("Descending order:", age_list)

Maximum, Minimum and Sum
Calculated the maximum age, minimum age, and total sum of all ages.

print("Maximum age:", max(age_list))
print("Minimum age:", min(age_list))
print("Sum of ages:", sum(age_list))

Accessing List Elements
Different methods were used to access elements from the name_list.

print("First element:", name_list[0])

print("Last element:", name_list[-1])

print("Elements from index 2 to 4:", name_list[2:5])

print("Reverse order:", name_list[::-1])

📚 2. Dictionaries – Creation, Modification & Access
A dictionary named student_marks was created to store student names and their marks using key-value pairs.

Dictionary Creation
student_marks = {
    "Arun": 75,
    "Bala": 68,
    "Divya": 90,
    "Kavya": 78,
    "Meena": 85
}

Accessing a Student's Mark
The mark of a specific student was accessed using the student's name as the key.

print("Divya's mark:", student_marks["Divya"])

Adding a New Student
Added "Janani" with a mark of 80.

student_marks["Janani"] = 80

Updating a Student's Mark
Updated Bala's mark to 82.

student_marks["Bala"] = 82

Dictionary Methods
The keys(), values(), and items() methods were used to display the contents of the dictionary.

print("Keys:", student_marks.keys())

print("Values:", student_marks.values())

print("Items:", student_marks.items())

🔤 3. Sets – Operations
Sets were used to understand unique elements and set operations such as Union and Intersection.

Creating a Set
A set named my_set was created using vowels with duplicate values.

my_set = {'a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'}

print("my_set:", my_set)

Set Output
{'a', 'e', 'i', 'o', 'u'}

The duplicate values are automatically removed because sets contain only unique elements.

The order of elements may vary because sets are unordered collections.

Accessing Set Elements
An attempt was made to access an element using an index.

try:
    print(my_set[4])
except TypeError:
    print("Error: Sets do not support indexing.")

Explanation
Sets do not support indexing because they are unordered collections. Therefore, attempting to access my_set[4] results in a TypeError.

Union and Intersection
Two sets were created:

set1 = {1, 3, 5, 7, 9}

set2 = {2, 3, 5, 8, 10}

Union
The Union contains all unique elements from both sets.

union_set = set1.union(set2)

print("Union:", union_set)

Output:

{1, 2, 3, 5, 7, 8, 9, 10}

Intersection
The Intersection contains the elements that are common to both sets.

intersection_set = set1.intersection(set2)

print("Intersection:", intersection_set)

Output:

{3, 5}

🔀 4. Conditional Statements – IF, ELIF & ELSE
A performance category program was created using conditional statements.

The user enters a score between 0 and 10.

Performance Criteria
Score	Performance Category
Greater than 7	Above Average
4 to 7	Average
Less than 4	Below Average

Python Code
score = float(input("Enter your score (0 to 10): "))

if score < 0 or score > 10:
    print("Invalid score. Please enter a score between 0 and 10.")

elif score > 7:
    print("Above Average: Excellent performance! Keep up the great work.")

elif score >= 4:
    print("Average: Good effort! Keep practicing, there's room for improvement.")

else:
    print("Below Average: Need to improve your performance; consistent practice will lead to better results.")

Sample Output
Enter your score (0 to 10): 7

Average: Good effort! Keep practicing, there's room for improvement.

📊 Final Results
The assignment successfully demonstrates the following Python concepts:

Concept	Status
List Creation	✅ Completed
List Modification	✅ Completed
List Indexing & Slicing	✅ Completed
Dictionary Creation	✅ Completed
Dictionary Modification	✅ Completed
Dictionary keys()	✅ Completed
Dictionary values()	✅ Completed
Dictionary items()	✅ Completed
Set Creation	✅ Completed
Set Uniqueness	✅ Completed
Set Indexing	✅ Completed
Set Union	✅ Completed
Set Intersection	✅ Completed
if Statement	✅ Completed
elif Statement	✅ Completed
else Statement	✅ Completed
User Input	✅ Completed

✅ Conclusion
This assignment provided practical experience with Python's fundamental data structures and conditional statements.

The programs demonstrate how to create, modify, access, and process data using Lists, Dictionaries, and Sets. The assignment also demonstrates decision-making using if, elif, and else statements along with user input.

🛠️ Technologies Used
Python
Google Colab
GitHub

📁 Project File
The complete Python assignment is available in the Google colab (.ipynb) file included in this repository.

👩‍💻 Author

Maathangi

Aspiring Data Analyst

Skills:
SQL • Excel • Power BI • Power Query • Python 

Connect With Me

🔗 GitHub:
https://github.com/Maathangi1412

🔗 LinkedIn:
https://www.linkedin.com/in/maathangip

