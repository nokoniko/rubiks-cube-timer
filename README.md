# Rubiks Cube Timer

Time your Rubik's Cube solves right inside Raycast — get a random scramble, start the timer, and keep your solves. No account, API key, or external service required.

## Features

- **Random 3×3 scrambles** — a fresh scramble for every solve
- **Timer** — start and stop with Enter, with a live count while you solve
- **Adjustable precision** — count up in whole seconds, half seconds, or tenths (the final time is always millisecond-accurate)
- **Local history** — every solve is saved on your machine between sessions
- **csTimer import/export** — move your solves to and from [csTimer](https://cstimer.net) using its export format

## Timer precision

Open the command preferences (⌘, → Extensions, or "Configure Command") and set **Timer Precision**:

- **Seconds** — 1, 2, 3
- **Half seconds** — 1, 1.5, 2
- **Tenths** — 1, 1.1, 1.2

The recorded time is always exact regardless of this setting; it only changes how finely the running timer ticks.

## Import / export

- **Export to csTimer** (⌘⇧E) writes a `cstimer_<timestamp>.txt` file to your Downloads folder that you can import directly into csTimer.
- **Import from csTimer** (⌘⇧I) lets you pick a csTimer export file and merges those solves into your history (duplicates are skipped).


Notation pictures are taken from https://www.cube.academy/ so give them some love :)