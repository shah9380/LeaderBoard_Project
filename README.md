# LeaderBoard_Project

A dynamic leaderboard project allowing users to add player information and track scores. The project is built using HTML, CSS, and JavaScript.

## Overview

This project showcases a leaderboard that allows users to dynamically add player details and scores, along with functionalities to sort the leaderboard based on player scores.

## Features

- **Add Players:** Enter player details like first name, last name, country, and player score. 
- **Leaderboard:** Displays the added players with their information and scores.
- **Sort Functionality:** Sorts the leaderboard based on player scores in descending order.

## Important JavaScript Functions and HTML Elements

### JavaScript Functions

#### `createacard(array)`
- **Purpose:** Creates a player card using the provided player details.
- **Elements Created:**
  - `div` for the player card.
  - `div` for the name section.
  - `div` for the country.
  - `div` for the score.
  - `div` for delete functionalities.
- **Usage:**
  - Formats and displays the player's name, country, score, and delete functionalities.
  - Appends the created card to the leaderboard.

#### `sortLeaderBoard()`
- **Purpose:** Sorts the leaderboard based on player scores.
- **Usage:**
  - Collects all player cards and their scores.
  - Uses a custom sorting algorithm to arrange the cards in descending order based on scores.
  - Rearranges the cards in the leaderboard.

#### `onContainerClick(e)`
- **Purpose:** Manages actions when a user interacts with the player cards.
- **Usage:**
  - Detects user actions such as removing a player or modifying their score.
  - Handles events triggered by delete or score modification buttons within the player cards.

### HTML Tags

#### `input`
- **Usage:** Collects player details (first name, last name, country, and score) from the user.

#### `button`
- **Usage:** Triggers the addition of a player to the leaderboard and subsequent actions such as sorting.

#### `div`
- **Usage:** Organizes the player cards and their information within the leaderboard.

## Screenshots

![image](https://github.com/shah9380/LeaderBoard_Project/assets/130676464/9dae5a16-8d64-4899-ba8c-137517da0732)


*Initial layout showcasing the leaderboard.*

![image](https://github.com/shah9380/LeaderBoard_Project/assets/130676464/7721e80d-b265-4d1a-98aa-8e88a920697a)

*New player added to the leaderboard.*

## Project Link

[Hosted Project Link](https://shah9380.github.io/LeaderBoard_Project/)

## Usage

1. Clone the repository.
2. Open `index.html` in a web browser to launch the project.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with your changes.
