# #85 Dirty JSON Scrubber

A specialized survival tool for developers to rescue valid JSON structures from the chaos of raw logs, emails, and unstructured text.

## Core Philosophy
- **1 Tool / 1 Action**: Instantly isolates JSON from noise.
- **User-Centric Priority**: Prioritizes professional utility over strict minimalism when multiple JSON blocks are detected.
- **High-Contrast Comfort**: Features a "Matrix-inspired" dark mode with optimized green hues to reduce eye strain during debugging.

## Features
- **Intelligent Multi-Extraction**: Scans entire text for all valid `{}` (objects) and `[]` (arrays), listing them as selectable tabs.
- **Deep Cleansing**: Automatically strips surrounding text, timestamps, and log headers, outputting perfectly indented JSON.
- **Pro-Feedback UI**: 
  - **Dynamic Tabs**: Shows byte sizes for each extracted block for quick identification.
  - **Tactile Copying**: The COPY button transforms to a "DONE" state with a green highlight for unmistakable confirmation.
  - **Zero-Friction Clear**: A one-tap "×" button to wipe large data sets instantly.
- **Mobile Optimized**: Prevents accidental text selection during rapid interaction via `user-select: none`.

## How to Use
1. **The Paste**: Dump your raw, messy log data into the input field.
2. **The Discovery**: The tool automatically identifies valid JSON blocks. Tap "SCRUB NOW" to focus on the result.
3. **The Selection**: If multiple JSONs exist, switch between tabs (e.g., JSON #1, JSON #2) to find the specific data you need.
4. **The Rescue**: Tap "COPY" to take your clean JSON back to your IDE or terminal.

## Design System
- **Theme**: Fridge Combo Dark (Background: `#1A1A1A` / Text: `#4AF626`)
- **Accent**: `#CCC`
- **Radius**: 15px
- **Font**: Optimized Monospace (SFMono/Consolas) for readability.

---
**No login / No tracking / No ads / Browser only**
**Privacy Policy / afrorakda © 2026**
