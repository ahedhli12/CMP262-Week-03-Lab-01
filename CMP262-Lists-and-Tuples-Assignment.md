# CMP 262 – Data Science Programming

## Week 3 – Lab 1: Python Lists and Tuples

**Due:**  
**Points: 100**

## Purpose

This lab gives you hands-on practice with Python **lists** and **tuples**. You will create collections, access and modify values, use common methods and functions, loop through collections, work with slices, and compare mutable and immutable data structures.

Complete all work in the Jupyter Notebook provided in this repository:

`ListsAndTuples.ipynb`

Add a **Markdown heading before each part** and complete each requirement in your own code.

---

## Part 1 – Creating Lists and Accessing Values

Create a list named `courses` that contains at least **six course names**.

Display:

- The entire list
- The first item
- The third item
- The last item using negative indexing
- The second-to-last item using negative indexing
- The number of items using `len()`

Then use list slicing to display:

- The first three items
- Items from index 2 through index 4
- The last three items

**Points: 15**

---

## Part 2 – Modifying Lists and List Methods

Create a list named `favorite_foods` containing at least **five foods**.

Complete all of the following:

1. Display the original list.
2. Change one existing item using its index.
3. Add one item using `append()`.
4. Add one item at a specific position using `insert()`.
5. Remove one item using `remove()`.
6. Remove one item using `pop()` and display the removed value.
7. Display the number of times one selected item appears using `count()`.
8. Display the index of one selected item using `index()`.
9. Display the final list.

**Points: 15**

---

## Part 3 – Sorting, Reversing, and Membership

Create a list named `cities` containing at least **six city names**.

Complete the following:

- Display the original list.
- Sort the list alphabetically using `sort()` and display it.
- Reverse the list using `reverse()` and display it.
- Use the `in` operator to check whether one city is in the list.
- Use the `not in` operator to check whether another city is not in the list.

Write a short Markdown sentence explaining what the `in` operator does.

**Points: 10**

---

## Part 4 – Numeric Lists and Built-In Functions

Create a list named `scores` containing at least **eight numeric values**.

Display:

- The entire list
- The highest value using `max()`
- The lowest value using `min()`
- The total using `sum()`
- The number of values using `len()`
- The average using `sum(scores) / len(scores)`

Then add one new score and display the new average.

**Points: 15**

---

## Part 5 – Looping Through Lists

Create a list named `programming_languages` containing at least **five programming languages**.

Complete the following:

1. Use a `for` loop to display every language on a separate line.
2. Use a second `for` loop to display a short message containing each language.
3. Create a numeric list containing at least six numbers.
4. Use a loop to display only the values that are greater than a number you choose.

Do not manually print each individual list item.

**Points: 15**

---

## Part 6 – Creating and Accessing Tuples

Create a tuple named `student_record` containing:

- Student name
- Major
- Graduation year
- GPA

Display:

- The entire tuple
- The first value
- The major
- The last value using negative indexing
- The number of values using `len()`
- A slice containing the first two values

Then use the `in` operator to check whether the student's major appears in the tuple.

**Points: 10**

---

## Part 7 – Tuple Packing and Unpacking

Create a tuple named `location` containing three values:

- City
- State
- ZIP code

Unpack the tuple into three separate variables.

Display each variable separately.

Then create another tuple with at least four values and unpack it into four variables.

**Points: 10**

---

## Part 8 – Converting Between Lists and Tuples

Create a list containing at least four values.

Complete the following:

1. Convert the list to a tuple using `tuple()`.
2. Display the tuple.
3. Convert the tuple back to a list using `list()`.
4. Display the new list.
5. Modify the new list to demonstrate that lists are mutable.

**Points: 5**

---

## Part 9 – Lists vs. Tuples Review

In a **Markdown cell**, answer each question in your own words.

1. What is a list?
2. What is a tuple?
3. What is one similarity between lists and tuples?
4. What is the main difference between a list and a tuple?
5. What does **mutable** mean?
6. What does **immutable** mean?
7. Which data structure is mutable?
8. Which data structure is immutable?
9. Why might a programmer choose a tuple instead of a list?
10. Give one real-world example where a list would make sense and one where a tuple would make sense.

**Points: 5**

---

## Before You Submit

Make sure that:

- Every required part is complete.
- Every part has a Markdown heading.
- All notebook cells have been run.
- All required output is visible.
- There are no Python errors.
- Your notebook is saved as `ListsAndTuples.ipynb`.
- You completed `AI-Use-Report.md` honestly.
- Your latest work has been committed and pushed to GitHub.

## Submission

Submit the link to **your own completed GitHub repository** through Blackboard Ultra.

## Important

- Write your own code.
- Use clear variable names.
- Test each section before moving to the next one.
- You should be able to explain every line of code you submit.
- Follow the rules in `AI-Use-Policy.md`.

## Grading Summary

| Section | Points |
|---|---:|
| Creating Lists and Accessing Values | 15 |
| Modifying Lists and List Methods | 15 |
| Sorting, Reversing, and Membership | 10 |
| Numeric Lists and Built-In Functions | 15 |
| Looping Through Lists | 15 |
| Creating and Accessing Tuples | 10 |
| Tuple Packing and Unpacking | 10 |
| Converting Lists and Tuples | 5 |
| Lists vs. Tuples Review | 5 |
| **Total** | **100** |
