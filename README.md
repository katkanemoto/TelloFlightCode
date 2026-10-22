# Tello Flight Code

This project contains Python code for controlling a Ryze Tello drone.

- `tello.py` defines a `Tello` class with commands for takeoff, landing, movement, turns, flips, and battery checks.
- `telloController.py` is a sample flight program. It checks the battery, takes off, climbs 100 cm, flips forward and backward, turns 180 degrees, lands, and reports the battery used.

## Run the program

1. Connect the computer to the Tello’s Wi-Fi network.
2. Keep `tello.py` and `telloController.py` in the same folder.
3. Run `python3 telloController.py`.

Movement distances use centimeters by default.

## Safety

Review the route and clear the flight area before running code. The sample program includes flips, so **do not run it as-is in an obstacle course**. Replace the flip commands with measured movement commands and get instructor approval before flying.
