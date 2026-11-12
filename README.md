# Quiz Application

A desktop multiple-choice quiz application built in C++ with Raylib. It combines a graphical quiz flow with timed scoring and PostgreSQL result storage.

## Preview

<p align="center">
  <img src="Images/Screenshot%202026-07-03%20083802.png" width="32%" alt="Quiz screen 1" />
  <img src="Images/Screenshot%202026-07-03%20083833.png" width="32%" alt="Quiz screen 2" />
  <img src="Images/Screenshot%202026-07-03%20083927.png" width="32%" alt="Quiz results" />
</p>

## Features

- 30 multiple-choice questions.
- Randomized question order.
- Time-based scoring.
- Pause and resume.
- Student PRN input.
- Result screen with score and completion time.
- PostgreSQL integration through `libpq`.

## Scoring and Stored Results

Correct answers contribute to the score, with faster responses receiving more points. Incorrect answers reduce the score. The application stores the submitted PRN, final score, and time taken in PostgreSQL.

## Controls

| Action | Input |
|---|---|
| Navigate and select | Mouse |
| Enter PRN | Keyboard |
| Pause | Esc |
| Resume / continue | Mouse |

## Technology

- C++
- Raylib
- PostgreSQL
- `libpq`

## Build and Run

The repository includes a Windows executable and runtime libraries, but does not currently provide a portable build configuration.

To build from source, configure Raylib and PostgreSQL's `libpq` development files for your compiler, then compile the application and link the required libraries. Do not commit database credentials; use local configuration for connection details.

## License

No license file is currently included. Unless a license is added, the repository should be treated as source available for viewing, not as granting general permission to reuse or redistribute the code.
