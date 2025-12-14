# STOPWATCH# Stopwatch Web Application

A simple, elegant stopwatch application built with HTML, CSS, and JavaScript. Features a clean user interface with start, stop, and reset functionality.

## Features

- **Start/Resume**: Begin timing or resume from a paused state
- **Stop/Pause**: Pause the timer at the current time
- **Reset**: Clear the timer back to 00:00:00
- **Time Display**: Shows hours, minutes, and seconds in HH:MM:SS format
- **Responsive Design**: Adapts to different screen sizes with a maximum width of 600px

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (Courier Prime)

## Project Structure

```
project-folder/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript logic
└── images/
    ├── background.png  # Background image for stopwatch
    ├── start.png       # Start button icon
    ├── stop.png        # Stop button icon
    └── reset.png       # Reset button icon
```

## How It Works

The stopwatch uses `setInterval()` to increment the time every second (1000ms). The timer tracks seconds, minutes, and hours separately:

- When seconds reach 60, they reset to 0 and minutes increment
- When minutes reach 60, they reset to 0 and hours increment
- Numbers are zero-padded for consistent display (e.g., "09" instead of "9")

### Key Functions

- `stopwatch()`: Increments time and updates the display
- `watchStart()`: Starts or resumes the timer
- `watchStop()`: Pauses the timer
- `watchReset()`: Stops and resets timer to 00:00:00

## Setup Instructions

1. Clone or download the project files
2. Ensure all files are in the correct structure as shown above
3. Make sure the `images` folder contains:
   - background.png
   - start.png
   - stop.png
   - reset.png
4. Open `index.html` in a web browser

