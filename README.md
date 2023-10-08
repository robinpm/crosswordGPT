# Crossword Puzzle Generator

A dynamic crossword puzzle generator built with a Flask backend and a TypeScript frontend, powered by a Language Learning Model (LLM) engine for creating engaging and educational puzzles.

## Features

- Generate unique crossword puzzles using the LLM engine
- Flask backend for handling requests and serving dynamically generated puzzles
- TypeScript frontend for an interactive user experience
- Customizable puzzle difficulty and themes

## Installation

### Backend

1. Navigate to the `backend` directory.
2. Create a virtual environment:
   ```sh
   python -m venv env
   ```
3. Activate the virtual environment:
   - On Windows:
     ```sh
     .\env\Scripts\activate
     ```
   - On Unix or MacOS:
     ```sh
     source env/bin/activate
     ```
4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
5. Run the Flask app:
   ```sh
   python run.py
   ```

### Frontend

1. Navigate to the `frontend` directory.
2. Install the required packages:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

## Usage

- Open your browser and navigate to `http://localhost:3000` to access the frontend.
- Generate new crossword puzzles by selecting your preferences and clicking the "Generate" button.
- Download or print the puzzles for offline use.

## Customizing Puzzles

- Adjust the difficulty level, grid size, and themes to create customized crossword puzzles.
- The LLM engine ensures a variety of word combinations and clues for a unique experience each time.

## Contributing

1. Fork the repository.
2. Create a new branch for your features or bug fixes.
3. Commit your changes and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.