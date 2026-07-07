# Chess-Version (Work in Progress)

A Java implementation of chess built from scratch as a learning project. The goal of this project is not only to recreate the rules of chess, but also to design a clean and maintainable architecture that separates piece movement from game logic.


---

## Goals

* Build a complete chess game from scratch in Java.
* Practice object-oriented programming and software design.
* Implement chess rules without relying on external chess libraries.
* Extend the game in the future with custom gameplay mechanics.

---

## Current Features

* Chess board representation
* Individual classes for chess pieces
* Pseudo-legal move generation
* Object-oriented project structure

---

## Planned Features

* Complete move generation for every piece
* Legal move validation
* Check detection
* Checkmate and stalemate detection
* Castling
* En passant
* Pawn promotion
* Game state management
* Graphical user interface

---

## Future Expansion: SuperUps

Once the standard version of chess is complete, the project will be expanded into a custom chess variant called **SuperUps**.

The idea is to randomly generate special squares on the board that grant strategic abilities, such as:

* Freezing the opponent's next turn
* Revealing an engine-recommended move as a hint
* Other unique power-ups designed to create new tactical possibilities

This feature is intended as a creative extension after the core chess implementation is finished.

---

## Project Structure

The project follows a layered design:

* **Piece classes** are responsible for generating pseudo-legal movement based on each piece's movement rules.
* **Game logic** validates moves according to the rules of chess.
* **Board state** is used to determine legal movement, captures, and check detection.

Keeping these responsibilities separate makes the code easier to maintain and extend.

---

## Technologies

* Java
* Object-Oriented Programming
* Git

---

## Project Status

This project is still a work in progress and is being developed as a learning exercise. New features and improvements will continue to be added over time.

---

