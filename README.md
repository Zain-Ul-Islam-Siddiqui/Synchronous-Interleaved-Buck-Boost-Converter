# Synchronous-Interleaved-Buck-Boost-Converter
High-efficiency 60A DC-DC converter with synchronous MOSFET driving and interleaved power stages.

## Overview

Designed a high-power DC-DC buck-boost converter capable of 60A output using an interleaved architecture to reduce ripple and improve thermal performance.

## Description

This converter was developed for applications requiring wide input ranges and high current output — such as battery charging and industrial power electronics.

The design uses dual-phase interleaving with synchronous MOSFETs to achieve:
- Lower inductor ripple current
- Higher efficiency
- Improved thermal distribution

The control circuitry includes a fast current-mode control loop, gate-driver isolation, and temperature-protected MOSFET stages. The design also incorporates:
- Input/output filtering
- Reverse current prevention
- Adjustable output regulation
- Fault messages via UART or CAN

## Key Features

- 60A continuous output
- Two-phase interleaving
- Synchronous MOSFET topology
- Current-mode control
- Optimized PCB copper pours for thermal handling
- Input/output LC filtering
- UVLO, OCP, OTP protections

## Technologies

- LTspice, Altium, Gate drivers, Current-mode control, High-power PCB design

## Contribution

- Full power stage design
- MOSFET selection & thermal modeling
- PCB layout for high-current paths
- Firmware tuning & validation
