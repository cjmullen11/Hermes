# Hermes

**Status:** Planned  
**Technologies:** ESP32-P4 · Embedded C/C++ · HDMI-to-CSI · USB HID · Ethernet · PCB Design

## Overview

Hermes is a compact IP-KVM designed to provide remote video, keyboard, mouse, and power control for a computer, even when its operating system is unavailable. I am exploring a low-cost embedded alternative to larger remote-management devices.

The name **Hermes** references the Greek messenger god associated with communication, travel, and crossing boundaries.

## Key Design Choices

- **Embedded video capture:** Investigate HDMI-to-CSI conversion for an ESP32-P4-class device.
- **Out-of-band control:** Emulate USB keyboard and mouse input and provide optional power/reset signals.
- **Wired networking:** Prioritize Ethernet, with PoE under consideration for simpler installations.
- **Purpose-built hardware:** Favor a small, affordable per-computer device over a general-purpose Linux system.

## Roadmap

- [ ] Validate the video capture and USB HID architecture.
- [ ] Select parts and draft the schematic.
- [ ] Design and review the PCB.
- [ ] Bring up video, input, and network firmware.
- [ ] Test remote control, power management, and reliability.

## Usage

### Requirements

### Setup

### Configuration

### Operation
