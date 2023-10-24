# Movie and TV Show Management System

A Java program to store and manage information about your favorite movies and TV shows, following object-oriented programming principles.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Java program is designed to manage information about your favorite movies and TV shows. It follows object-oriented programming (OOP) principles, including encapsulation, abstraction, inheritance, polymorphism, and method/constructor overloading.

The program consists of three main classes:

1. `MotionPicture`: An abstract class representing common properties for both movies and TV shows, such as title, year, and running time.
2. `Movie`: A class that inherits from `MotionPicture` and adds properties specific to movies, including director, screenwriters, and starring actors.
3. `TVShow`: A class that inherits from `MotionPicture` and adds properties specific to TV shows, such as creator, number of episodes, and an array of episodes (which are instances of `Movie`).

## Project Structure

- `MotionPicture.java`: Defines the `MotionPicture` abstract class with common properties.
- `Movie.java`: Defines the `Movie` class, which inherits from `MotionPicture` and includes movie-specific properties.
- `TVShow.java`: Defines the `TVShow` class, which inherits from `MotionPicture` and includes TV show-specific properties.
- `Main.java`: Contains the main application, demonstrating how these classes can be used and interacting with them.
- `README.md`: The file you are currently reading, providing an overview of the project.

## How to Use

1. Clone the repository to your local machine using the following command:

   ```shell
   git clone <repository-url>
