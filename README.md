# Motorhome LED Panels

WLED presets and tooling for the motorhome LED panel projects.

## Current Hardware Assumption

- One eye uses two chained 32x8 panels as a 64x8 matrix.
- Total LEDs per eye: 512.
- WLED segment: start `0`, stop `512`.
- Matrix setup: 64x8, RGB color order.

## Files

- `wled/motorhome_one_eye_wled_commands.json`: initial WLED JSON commands for amber and red angry-eye presets, with progressive and serpentine wiring variants.

## Usage

In WLED, create a preset, open the API command/JSON field, paste one command object from the JSON file, and save it.

If the eye shape looks scrambled, try the matching serpentine variant.
