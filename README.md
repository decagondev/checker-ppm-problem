# Checkerboard PPM Generator Challenge

## Problem

Write a program that generates a red-and-black checkerboard image in the binary Netpbm PPM (P6) format.

### Specifications

- Image size: 960 × 540 pixels
- Square size: 60 × 60 pixels
- Colors:
  - One color: pure red (255, 0, 0)
  - Other color: pure black (0, 0, 0)
- Top-left square must be red
- Output file: `checkerboard.ppm` (created in the current directory)
- Format: Binary PPM (P6)
  - Header: P6\n960 540\n255\n
  - Followed by exactly 960 × 540 × 3 = 1,555,200 bytes of raw RGB data

### Rules

- No external image libraries allowed
- Must write raw binary pixel data directly
- Program takes no arguments
- Must work on standard-compliant compilers/interpreters