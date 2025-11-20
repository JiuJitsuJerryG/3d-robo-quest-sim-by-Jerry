# 🤖 RoboQuest: 3D Robotic Arm Simulator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-orange)
![Engine](https://img.shields.io/badge/engine-Three.js-black)
![Status](https://img.shields.io/badge/status-Active-green)

**RoboQuest** is a standalone, browser-based 3D robotics simulator designed for beginners. It features a fully interactive 5-Degree-of-Freedom (5DOF) robotic arm, gamified challenges, and a block-coding interface—all contained within a single HTML file.

> **[🔴 LIVE DEMO: Click Here to Play](https://your-username.github.io/your-repo-name/)**
> *(Note: Replace the link above with your actual GitHub Pages URL after deploying)*

---

## ✨ Key Features

*   **🦾 Realistic 3D Simulation:** Fully rendered 5-DOF robotic arm with smooth kinematics using Three.js.
*   **🎮 Gamified Learning:** Complete pick-and-place challenges, unlock levels, and earn high scores with confetti celebrations.
*   **🧩 Block Coding:** Drag-and-drop style programming interface to automate robot movements (perfect for STEM learning).
*   **🕹️ Manual Control:** Fine-tune movements with sliders or keyboard shortcuts (WASD + Spacebar).
*   **📡 Simulated Sensors:** Real-time readout of distance-to-target and gripper state.
*   **🎨 Customization:** Switch between "Sci-Fi", "Industrial", and "Stealth" skins.

## 🚀 How to Use

### Online (Recommended)
Simply visit the **[Live Demo Link](#)** provided at the top of this page. No installation required!

### Offline (Local)
1.  Download the `index.html` file from this repository.
2.  Open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3.  *Note: An internet connection is required to load the Three.js library via CDN.*

## 🛠️ Controls

| Action | Input |
| :--- | :--- |
| **Move Camera** | Click & Drag Mouse |
| **Toggle Gripper** | Spacebar |
| **Move Base** | A / D Keys |
| **Move Shoulder** | W / S Keys |
| **Run Code** | Click "Run Program" in Sidebar |

## 📚 Educational Concepts

This simulator helps visualize core robotics concepts:
*   **Degrees of Freedom (DOF):** Visualizing how individual joints (motors) combine to move an end-effector in 3D space.
*   **Forward Kinematics:** Understanding how joint angles determine position.
*   **Teleoperation:** Controlling a remote robot via manual inputs.
*   **Automation:** Using sequential logic (code blocks) to execute repetitive tasks.

## 🔧 Customization & Hacking

Since the entire app is in one file (`index.html`), it is easy to modify! 
1.  Open `index.html` in a text editor (VS Code, Notepad++, etc.).
2.  Scroll to the `<script>` tag to change settings:
    *   **Modify Gravity/Speed:** Look for `const speed = 0.1;` inside `updatePhysics()`.
    *   **Change Level Layouts:** Edit the `setupLevel()` function to add new obstacles.
    *   **Add New Skins:** Add new colors to the `document.getElementById('skin-select')` event listener.

## 🛣️ Roadmap

Future features planned for this simulator:
- [ ] Inverse Kinematics (Click-to-move)
- [ ] Save/Load user programs to LocalStorage
- [ ] "Work-cell" Camera View (Picture-in-Picture)
- [ ] Mobile-optimized joystick controls

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created with Three.js and pure creativity.*
