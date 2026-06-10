# TimeForge

A desktop productivity application for task management, event scheduling, and user rewards.
Built with Java as a team of 4 at the University of Toronto.

## Tech Stack

- Java
- Clean Architecture
- LGoodDatePicker (date/time picker)

## Architecture

Structured into 5 decoupled layers following Clean Architecture:

- **Entity** — core domain objects
- **Use Case** — business logic
- **Interface Adapter** — bridges use cases and UI
- **Data Access** — file-based persistence via DAOs
- **View** — UI layer

Key design decisions:
- Dependency Inversion Principle via explicit input/output boundaries
- Factory pattern for object creation
- MVVM-inspired design with dedicated State objects for UI state management
- DAO-based CRUD operations across users, tasks, events, and rewards

## Features

- Personal to-do list with task creation and deletion
- Event scheduling with calendar view
- Reward system for task completion

## My Contribution

Led design and implementation of the overall architecture across 80+ Java classes.


## Contributors

Narges Movahedian Nezhad - [GitHub Profile](https://github.com/nargesmn100)

Jae Joon Han - [GitHub Profile](https://github.com/JJ-Han)

JoonsungPark - [GitHub Profile](https://github.com/UofTJoonsungPark)

Jenny Nguyen - [GitHub Profile](https://github.com/jolateral)
