# Pomodoro Timer

This is a simple **Pomodoro Timer** application built using Python's `tkinter` library. The Pomodoro technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. This tool helps to structure work sessions and breaks effectively, boosting productivity and maintaining focus.

## Features

- **Work Intervals**: Set to 25 minutes by default.
- **Breaks**: Alternates between 5-minute short breaks and a 20-minute long break after every four work sessions.
- **Visual Indicators**: The interface color and label text change to indicate whether it’s a work session or break time.
- **Progress Tracking**: A checkmark appears at the bottom for each completed work session, giving a visual representation of progress.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/pomodoro-timer.git
    cd pomodoro-timer
    ```

2. **Install Dependencies**:
    This project uses the `tkinter` library, which is included in Python’s standard library. Just make sure you have Python 3.x installed.

3. **Download the `tomato.png` Image**:
    Place an image file named `tomato.png` in the same directory as the code file. This image serves as a background for the timer on the main interface.

## Usage

1. **Run the Program**:
    Execute the script by running:
    ```bash
    python pomodoro_timer.py
    ```

2. **Using the Timer**:
    - Click **Start** to initiate a work session.
    - The timer will count down from 25 minutes by default. 
    - After each work session, a short or long break will automatically start based on the cycle count.
    - Click **Reset** at any time to reset the timer and start over.

## Code Overview

### Constants
- Defines colors, font settings, and the duration for each work, short break, and long break interval.

### Timer Functions
- **`reset_timer()`**: Stops the current countdown, resets the timer display and clears the progress checkmarks.
- **`start_timer()`**: Determines the current phase (work or break) based on the cycle count and starts the appropriate countdown.
- **`count_down(count)`**: Handles the countdown for each session, updating the timer display every second.

### UI Setup
- Uses `tkinter` to create the GUI, including labels, buttons, and a canvas to display the timer.

## Screenshots

Include a screenshot of the main interface here to provide users with a preview.

## Contributing

Feel free to open issues, create pull requests, or fork the repository for further improvements. Contributions are welcome!
