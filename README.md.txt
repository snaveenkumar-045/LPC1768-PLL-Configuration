# PLL Configuration using LPC1768

## Overview

This project demonstrates the configuration of the Main PLL (PLL0) on the LPC1768 ARM Cortex-M3 microcontroller to generate higher CPU clock frequencies.

The application initializes the main oscillator, configures PLL0, performs the mandatory PLL Feed Sequence, waits for PLL lock, and connects the PLL as the system clock source.

LED blinking is used to verify the change in processor clock frequency.

---

## Features

- Main Oscillator Configuration
- PLL0 Configuration
- PLL Feed Sequence
- PLL Lock Detection
- CPU Clock Configuration
- LED Blinking Demonstration

---

## Hardware

- LPC1768 Development Board
- LEDs
- Keil uVision
- Embedded C

---

## Project Structure

```
pll1.c
images/
docs/
videos/
```

---

## Working

1. Configure Main Oscillator.
2. Select Main Oscillator as Clock Source.
3. Configure PLL Multiplier.
4. Enable PLL.
5. Execute PLL Feed Sequence.
6. Wait until PLL is Locked.
7. Connect PLL as CPU Clock.
8. Blink LEDs to demonstrate clock speed.

---

## How to Run

1. Open the project in Keil uVision.
2. Build the project.
3. Flash the program to the LPC1768 board.
4. Observe the LED blinking pattern.

---

## Demo Video

LinkedIn Project Demo:

(Paste your LinkedIn video URL here)

---

## Author

S Naveen Kumar