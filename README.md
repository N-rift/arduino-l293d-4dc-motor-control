# Arduino L293D 4 DC Motor Control

This project is a Tinkercad simulation that demonstrates controlling four DC motors using an Arduino Uno and two L293D motor drivers.

## Project Objective

Program four DC motors to perform the following sequence:

1. Move forward for **30 seconds**.
2. Move backward for **1 minute**.
3. Alternate between turning **right** and **left** for **1 minute**.

## Components

- Arduino Uno
- 2 × L293D Motor Driver IC
- 4 × DC Motors
- Breadboard
- Jumper Wires

## Pin Configuration

### L293D #1

| Arduino Pin | L293D Pin | Function |
|-------------|-----------|----------|
| D2 | IN1 | Motor 1 Direction |
| D3 | IN2 | Motor 1 Direction |
| D5 | EN1 | Motor 1 Enable |
| D4 | IN3 | Motor 2 Direction |
| D7 | IN4 | Motor 2 Direction |
| D6 | EN2 | Motor 2 Enable |

### L293D #2

| Arduino Pin | L293D Pin | Function |
|-------------|-----------|----------|
| D8 | IN1 | Motor 3 Direction |
| D9 | IN2 | Motor 3 Direction |
| D10 | EN1 | Motor 3 Enable |
| D11 | IN3 | Motor 4 Direction |
| D12 | IN4 | Motor 4 Direction |
| D13 | EN2 | Motor 4 Enable |

## Features

- Controls four DC motors using two L293D motor drivers.
- Forward movement.
- Backward movement.
- Alternating left and right turns.
- Designed and tested using Tinkercad.

## Simulation

This project was created as part of the **Smart Methods Robotics Training** simulation tasks.

## Author

**V**
