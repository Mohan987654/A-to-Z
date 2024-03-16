Title: chess-using-django

Description:
This project aims to create a web-based interface for playing chess against an AI engine implemented in Python. The interface provides a user-friendly way to interact with the chessboard, make moves, and receive moves from the AI opponent.

Team Members:
1.Mohan Sai pappuru

2.Vishnu Vardhan pitla

3.Pushpa latha akkireddy

4.Anjani devi thammineni

The Problem it Solves:

Lack of accessible and user-friendly interfaces for playing chess against computer opponents.
Difficulty in integrating chess engine logic with web applications.
Limited options for customizable chess AI opponents.

Use Cases:

Player vs. AI: Users can play against the built-in chess engine at various difficulty levels.
Learning: Users can use the interface to practice chess tactics and strategies against the AI opponent.


Challenges Encountered:

Integration of Chess Engine: Incorporating the complex logic of the chess engine into a web application while maintaining performance.
Real-Time Updates: Ensuring real-time updates of the game state between the frontend and backend.
User Interface Design: Designing an intuitive and responsive user interface for the chessboard and game controls.



Technologies Used:

Flask: For building the backend server to handle HTTP requests.
Python-Chess: For implementing the chess engine logic and game mechanics.
Chessboard.js: For rendering the interactive chessboard on the frontend.
Chess.js: For client-side chess move validation and game state management.
HTML/CSS/JavaScript: For building the frontend interface and user interaction.


Architecture Diagram:

    [Frontend] <----HTTP Requests----> [Flask Backend] <----> [Python-Chess Engine]
              <----WebSocket----> (Real-Time Updates)

The frontend communicates with the Flask backend via HTTP requests to fetch moves, update the game state, and display the chessboard. Real-time updates are facilitated through WebSocket connections to ensure immediate feedback on moves made by either player.


Flowchart:

+---------------------+                  +---------------------+
|      Frontend       |                  |      Flask          |
|    (Chessboard)     |    HTTP Requests |      Backend        |
+----------+----------+                  +----------+----------+
           |                                          |
           |               Update Game State           |
           +------------------------------------------>|
           |                                          |
           |              Receive Move Request        |
           |<------------------------------------------+
           |               Send Move Response         |
           +----------------------------------------->|

This flowchart illustrates the interaction between the frontend chessboard component and the Flask backend. The frontend sends HTTP requests to the backend to update the game state and receive moves from the AI opponent. The backend processes the requests, communicates with the chess engine, and sends move responses back to the frontend.

-> run code through command promt.

                    
