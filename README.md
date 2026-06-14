# Foundational C# with Microsoft Certification

A comprehensive collection of projects, exercises, guided labs, and challenge solutions completed while studying the Microsoft & freeCodeCamp Foundational C# Certification.

## Overview

This repository documents my practical journey learning C# and .NET through Microsoft's official learning path.

Rather than only completing lessons, I focused on understanding the reasoning behind each solution, debugging real problems, and improving project implementations beyond the minimum requirements.

## Skills Demonstrated

* C# Fundamentals
* Variables and Data Types
* Decision Logic
* Arrays and Collections
* Loops and Iteration
* Methods and Modular Design
* Debugging Techniques
* Exception Handling
* Console Application Development
* Problem Solving
* Algorithmic Thinking

## Repository Structure

### Module 01 — Basic Syntax

Introduction to C# syntax, variables, literals, operators, and console interaction.

### Module 02 — Decision Logic

Projects focused on:

* if / else statements
* switch expressions
* Boolean logic
* Business rule implementation

### Module 03 — Data Structures

Practice with:

* Arrays
* Iteration
* Data processing
* Sequence manipulation

### Module 04 — Methods

Building reusable and maintainable code through:

* Custom methods
* Parameters
* Return values
* Code organization

### Debugging & Exception Handling

Projects demonstrating:

* Debugging workflows
* Error diagnosis
* Exception creation and handling

## Highlight Project — Console Food Game

One of the most interesting projects in this repository is a console-based game where a player moves around the screen collecting food items.

### Features

* Real-time keyboard input
* Random food generation
* Multiple player states
* Dynamic movement speed
* Collision detection
* Terminal boundary handling
* Window resize detection

### Technical Challenge

A collision-detection bug appeared when the player's movement speed increased from 1 to 3.

The original implementation checked whether:

playerX == foodX && playerY == foodY

This failed because the player could move several positions in a single update and skip the exact food coordinate.

To solve this, collision detection was changed from point matching to range overlap detection:

playerX >= foodX &&
playerX < foodX + foods[food].Length &&
playerY == foodY

This allows food to be consumed whenever the player's position enters the food's occupied area rather than requiring an exact coordinate match.

### Concepts Practiced

* State Management
* Game Loop Design
* Collision Detection
* Console Rendering
* Procedural Game Programming

## Certification

Microsoft & freeCodeCamp Foundational C# Certification

(Certificate link will be added after completion)

## Contact

GitHub: https://github.com/Qusai-netizen

LinkedIn: [Your LinkedIn Profile]

---

Building strong programming fundamentals one project at a time.
