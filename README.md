# VNH2SP30E-Dual-Driver-Board
Overview:
This project contains the schematic design and reference files for a dual-channel motor driver board based on the VNH2SP30-E full-bridge motor driver IC. The board is designed for high-current DC motors with enhanced protection and integrated logic power management.
It is intended for robotics, automation, and high-power DC motor applications.

##Features:
Dual VNH2SP30-E H-bridge motor driver configuration

Reverse polarity protection on main power input

TVS diode protection for voltage transients

Self-powered 5V logic supply using LM2596S

MCU supply capable from onboard 5V rail

High-current motor support

Separate logic and motor ground layout considerations

##Applications:

Mobile robots

Electric mobility platforms

Robotic arms and automation projects

Combat robots and hobbyist projects

##Hardware Architecture:

Power Input: Reverse polarity protected and TVS-protected

Logic Supply: Onboard 5V regulator to power MCU and logic circuits

Motor Driver Stage: Dual VNH2SP30-E H-bridges with current handling capability

Protection: TVS and reverse polarity diodes

Connectors: Easy interfacing with MCU and motor terminals

## License

This project is licensed under the
CERN Open Hardware Licence Version 2 – Weakly Reciprocal (CERN-OHL-W-2.0).
See the LICENSE file for details.
