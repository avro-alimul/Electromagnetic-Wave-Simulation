# 3D Electromagnetic Wave Simulation

A real-time, interactive 3D visualization of electromagnetic wave propagation using [Three.js](https://threejs.org/). This project demonstrates the relationship between electric and magnetic fields in a traveling wave, allowing users to adjust parameters and observe the effects in real time.

## Features

- **3D Visualization**: See electric (E) and magnetic (B) field oscillations and their propagation in space.
- **Interactive Controls**: Adjust frequency, wavelength, amplitude, and particle density.
- **Pause/Play Animation**: Control the simulation flow.
- **Reset Camera**: Instantly reset the 3D view.
- **Responsive UI**: Works on both desktop and mobile devices.

## Demo

Open `index.html` in your browser to run the simulation locally. No build step or server is required.

## Usage

- **Frequency**: Changes the oscillation rate of the wave.
- **Wavelength**: Adjusts the spatial period of the wave.
- **Amplitude**: Sets the maximum field strength.
- **Particle Density**: Controls the number of visualized points along the wave.
- **Pause/Play**: Start or stop the animation.
- **Reset View**: Return the camera to its default position.

## How It Works

- **Electric Field (E)**: Visualized as red spheres and a red line, oscillating along the Y-axis.
- **Magnetic Field (B)**: Visualized as blue spheres and a blue line, oscillating along the Z-axis.
- **Propagation Direction (k)**: Along the X-axis.
- **Field lines**: Show the continuous variation of E and B fields.
- **Three.js**: Used for all 3D rendering and animation.

## Controls

| Control          | Description                      |
| ---------------- | -------------------------------- |
| Frequency        | Adjusts wave frequency (Hz)      |
| Wavelength       | Adjusts wave length (units)      |
| Amplitude        | Adjusts field strength           |
| Particle Density | Number of points along the wave  |
| Pause/Play       | Start or stop the animation      |
| Reset View       | Reset camera to default position |

## Installation

1. **Clone or Download** this repository.
2. **Open `index.html`** in any modern web browser (Chrome, Firefox, Edge, Safari).

No dependencies or build tools are required. All libraries are loaded via CDN.

## Dependencies

- [Three.js](https://threejs.org/) (via CDN)

## File Structure

```
index.html      # Main application file
README.md       # Project documentation
```

## Screenshots

> _Add screenshots here if desired._

## License

This project is open source and available under the MIT License.
