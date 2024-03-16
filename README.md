Title: chess-using-django

Description:
This project aims to create a web-based interface for playing chess against an AI engine implemented in Python. The interface provides a user-friendly way to interact with the chessboard, make moves, and receive moves from the AI opponent.

Team Members:
1.Mohan Sai pappuru  9921004538@klu.ac.in
 
2.Vishnu Vardhan pitla  99210041774@klu.ac.in

3.Pushpa latha akkireddy 9921011052@klu.ac.in

4.Anjani devi thammineni  9921011045@klu.ac.in

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


images

![3d03f18b-0ff5-4c75-9739-48bab4bcb7bb](https://github.com/Mohan987654/A-to-Z/assets/163646122/f487f872-caa4-4d03-9c3c-a72da893b334)
![5cbe46bd-6de1-42e1-9bd4-a84724440333](https://github.com/Mohan987654/A-to-Z/assets/163646122/70c4f5c6-9dba-4823-b149-be908ccc5836)
![01879795-b448-4656-a7ea-2c391a145c4d](https://github.com/Mohan987654/A-to-Z/assets/163646122/c3131045-c417-4932-9a47-fa975c72d8db)

-> run code through command promt.

                    
