# Graphical-timer

A simple yet powerful Python timer with both terminal-based and graphical user interfaces (GUIs). This project includes two versions of the timer:
1. **Terminal Timer**: Built using the `curses` library for a dynamic and interactive terminal experience.
2. **Graphical Timer**: Built using `tkinter` for a user-friendly graphical interface.

Whether you need a quick countdown for productivity or a visual timer for presentations, this project has you covered!

---

## Features

### Terminal Timer (`curses`)
- **Dynamic Display**: The timer updates in real-time in the terminal.
- **Progress Bar**: Visualizes the remaining time with a progress bar.
- **Interactive**: Press `q` to quit the timer early.
- **User-Friendly**: Easy-to-follow prompts and clear output.

### Graphical Timer (`tkinter`)
- **Graphical Interface**: A clean and intuitive window-based timer.
- **User Input**: Enter the number of seconds in a text box.
- **Start Button**: Click to start the countdown.
- **Popup Notification**: Displays a "Time's up!" message when the timer finishes.

---

## Installation

### Prerequisites
- Python 3.x
- `curses` library (pre-installed on most Unix-based systems like Linux and macOS)
- `tkinter` library (pre-installed with Python on most systems)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/python-timer.git
   cd python-timer
   ```

2. Run the desired timer script:
   - For the **Terminal Timer**:
     ```bash
     python terminal_timer.py
     ```
   - For the **Graphical Timer**:
     ```bash
     python graphical_timer.py
     ```

---

## Usage

### Terminal Timer
1. Run the script:
   ```bash
   python terminal_timer.py
   ```
2. Enter the number of seconds for the timer.
3. Watch the timer count down in real-time!
4. Press `q` to quit the timer early.

### Graphical Timer
1. Run the script:
   ```bash
   python graphical_timer.py
   ```
2. Enter the number of seconds in the text box.
3. Click the "Start Timer" button.
4. A popup will notify you when the timer finishes.

---

## Screenshots

### Terminal Timer
```
Timer: 02:00
Progress: [====================]
```

### Graphical Timer
![Graphical Timer Screenshot](screenshot.png) *(Replace with an actual screenshot of your GUI timer)*

---

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Inspired by the need for a simple and customizable timer.
- Built with Python's `curses` and `tkinter` libraries.

---
