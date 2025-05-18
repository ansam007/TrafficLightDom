# TrafficLightDom

Problem: Traffic Light Simulation System

Objective:

Design a program to simulate traffic light behavior for an intersection with 4 directions: North, South, East, and West.

The traffic lights should cycle through Red → Green → Yellow, with configurable timing for each state.

Functional Requirements:

1. Each direction should have:

A light indicator (Red, Green, Yellow)

A countdown timer for the current state

2. The transition cycle for each signal is:

Red Green → Yellow → Red

3. Configurable Timing:

Each state (Red, Green, Yellow) should be configurable through a settings section (e.g., Green = 20s, Yellow = 4s, Red = 24s).

4. Times can be changed before starting the simulation.

5. Continuous Operation:

The program should run in a loop, continuously cycling the signals.

At any time, only one direction has the Green light.

After completing one direction's cycle (Green + Yellow), the next direction becomes active.

6. Start/Stop Buttons:

User can start and stop the simulation using Ul buttons.

7. Interface Features (if built with web/PHP + JS):

A simple Ul showing 4 traffic lights (one for each direction).

Timer displayed under each light, showing remaining seconds.

"Start Simulation" and "Stop Simulation" buttons.

Settings panel to configure durations.

8. Example Configuration:

Green = 20 seconds

Yellow = 4 seconds

Red (Green + Yellow x 3) = 72 seconds for a 4-direction model

So, each light is:

Green for 20s

Yellow for 4s

Red while other 3 lights cycle (20+4)x3 = 725

9. In second versing of this program add following features:

Add pedestrian signals

Emergency override (stop all)

Log transitions and timer events

Simulate night mode (flashing yellow)
