# Public Design Evidence Index

This index links to **existing CAD files** checked into the default branch. It does not contain recreated screenshots or claim that a design has passed verification.

| Artifact | Location | Evidence type |
|---|---|---|
| BMP sensor | [BMP unit schematic](../hardware/BMP_unit.kicad_sch) | Original KiCad schematic |
| LSM6DSO32 IMU | [IMU project directory](../hardware/LSM6DSO32_schematic/) | Original schematic, PCB, and project |
| GPS module | [GPS board directory](../hardware/GPS%20board/) | Original schematic, PCB, and project |
| Integrated design | [ESP32 Sensor Hat directory](../hardware/sensor_board/) | Original schematic, PCB, and project |
| Board requirements | [Electrical requirements](requirements/electrical_requirements.md) | Engineering requirements (some TBD) |
| Planned verification | [Bring-up checklist](../testing/bringup/bringup_checklist.md) | Test plan, not signed results |

## How to review

1. Open the linked schematic (`.kicad_sch`) in KiCad's Schematic Editor.
2. Open a matching PCB (`.kicad_pcb`) in PCB Editor; use 3D Viewer for a geometry preview.
3. Check project files (`.kicad_pro`) and library references before drawing conclusions about build readiness.
4. Review branch and commit history for changes that have not yet reached `main`.

## Screenshots and Tests

No publicly reviewed, source-backed screenshots, physical-board photographs, oscilloscope traces, or verified sensor-readout captures were located in this repository's default branch during this documentation update. Such assets should be added only with team approval and accurate captions.

[Back to README](../README.md) · [Engineering portfolio](https://github.com/LezigaBeage/Leziga_Portfolio)
