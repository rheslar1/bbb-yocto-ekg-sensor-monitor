# BBB Yocto EKG Sensor Monitor

BeagleBone Black medical-sensor project using a custom Yocto image, ADC-connected EKG/ECG front end, systemd acquisition service, and local waveform logging.

## Portfolio Purpose

This repository is an Embedded Systems project scaffold for the Rheslar portfolio. It is designed to become a hardware-backed project with build output, validation logs, and reviewable implementation evidence.

All generated Embedded Systems repos are C++17-first and are framed around C++ design patterns and SOLID design principles.

## Stack

- C++17
- C++ Design Patterns
- SOLID
- BeagleBone Black
- Yocto
- EKG/ECG
- ADC
- IIO
- Systemd
- Signal filtering

## Quick Start

```bash
cmake -S . -B build
cmake --build build
./build/bbb_yocto_ekg_sensor_monitor
ctest --test-dir build --output-on-failure
```

## Implementation Slices

- C++17 starter executable that exposes the project identity, stack, and validation target.
- Small strategy-style readiness check that keeps the scaffold aligned with C++ design patterns.
- Architecture document with control boundaries, data flow, safety assumptions, and evidence plan.
- CTest smoke test that keeps source, docs, and CI files present as the repo grows.
- GitHub Actions workflow for configure, build, executable smoke run, and repository validation.

## Evidence Target

Custom Linux image ownership, analog biosignal acquisition, timestamped waveform capture, filtering evidence, and board-level validation boundaries.

## Remote

Intended public repository: https://github.com/rheslar1/bbb-yocto-ekg-sensor-monitor
