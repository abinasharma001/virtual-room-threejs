# 🏠 Virtual Room – Three.js
Global Hack Week: Beginners – The Virtual Room
An interactive 3D virtual room experience built with Three.js, featuring draggable objects, smooth camera controls, and an immersive environment.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://abinasharma001.github.io/virtual-room-threejs/)
[![Three.js](https://img.shields.io/badge/Three.js-r128-blue)](https://threejs.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## ✨ Features

- **Interactive 3D Environment** – Fully rendered 3D room with realistic lighting
- **Draggable Objects** – Click and drag objects to reposition them in the room
- **Smooth Camera Controls** – Intuitive mouse controls for navigation
  - Zoom in/out with mouse wheel
  - Rotate view with right-click and drag
- **Responsive Design** – Adapts to different screen sizes
- **Physics-based Interactions** – Natural object movement and placement

## 🎮 Controls

| Action | Control |
|--------|---------|
| **Move Objects** | Click & Drag on any object |
| **Zoom** | Mouse Wheel / Scroll |
| **Rotate View** | Right Click + Drag |

## 🚀 Demo

Check out the live demo: [Virtual Room Demo](https://abinasharma001.github.io/virtual-room-threejs/)

## 🛠️ Technologies Used

- **Three.js** – 3D graphics library
- **JavaScript (ES6+)** – Core programming language
- **HTML5 Canvas** – Rendering surface
- **OrbitControls** – Camera movement and interaction

## 📦 Installation

### Prerequisites

- A modern web browser with WebGL support
- Basic web server (optional, for local development)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/abinasharma001/virtual-room-threejs.git
   cd virtual-room-threejs
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local server for better performance:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or open `index.html` directly in your browser

## 📁 Project Structure

```
virtual-room-threejs/
│
├── index.html          # Main HTML file with Three.js scene
├── README.md           # Project documentation
└── assets/             # (Future) 3D models, textures, etc.
```

## 🎨 Features Breakdown

### Scene Setup
- Ambient and directional lighting for realistic shadows
- Perspective camera with optimal field of view
- Anti-aliased renderer for smooth edges

### Interactive Objects
- Dynamic raycasting for object selection
- Smooth drag-and-drop mechanics
- Collision detection with room boundaries

### Camera System
- OrbitControls for intuitive navigation
- Customizable zoom limits
- Smooth damping for natural movement

## 🔮 Future Enhancements

- [ ] Add more furniture and decorative objects
- [ ] Implement texture mapping for realistic materials
- [ ] Add day/night lighting toggle
- [ ] Include sound effects for interactions
- [ ] Save and load room configurations
- [ ] Multi-room support
- [ ] VR compatibility

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- Performance may vary on older devices
- Some mobile browsers may have limited touch controls

## 📝 Development Notes

This project was developed as part of the **Global Hack Week: Beginners – The Virtual Room Challenge**. GitHub Copilot was utilized to assist in generating the Three.js scene setup, camera controls, and interaction logic.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Abina Sharma**

- GitHub: [@abinasharma001](https://github.com/abinasharma001)
- Project Link: [https://github.com/abinasharma001/virtual-room-threejs](https://github.com/abinasharma001/virtual-room-threejs)

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) – Amazing 3D graphics library
- [GitHub Copilot](https://github.com/features/copilot) – AI pair programmer
- Global Hack Week community for inspiration

## 📚 Resources

- [Three.js Documentation](https://threejs.org/docs/)
- [Three.js Examples](https://threejs.org/examples/)
- [WebGL Fundamentals](https://webglfundamentals.org/)

---

⭐ If you found this project interesting, please consider giving it a star!
