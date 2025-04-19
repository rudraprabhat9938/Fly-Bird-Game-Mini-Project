# Fly By: Building an Interactive 3D Experience

## Overview

**Fly By** is a web-based 3D flight simulation game developed as a group minor project at the **School of Computer Engineering, KIIT University, Bhubaneswar**. The game allows players to explore an infinite, procedurally generated hexagonal landscape from a bird's perspective. Built using **Three.js** and optimized for web performance, the game leverages modern WebGL techniques, procedural content generation, and GPU-aware rendering strategies.

## Key Features

- Infinite procedurally generated terrain using Simplex noise.
- Adaptive rendering using InstancedMesh for grass, trees, and terrain tiles.
- Real-time asset loading and GPU-tier based optimizations.
- Smooth third-person and bird’s-eye camera system with virtual joystick support.
- Flight controls with responsive animations and terrain collision avoidance.
- UI enhancements with animated loading screens, modal info windows, and background music.

## Technologies Used

- [Three.js](https://threejs.org/)
- [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader)
- [Howler.js](https://howlerjs.com/) for audio
- [GSAP](https://greensock.com/gsap/) for UI animations
- [NippleJS](https://yoannmoi.net/nipplejs/) for virtual joystick
- [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) for optimized raycasting

## Team Members & Contributions

### 🔹 Masheera Afrin (22051348)
- Implemented environmental elements (clouds, grass, trees).
- Used InstancedMesh for efficient foliage rendering.
- Contributed to sections on foliage placement and asset loading.
- Presented biome-based foliage system and rendering optimization.

### 🔹 Priyangsu Banerjee (22052490)
- Designed and implemented procedural terrain system.
- Created dynamic tile loading/unloading logic.
- Ensured GPU memory management using `.dispose()`.
- Presented terrain generation and tiling performance optimizations.

### 🔹 Masoom Choudhury (22052828)
- Built core Three.js initialization and adaptive GPU settings.
- Configured fog, lighting, and responsive scene adjustments.
- Emphasized scene aesthetics and initialization order.
- Presented engine setup and fog-based performance tuning.

### 🔹 Piyush Kumar Sahoo (22053834)
- Developed loading screen, background music, and UI animations.
- Integrated Howler.js and GSAP for enhanced UX.
- Managed asynchronous asset loading coordination.
- Presented UX components and loading flow.

### 🔹 Rudra Prabhat Pattanaik (22052847)
- Implemented third-person camera system and joystick controls.
- Created toggleable views and flight speed modes.
- Integrated nippleJS for mobile control compatibility.
- Presented camera mechanics and UI interaction logic.

### 🔹 Souradip Saha (22052939)
- Loaded bird model, implemented animations and movement.
- Enabled terrain collision detection using BVH-accelerated raycasting.
- Developed flight physics and character interaction.
- Presented bird control system and terrain response.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fly-by.git
   cd fly-by
