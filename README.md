# Student Program Transfer Planner

## Project Description

This project is a simple web application created for the Introduction to Artificial Intelligence midterm exam.

The goal of the application is to help a student plan a transfer from one academic program to another. The application shows the student's current courses and checks which passed courses may be equivalent to courses in the selected target program.

## Current Program

My current academic program is:

**Computer Engineering**

## Available Target Programs

The user can select one of the following target programs:

- Civil Engineering
- Electrical and Electronics Engineering
- Computer Science

The current program, Computer Engineering, is not included in the dropdown because the user is transferring to another program.

## Technologies Used

The project uses only:

- HTML
- CSS
- JavaScript

All CSS and JavaScript are embedded inside one single HTML file.

## Files in This Repository

| File Name | Description |
|---|---|
| `index.html` | Main web application file |
| `README.md` | Project documentation |

## Course Display

When the page loads, the application automatically displays a table with two columns:

| Column | Meaning |
|---|---|
| Course | The course name |
| Passed | Shows whether the course was passed or not |

Courses marked as `Yes` are completed courses.

Courses marked as `No` are either failed courses, not completed yet, or currently in progress.

## Equivalency Algorithm

The equivalency algorithm is based on simple rule-based logic.

First, the application stores all courses in a JavaScript array. Each course has two values:

```js
{
  course: "Course Name",
  passed: "Yes"
}
