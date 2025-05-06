# AlarmClock

A simple Python alarm clock script designed for macOS. This script allows you to set an alarm for a specific time, and when the alarm triggers, it plays a sound to wake you up. The script uses standard Python libraries, tkinter and Pygame, and can be ran from the command line.

## Features

- Set an alarm for any time in 24-hour format (HH:MM:SS)
- Plays a sound file when the alarm time is reached
- Simple and lightweight, no external dependencies except for sound playback
- Designed to work on macOS

## Pre-reqs:

- Python 3.x (recommended: Python 3.7+)
- [pygame](https://www.pygame.org/) (for playing sound)
- A sound file (e.g., `sound.mp3`, `sound.wav`) in the same directory as the script

## Installation

1. **Clone the repository or download the script:**
```
git clone https://github.com/crissyg/AlarmClock.git
```

3. **Install required packages:**
```
pip3 install tkinter

pip3 install pygame
```

## Usage

1. **Place your alarm sound file**, `sound.wav` or `sound.mp3`, in the same directory as the script.

2. **Run the script:**

python alarmclock.py


3. **When the Alarm Clock GUI is prompted, enter the alarm time** in 24-hour format, for example:

Enter alarm time (HH:MM:SS): 07:30:00

![Username field and element ID name](images/tk-alarmclock.png)

4. The script will display the current time every second in the terminal. When the set time is reached, the alarm will sound and a wake-up message will be displayed.

## Example

```
23:02:49 23:02:50
23:02:49 23:02:50
23:02:50 23:02:50
Time to Wake up
```