# Deadline – Academic Workload Planner

## 1. Project Overview

Deadline is a web application designed to help college students organize assignments and manage their academic workload. Traditional calendars and to-do lists show students what needs to be completed but don't help them determine how to distribute their workload effectively.

Deadline aims to solve this problem by automatically generating personalized study schedules based on assignment deadlines, estimated workload, and available study time.

## 2. Minimum Viable Product (MVP)

The first version of Deadline will focus on three main features:

1. **Assignment Management:** Users can add, edit, and delete assignments with course names, due dates, estimated completion times, and priority levels.
2. **Automatic Study Scheduling:** The application generates a study schedule by calculating assignment priorities and distributing work across available days.
3. **Progress Tracking:** Users can mark assignments as completed or modify them. The application will automatically update the study schedule when changes occur.

The goal is to build a functional application that allows students to manage their assignments and receive an organized study plan.

## 3. Eisenhower Matrix

The following matrix organizes potential features based on their importance and urgency.

![Deadline Eisenhower Matrix](Docs/DeadLine_MVP.pdf)

## 4. System Diagram

The following flowchart illustrates how the major components of Deadline interact and how information moves through the application.

![Deadline System Diagram](docs/Deadline(FlowChart).jpg)

## 5. Tech Stack

The application will use the following languages, libraries, and tools:

- **HTML:**
- **CSS:**
- **JavaScript:**
- **Chart.js:** Generates visual representations of workload
- **LocalStorage:** Stores assignments and scheduling preferences in the browser using JSON.

The MVP will not require a backend, database, or external APIs. Users will manually enter their assignments and scheduling preferences.

## 6. Future Plans (Version 2.0+)

After completing the MVP, I plan to explore additional features that could make Deadline more useful.

- **Google Calendar Integration:** Allow users to import assignments and export generated study sessions to their calendars.
- **Recurring Assignments:** Support repeating assignments such as weekly homework and quizzes.
- **Workload Analytics:** Display charts showing study hours, assignment completion rates, and workload distribution.
- **Customizable Availability:** Allow users to specify which days and times they prefer to study and how many hours they can dedicate each day.

These features will be considered after the core scheduling functionality is complete.

## 7. Project Milestones

The project will be developed through the following milestones:

1. Set up the project structure, create the initial dashboard layout, and navigation.
2. Allow users to add, edit, and delete assignments with course names, due dates, estimated hours, and priority levels.
3. Implement data storage using LocalStorage
4. Develop the scheduling algorithm 
5. Generate a personalized study schedule that distributes assignments across available days while respecting study limits.
6. Add assignment completion tracking and auto-recalculate the schedule whenever assignments are completed/modified
7. Polish dashboard and user interface
8. Test and finalize

## 8. Project Goal

The ultimate goal of Deadline is to help students spend less time figuring out what to work on and more time actually getting their work done. By automatically organizing assignments into manageable study sessions, Deadline aims to make academic workload management easier and more efficient.