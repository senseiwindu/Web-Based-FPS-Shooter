# Advanced Web FPS

## Features

* **3D Graphics:** Rendered using WebGL and the Three.js library.
* **First-Person Controls:** Utilizes the browser's Pointer Lock API for infinite 360-degree mouse-look.
* **Physics & Movement:** Smooth WASD movement with gravity and jumping mechanics.
* **Shooting & Raycasting:** Accurately calculates line-of-sight shooting from the center of the camera.
* **Weapon Model:** Features a 3D gun model attached to the camera with dynamic recoil animations.
* **Destructible Targets:** Shoot targets to destroy them and increase your score.
* **Particle Effects:** Generates exploding debris blocks when a target is successfully hit.
* **Delta-Time Rendering:** Ensures the game runs at a consistent speed regardless of your monitor's refresh rate.

## Controls

* **W, A, S, D** - Move Forward, Left, Backward, Right
* **Spacebar** - Jump
* **Mouse** - Look around
* **Left Click** - Shoot

## How to Run Locally (Visual Studio Code)

Because this game uses the Pointer Lock API and external JavaScript libraries, it needs to be run through a local web server to bypass strict browser security rules (CORS). 

1. **Open the Project:** Open the folder containing `index.html` in Visual Studio Code.
2. **Install Live Server:** * Navigate to the **Extensions** tab in VS Code on the left sidebar (`Ctrl+Shift+X` or `Cmd+Shift+X`).
   * Search for `Live Server` (authored by Ritwick Dey).
   * Click **Install**.
3. **Launch the Game:**
   * Open the `index.html` file in your VS Code editor.
   * Look at the bottom right corner of your VS Code window for a button that says **Go Live** and click it.
   * Your default web browser will open automatically (usually at `http://127.0.0.1:5500/index.html`).
4. **Play:** Click anywhere on the game screen to lock your mouse and start playing!

## Things Used In the project

* HTML5 / CSS3
* JavaScript (ES6)
* [Three.js](https://threejs.org/) (r128)
* PointerLockControls.js
