# BBB Yocto EKG Sensor Monitor Design Package

## Purpose

BeagleBone Black medical-sensor project using a custom Yocto image, ADC-connected EKG/ECG front end, systemd acquisition service, and local waveform logging.

This package defines the project as an implementation-ready embedded system. It covers system architecture, requirements, interface boundaries, runtime design, validation evidence, and phased delivery.

## Project Profile

| Field | Value |
| --- | --- |
| Repository | `rheslar1/bbb-yocto-ekg-sensor-monitor` |
| Primary stack | C++17, C++ Design Patterns, SOLID, BeagleBone Black, Yocto, EKG/ECG, ADC, IIO, Systemd, Signal filtering |
| Review proof point | Custom Linux image ownership, analog biosignal acquisition, timestamped waveform capture, filtering evidence, and board-level validation boundaries. |

## Artifacts

- [System Design](system-design.md)
- [Requirements](requirements.md)
- [Interface Control](interface-control.md)
- [Runtime Design](runtime-design.md)
- [Validation Plan](validation-plan.md)
- [Implementation Roadmap](implementation-roadmap.md)
- [Draw.io UML](diagrams/system-design.drawio)
- [PNG UML](diagrams/system-design.png)
