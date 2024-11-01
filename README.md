# Chess Algorithm with Dobot Arms

## Overview and Goal
This project showcases a competition between two AI-powered robots playing chess against each other. Using the Stockfish chess engine for high-level gameplay, the project combines vision-based camera calibration to track moves and interpret board states in real-time. The goal is to create an engaging chess match experience where two virtual opponents, each powered by sophisticated AI, compete in a head-to-head game of strategy and skill.

---

## Robots Used
This project utilizes two **Dobot Magician** robotic arms for physically moving chess pieces on the board. These versatile robotic arms are well-suited for educational and research purposes and provide accurate and repeatable motion control, making them ideal for a chess-playing robot.

---

## Dependencies
To run this project, you’ll need the following:
- Python 3.x
- OpenCV for camera functionality (if applicable to `camera_callibration.py`)
- Stockfish Chess Engine [Download here](https://stockfishchess.org)

---

## Files
- **`camera_callibration.py`**: Manages camera calibration functions, possibly to capture and interpret board positions.
- **`main.py`**: The main script that runs the program, integrating chess engine functionality and additional features.

---

## Running the Project
To start the project:
1. Install the required dependencies:
   ```bash
   pip install opencv-python
   ```
2. Run the main script:
   ```bash
   python main.py
   ```
---
## Acknowledgments

  Special thanks to the teaching assistant for support and guidance [Hossam](https://github.com/Hossamvs)
