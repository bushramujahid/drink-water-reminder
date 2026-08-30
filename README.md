# Drink Water Reminder

A simple Python desktop notification app that reminds you to drink water every hour.

## Features
- Sends a desktop notification with a reminder message
- Runs continuously in the background
- Easy to customize the reminder interval

## Requirements
- Python 3
- `plyer` package

## Installation

1. Open a terminal in the project folder.
2. Install the dependency:

```bash
pip install plyer
```

## Run the app

```bash
python main.py
```

The app will show a notification titled **Water Reminder for Bushra** every hour.

## Customize the reminder interval

In `main.py`, you can change the sleep duration:

```python
time.sleep(3600)
```

This value is in seconds. For example:
- `1800` = 30 minutes
- `3600` = 1 hour
- `3` = 3 seconds (useful for testing)

## Notes
This project uses the `plyer` library to display system notifications on desktop platforms.
