# Café de la Gare

**Project developed for a client**

## Description
This project was developed for the client "Café de la Gare". It is a client/server application developed in C communicating over a local area network (LAN).

## Tech Stack
- **Language**: C
- **Architecture**: Client / Server
- **Network**: Sockets, custom communication protocol (`protocol.h`)

## Installation and Launch
To compile and run the project, you will need a C compiler (e.g., GCC or MinGW on Windows).

### Launch with the script
1. Clone this repository.
2. On Windows, double-click the `run.bat` file to automatically launch the environment.

## Project Structure
```text
cafe-de-la-gare/
├── server_main.c    # Network logic and management (Server)
├── client_main.c    # Logic and display (Client)
├── protocol.h       # Packet structure definitions
├── run.bat          # Launch script for Windows
└── README.md        # Project documentation
```
