# Harvard HIV Research WebXR Data Visualization

![Harvard Institution HIV Data Visualization]
(https://github.com/CharityEverett/hiv/blob/f85c766f1dd307cba3fb5d2c7aa436663f917870/assets/WIP.gif)

[View the visualization here](https://charityeverett.github.io/hiv/)

An interactive WebXR visualization exploring Harvard's groundbreaking HIV research collaborations across multiple institutions. This project visualizes how Harvard's research centers worked together to reshape modern medicine through HIV research as shown in the recent Harvard Gazette article. [Find the published article here](https://news.harvard.edu/gazette/story/2024/11/how-hiv-research-has-reshaped-modern-medicine/).

## Overview

This visualization features:
- Interactive 3D model of an HIV virus with dynamic spikes and glowing elements
- Circular timeline showing Harvard's key research institutions
- Click on any of the timeline panels to see information on the contributions and researchers
- Color-coded segments representing different research centers
- Particle effects creating a microscopic atmosphere
- 3D extruded text elements providing institutional information
- VR-compatible interface

## Technical Features

- Built with A-Frame WebXR framework
- Dynamic 3D text rendering using Troika Text
- Particle system for background effects
- Bloom post-processing effects
- Interactive elements with click responses
- Responsive design for both desktop and VR viewing
- Soon to have AR component where visualization is tracked to your hand

## Installation

1. Clone the repository
2. Serve the files using a local server (e.g., `python -m http.server`)
3. Open in a WebXR-compatible browser

## Dependencies

- A-Frame 1.2.0
- Troika Text
- Three.js
- A-Frame Particle System

## Usage

- View in desktop browser, mobile, or VR headset
- Click/touch timeline segments for more information
- Use WASD keys or VR controllers to navigate
- Look around using mouse or headset movement
- Manipulate model by dragging and rotating. 

## Credits

Based on research from Harvard's [recent article](https://news.harvard.edu/gazette/story/2024/11/how-hiv-research-has-reshaped-modern-medicine/) on HIV research impact. Visualization inspired by Harvard's collaborative approach to HIV research across multiple institutions.

## License

MIT License
