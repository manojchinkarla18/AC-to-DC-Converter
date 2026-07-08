# 12V AC to DC Converter PCB Design

## Overview

This project presents the design of a **12V AC to DC Converter** using **KiCad 10**. The converter uses a full-wave bridge rectifier to convert a 12V AC input into an unregulated DC output. A filter capacitor smooths the rectified voltage, while an LED with a current-limiting resistor serves as a power indicator.

The project demonstrates the complete PCB design workflow, including schematic capture, footprint assignment, PCB layout, design rule checking (DRC), and Gerber file generation for PCB fabrication.

---

## Features

- 12V AC input
- Full-wave bridge rectifier using four 1N4007 diodes
- Capacitor filter for smoothing the output voltage
- LED power indicator
- Compact single-board PCB layout
- Designed using KiCad 10

---

## Specifications

| Parameter | Value |
|----------|-------|
| Input Voltage | 12 VAC |
| Output Voltage | ~15–16 VDC (Unregulated) |
| Rectifier Type | Full-Wave Bridge |
| Diodes | 4 × 1N4007 |
| Filter Capacitor | 1000 µF |
| PCB Software | KiCad 10 |

---

## Components Used

- 4 × 1N4007 Rectifier Diodes
- 1 × 1000 µF Electrolytic Capacitor
- 1 × 10 kΩ Resistor
- 1 × 2.2 kΩ Resistor
- 1 × 5 mm LED
- 2 × 2-Pin Screw Terminal Connectors

---

## PCB Design Workflow

1. Project Setup
2. Schematic Design
3. Component Annotation
4. Footprint Assignment
5. PCB Layout
6. Track Routing
7. Design Rule Check (DRC)
8. 3D PCB Verification
9. Gerber File Generation

---
## Learning Outcomes

This project helped in understanding:

- Schematic design using KiCad 10
- Bridge rectifier implementation
- PCB footprint assignment
- PCB routing techniques
- Design Rule Check (DRC)
- PCB manufacturing file generation
- Hardware project documentation using GitHub

---

## Software Used

- KiCad 10
- Git
- GitHub
