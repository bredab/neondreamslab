# Neon Dreams Lab
Creative Coding & Interactive Web Playground

## Overview
This repository contains a collection of single-file web applications focused on mathematical visualizations, generative art, and interactive experiments. Each application is designed to run directly in the browser, leveraging technologies like WebGL, Three.js, and the HTML5 Canvas API.

## Applications

### 1. 3D Interference Lab
**Path:** `apps/3dinterference/`  
A powerful 3D visualizer for mathematical interference patterns and isosurfaces.
- **Tech**: Three.js, WebGL
- **Features**: 
  - Custom mathematical formula input (`f(x,y,z) = 0`).
  - Presets for complex surfaces like Gyroid, Schwarz P, and Neovius.
  - Real-time adjustment of grid size, tolerance, and periodicity.
  - Advanced material rendering (metalness, roughness) and environment lighting.

### 2. Carpethia
**Path:** `apps/carpethia/`  
A 2D pattern generator simulating wave interference combined with "logic gate" thresholding logic.
- **Tech**: Custom WebGL Shaders
- **Features**: 
  - precise control over interference wave frequency and rotation.
  - "Logic Gate" threshold parameters to slice the noise function.
  - RGB phase shifting for chromatic aberration effects.

### 3. Kaleidoscope
**Path:** `apps/kaleidoscope/`  
A complex visual synthesizer and kaleidoscope effect generator with audio-reactive capabilities.
- **Tech**: HTML5 Canvas (Advanced Pixel Manipulation)
- **Features**: 
  - **Audio Matrix**: Reacts to microphone/system audio with Bass/Mid/Treble mapping.
  - Geometry and post-processing controls (Blur, Contrast, Gamma).
  - Built-in video recording and preset system.

### 4. Moire Pattern Generator
**Path:** `apps/moire/`  
Generates mesmerizing Moiré patterns using dynamic point rendering based on wave interference.
- **Tech**: WebGL
- **Features**: 
  - Adjustable wave density, rotation, and point radius.
  - High-precision rendering options.
  - Export capabilities (PNG/JPG).
  - Mobile-friendly with landscape orientation warnings.

### 5. Simple Pattern Generator
**Path:** `apps/simplepattern/`  
A lightweight, efficient tool for creating grid-based spherical height map patterns.
- **Tech**: WebGL
- **Features**: 
  - Real-time grid density and sphere radius adjustments.
  - RGB offset controls for color separation.
  - High-resolution image export.

### 6. Integer Spectroscope
**Path:** `apps/spectroscope/`  
A mathematical visualization tool exploring number theory relationships, specifically Greatest Common Divisors (GCD).
- **Tech**: Chart.js, HTML5 Canvas
- **Features**: 
  - **Spectrogram**: Grid visualization colored by GCD values.
  - **Chart**: Line graph showing "Common Divisors Count" resonances.
  - Dynamic grid size adjustment.

### 7. Concept Prototype
**Path:** `apps/concept/`  
A 2D visualization sandbox for trigonometric functions (Prototyping tool).
- **Tech**: HTML5 Canvas
- **Features**: 
  - Visualizes constraints like `z - ε/2 ≤ cos(x) + cos(y) ≤ z + ε/2`.
  - Simple controls for resolution and periodicity.

## Usage
These are static web applications. You can run them by:
1. Cloning the repository.
2. Opening the `.html` files directly in any modern web browser.
3. For the best experience (especially for audio/video features), serving them via a local web server is recommended (e.g., VS Code Live Server, python http.server).
