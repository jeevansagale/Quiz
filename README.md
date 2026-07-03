# Quiz Application

A desktop quiz application built in **C++** using **Raylib** with **PostgreSQL (Supabase)** integration for storing quiz results.

The project was developed as a learning experience in GUI programming, state management, database connectivity, and game/application development using C++.

## Preview

<p align="center">
  <img src="Images/Screenshot%202026-07-03%20083802.png" width="48%">
  <img src="Images/Screenshot%202026-07-03%20083814.png" width="48%">
</p>

<p align="center">
  <img src="Images/Screenshot%202026-07-03%20083833.png" width="48%">
  <img src="Images/Screenshot%202026-07-03%20083845.png" width="48%">
</p>

<p align="center">
  <img src="Images/Screenshot%202026-07-03%20083927.png" width="70%">
</p>

*Screenshots of the quiz interface, gameplay, and result screens.*

---

## Features

* Interactive graphical interface using Raylib
* 30 multiple-choice questions
* Randomized question order
* Timer-based scoring system
* Dynamic score calculation
* Pause & Resume functionality
* Credits screen
* PRN (Student ID) input
* Result screen displaying score and completion time
* PostgreSQL (Supabase) database integration
* Automatic result storage

---

## Scoring System

The application rewards quick and accurate answers.

* Correct answers earn points based on response time.
* Faster responses receive higher scores.
* Incorrect answers reduce the score.
* Total completion time is recorded and displayed after finishing the quiz.

---

## Database Integration

Quiz results are automatically stored in a PostgreSQL database using **libpq**.

Each submission records:

* Student PRN
* Final Score
* Time Taken

---

## Controls

| Action        | Input             |
| ------------- | ----------------- |
| Navigate UI   | Mouse             |
| Select Answer | Left Mouse Button |
| Continue      | Mouse             |
| Pause         | Esc               |
| Resume        | Mouse             |
| Enter PRN     | Keyboard          |

---

## Tech Stack

| Component        | Technology            |
| ---------------- | --------------------- |
| Language         | C++                   |
| Graphics Library | Raylib                |
| Database         | PostgreSQL (Supabase) |
| Database Driver  | libpq                 |
| Platform         | Windows               |

---

## Project Structure

```text
Quiz/
│
├── Images/
├── Assets/
├── main.cpp
└── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/jeevansagale/Quiz.git
```

### Requirements

* Visual Studio 2022
* Raylib
* PostgreSQL libpq library
* C++17 or newer

### Build

Open the project in Visual Studio, configure Raylib and libpq, then build and run.

---

## Learning Objectives

This project was built to gain practical experience with:

* Modern C++
* GUI programming
* Event-driven applications
* State management
* Timer systems
* Randomization
* Database connectivity
* PostgreSQL integration
* User input handling
* File and data management

---

## Future Improvements

* User authentication
* Difficulty levels
* Question categories
* Leaderboard
* Timer per question
* Better UI animations
* Online multiplayer quiz
* Admin panel for managing questions
* Secure database credentials using environment variables
* Question loading from external JSON or database

---

## Roadmap

* [x] GUI
* [x] Question system
* [x] Random question order
* [x] Timer
* [x] Score calculation
* [x] PRN input
* [x] Pause system
* [x] Result screen
* [x] PostgreSQL integration
* [ ] Leaderboard
* [ ] Question editor
* [ ] Categories
* [ ] Improved UI

---

## Contributing

Contributions, suggestions, and feedback are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

---

## License

This project is licensed under the MIT License.

---

## Author

**Jeevan Sagale**

GitHub: https://github.com/jeevansagale
