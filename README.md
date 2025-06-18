# E-Learning System: A C++ Virtual Classroom

Welcome to the **E-Learning System**, a console-based C++ application that creates a dynamic virtual learning environment. This project, built with object-oriented programming (OOP) principles, enables students to enroll in courses, submit assignments & quizzes, and track progress, while instructors manage courses and evaluate performance. 

## Description

The E-Learning System is a C++ platform that simulates a virtual classroom. Students can enroll in courses, access materials, submit quizzes and assignments, and view grades. Instructors can create courses, add content, and assign marks. This project demonstrates OOP concepts, modular design, and efficient data management, making it an engaging tool for learning and teaching.

## Key Features

- **User Roles**: Distinct dashboards for students and instructors.
- **Course Management**: Instructors create courses and add materials, assignments, and quizzes.
- **Student Interaction**: Enroll, submit answers, and view marks.
- **Marks Tracking**: Instructors assign marks; students access performance details.
- **Console Interface**: Intuitive, menu-driven navigation.
- **Data Management**: Uses vectors and maps for dynamic storage.
- **Secure Login**: Email and password authentication.

## System Overview

The system is built around classes like `User`, `Course`, `Student`, `Instructor`, `Assignment`, `Quiz`, and `Material`. Key components include:

1. **Authentication**: Users register or log in as students or instructors.
2. **Student Dashboard**: Enroll in courses, view materials, submit answers, and check marks.
3. **Instructor Dashboard**: Create courses, add content, review submissions, and assign marks.
4. **Course Structure**: Courses contain materials, assignments, and quizzes.
5. **Marks System**: Tracks student performance per course.

Global vectors (`students`, `instructors`, `courses`) and menu functions (`studentPanel`, `instructorPanel`) drive the interactive experience.

## OOP Concepts

The project leverages core OOP principles:

- **Encapsulation**: Protects data (e.g., `name`, `email`) with public getters.
- **Inheritance**: `User` base class extended by `Student` and `Instructor`.
- **Polymorphism**: Virtual functions (`displayDashboard`, `viewMarks`) tailored for each role.
- **Abstraction**: `User` class hides implementation details.
- **Composition**: `Course` contains `Material`, `Assignment`, and `Quiz` objects.
- **Friendship**: `Instructor` accesses `Student` data for marking.

These principles ensure modular, maintainable, and scalable code.

## Future Enhancements

Potential improvements include:

- **File Storage**: Persist data to files.
- **GUI Interface**: Replace console with a graphical UI (e.g., Qt).
- **Enhanced Security**: Add password hashing.
- **Grading Rubrics**: Define custom grading criteria.
- **Discussion Forums**: Enable user interaction.
- **Analytics**: Visualize performance with charts.

These additions could elevate the system to compete with modern learning platforms.

## Learning Outcomes

This project delivered valuable insights:

- **OOP Mastery**: Applied inheritance, polymorphism, and encapsulation.
- **C++ Skills**: Enhanced proficiency with vectors, maps, and pointers.
- **System Design**: Built a modular, scalable application.
- **Problem-Solving**: Addressed challenges like input validation and data management.
- **Project Management**: Planned and documented a complex system.

This experience strengthened my ability to create impactful software solutions.

## Get Involved

Explore the code, suggest improvements, or contribute! Star the repo, report issues, or submit pull requests to enhance this educational tool.

