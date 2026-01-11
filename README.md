# 🧊 The Virtual Room - 3D Web Experience

A spatial 3D web application built with **Three.js** for the **MLH Global Hack Week: Beginners** challenge. This project creates an interactive virtual environment where users can navigate a 3D space, manipulate objects, and explore spatial web technologies.

🔗 **[Play the Live Demo Here](https://kaustavoffx.github.io/virtual-room/)**

![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

---

## ✨ Features

This project goes beyond a simple cube by implementing advanced Three.js mechanics:

* **Interactive 3D Environment:** A fully rendered room with floors, walls, and dynamic lighting (Spotlights & Shadows).
* **Textured Assets:** The central cube features unique textures mapped to all 6 faces using `TextureLoader`.
* **Raycasting & Interaction:**
    * **Hover Effects:** The cube glows and scales up when hovered over with the mouse.
    * **Cursor States:** The cursor changes dynamically to indicate interactivity.
* **Advanced Controls:**
    * **Orbit Controls:** Click and drag to rotate the camera around the room.
    * **Zoom Constraints:** Camera allows zooming but prevents clipping through the floor or getting lost in the void.
    * **Keyboard Navigation:** Smooth character movement using arrow keys with boundary collision detection.
    * **Visual UI Overlay:** A custom HUD (Heads-Up Display) that visualizes controls for better user experience.

---

## 🎮 How to Play

| Control | Action |
| :--- | :--- |
| **Arrow Keys** | Move the cube around the room (X/Z Axis) |
| **Mouse Drag** | Rotate the camera view (Orbit) |
| **Mouse Scroll** | Zoom in and out |
| **Mouse Hover** | Interact with the cube (Triggers animation) |
| **Spacebar** | Reset the camera to the default position |

---

## 🛠️ Installation (Running Locally)

Because this project uses **ES Modules** and **Texture Loading**, standard browser security (CORS) will block it if you just double-click `index.html`. You need a local server.

### Option 1: VS Code (Recommended)
1. Install the **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** extension.
2. Right-click `index.html`.
3. Select **"Open with Live Server"**.

### Option 2: Python
If you have Python installed, run this command in the project folder:

```bash
python -m http.server 8000
