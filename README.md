# sre-github-lab
Requirement Documentation for a Student Task Tracker
# Student Task Tracker
## Overview
Students often struggle to keep track of multiple coursework deadlines, assignments, and quizzes across different courses. Tasks are scattered across WhatsApp groups, LMS, and notes, leading to missed deadlines. The Student Task Tracker aims to provide a single, simple place where students can record all coursework tasks, view pending work, and track completion to improve academic planning and reduce stress.

## Scope
- In scope: Add a coursework task with title, course name, and deadline.
- In scope: List recorded tasks sorted by deadline.
- In scope: Mark a task complete and filter by pending/completed.
- Out of scope: Fee payments and financial management.
- Out of scope: Automatic grading or LMS integration.

## Stakeholders
- Student: Primary user who records tasks and checks daily progress to avoid missing deadlines.
- Instructor: Interested in understanding student workload patterns and ensuring task clarity; may suggest task types and deadlines.
- Project maintainer: Responsible for maintaining clear, correct, and up-to-date requirements documentation and managing future changes.

## Functional requirements
- FR-01: The system shall let a student create a task with a title, course name, and due date.
- FR-02: The system shall display the student's recorded tasks with their due dates and status.
- FR-03: The system shall let a student mark a task as complete and retain its completion date.

## Nonfunctional requirements
- NFR-01: For 100 stored tasks, the task list shall appear within 2 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: All task actions shall be operable using a keyboard alone, verified against each documented task workflow.

## Acceptance criteria
- FR-01: Given the title "Read Chapter 1", course "SE", and due date "2025-10-10", saving a new task causes that title with its course and date to appear in the task list.
- FR-02: With two saved tasks "Assignment 1" and "Quiz 1", opening the task list shows both titles with their due dates in deadline order.
- FR-03: Marking an incomplete task "Lab 1" as complete changes its displayed status to Complete and shows the completion timestamp.

## Assumptions and open questions
- Assumption A-01: Students have access to a laptop with a modern browser and internet for viewing documentation.
- Question Q-01: Should the system support recurring tasks or only one-time coursework tasks?
- Question Q-02: Which device and environment will test NFR-01? Will it be a mid-range laptop with 8GB RAM on Chrome?

## Project status and viewing
Documentation only. Application implementation has not started.
Clone this repository and open README.md in a Markdown viewer, or read the rendered file on GitHub.
```bash
________