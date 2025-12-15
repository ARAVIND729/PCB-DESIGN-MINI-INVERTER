🔌 Mini Inverter PCB Design (12V DC to AC)

📘 Overview

This project presents the design and PCB implementation of a Mini Inverter that converts 12V DC input to AC output using a transformer-based topology. The inverter is designed and laid out using KiCad, covering the complete flow from schematic capture to PCB routing.

The design focuses on power electronics fundamentals, including oscillator generation, MOSFET switching, and step-up transformation.

🎯 Objectives

Design a compact inverter circuit using discrete components

Implement PWM/oscillator-based switching for MOSFETs

Convert low-voltage DC to higher-voltage AC using a transformer

Design and route a manufacturable PCB in KiCad

⚙️ System Description

The inverter system consists of the following functional blocks:

DC Input Stage (12V)

Battery input

Input filtering capacitors

Reverse polarity / protection diode

Oscillator / Driver Stage

IC-based square-wave / PWM signal generation

Adjustable frequency control using potentiometer

Gate drive resistors for MOSFET protection

Power Switching Stage

N-channel MOSFETs (IRLZ24)

Push-pull configuration

Low-side switching topology

Output Stage

Step-up transformer (12V → AC output)

LED indicator for output status

🧩 Key Components

MOSFETs: IRLZ24

Driver IC: IR2153 / equivalent PWM oscillator

Transformer: Step-down 240V ↔ 12V (used in reverse)

Diodes: 1N4007

Capacitors: Electrolytic + ceramic for filtering

Potentiometer: Frequency adjustment

PCB Tool: KiCad (Schematic + PCB Editor)

🖥️ PCB Design Details

Designed using KiCad 6.x

Two-layer PCB (Top & Bottom copper)

Proper component spacing for power devices

Thick power traces for high-current paths

Ground copper pour for noise reduction

Mounting holes provided for enclosure integration
