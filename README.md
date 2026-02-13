# The Game

A multiplayer card game made in **C++20**, featuring a graphical interface built with SFML + TGUI and a REST backend server built with **Crow** and **SQLite**.

## Features

- Graphical user interface built with SFML + TGUI.
- Client-server architecture.
- User authentication and sessions.
- Lobby system with matchmaking.
- Persistent storage with **SQLite**.
- Modern C++ 20 codebase (modules, move semantics, smart pointers, etc).

## Tech Stack

### Client
- **C++20**
- **SFML** (graphics, audio, windowing)
- **TGUI** (GUI library for SFML)

### Server
- **C++20**
- **Crow**
- **SQLite**
- **SQLite ORM**

## Dependencies

To run the solution, the following configuration steps are required:
- Update IP Address: Replace the IP address in main.cpp(Server), main.cpp(HTTPClient), and RegisterWindow.cpp(HTTPClient) with your local machine's IP.
- External Dependencies: Update the "Include Directories" and "Library Reference" paths in the HTTPClient project properties (C/C++ and Linker) to point to your local "third party mc" folder location.

### Required libraries

- SFML 
- TGUI
- Crow
- SQLite
- SQLite ORM | C++ ORM for SQLite
