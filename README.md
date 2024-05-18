# Flashy-Flashcard-Learning-App

## Overview
Flashy is a flashcard application designed to help users learn French vocabulary. The app displays French words and their English translations, allowing users to mark words they know and track their progress.

## Features
- **Random Flashcards:** Displays a random French word on the front of the card.
- **Flip Card:** Automatically flips the card after 3 seconds to show the English translation.
- **Track Learning Progress:** Users can mark words as known, and the app saves progress to `words_to_learn.csv`.
- **Responsive UI:** User-friendly interface with buttons to mark words as known or unknown.

## Technologies Used
- **Frontend:** Tkinter for the graphical user interface.
- **Backend:** Python for application logic.
- **Data Handling:** Pandas for reading and writing CSV files.

## Installation
1. Clone the repository:
   ```sh
   git clone <your-repo-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <your-project-directory>
   ```
3. Install the required dependencies:
   ```sh
   pip install pandas
   ```
4. Run the application:
   ```sh
   python main.py
   ```

## Usage
- Launch the application to start learning.
- Click the "wrong" button to skip to the next word.
- Click the "right" button to mark a word as known and remove it from the learning list.
