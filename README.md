
---

# Retro Flight Simulator

A 3D flight simulator with a retro cyberpunk aesthetic, featuring flying, shooting, and multiplayer capabilities. Built using HTML, JavaScript, and WebGL, this project is hosted on GitHub Pages and accessible at [fly.ewluong.com](https://fly.ewluong.com).

## Features

- **3D Environment**: Includes sky, ground, runway, ATC tower, windsock, ocean, beach, buildings, houses, castle, clouds, and a moon.
- **Aircraft Model**: Detailed aircraft with body, wings, tail, windows, and landing gear, capable of shooting foam darts.
- **Flight Mechanics**: Simulates realistic flight physics, including lift, gravity, and turbulence.
- **Shooting Mechanics**: Shoot foam darts to hit targets like balloons, ships, buildings, and a castle.
- **Multiplayer**: WebRTC-based multiplayer using PeerJS, allowing real-time interaction with other players.
- **Camera Views**: Toggle between third-person and cockpit views.
- **Day-Night Cycle**: Dynamic lighting with a day-night cycle and runway/approach lights.
- **Mobile Support**: On-screen joysticks for touch devices.
- **Audio**: Engine sounds, shooting effects, explosions, and an ATC radio stream.

## How to Play

Visit [fly.ewluong.com](https://fly.ewluong.com) to access the simulator. Fly your aircraft, shoot targets, and interact with other players in multiplayer mode. The goal is to hit as many targets as possible while avoiding collisions.

## Controls

### Desktop
- **W/S**: Throttle up/down
- **Left/Right Arrows or A/D**: Turn left/right
- **Up/Down Arrows**: Pitch up/down
- **Space**: Shoot foam darts
- **V**: Toggle between third-person and cockpit views
- **Mouse**: Control camera direction

### Mobile
- **Left Joystick**: Pitch and roll controls
- **Right Joystick**: Throttle control
- **Touch Screen**: Camera control and shooting

## Dependencies

This project relies on the following libraries:
- [Three.js](https://threejs.org/) for 3D rendering
- [PeerJS](https://peerjs.com/) for multiplayer networking
- [NippleJS](https://yoannmoi.net/nipplejs/) for mobile joystick controls

## Running Locally

To run the simulator on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/ewluong/flight-simulator.git
   ```
2. Open `index.html` in a modern web browser (e.g., Chrome, Firefox).

**Note**: Some features, such as multiplayer, may require additional setup or a local server to function properly.


For more projects, visit [ewluong.com](https://ewluong.com).

---
