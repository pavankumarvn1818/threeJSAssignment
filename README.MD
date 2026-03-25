# 🌌 3D Solar System Simulation – Three.js

## 📌 Overview

This project is an **interactive 3D Solar System simulation** built using **Three.js**, designed to visualize planetary motion with real-time user controls. The application enables users to dynamically adjust orbital speeds for each planet, providing an engaging and customizable experience.

The solution demonstrates practical implementation of **WebGL rendering, animation loops, and interactive UI controls** using pure **HTML, CSS, and JavaScript**.

---

## 📝 Assignment & Internship Context

This project was developed as part of a **frontend assignment** associated with an internship opportunity from **EmptyCup**, facilitated via **Internshala**.

The assignment was aimed at evaluating:

* Proficiency in **Three.js and WebGL rendering**
* Understanding of **animation and simulation logic**
* Ability to integrate **interactive UI controls**
* Overall **frontend engineering and problem-solving skills**

This implementation reflects a structured and practical approach to building **interactive 3D web applications**.

---

## 🚀 Live Demo

🔗 https://frontend-assignment-psi-ochre.vercel.app/

---

## 📂 Repository

🔗 https://github.com/pavankumarvn1818/threeJSAssignment.git

---

## 🧠 Key Features

* 🌍 Full Solar System Rendering (Sun + 8 planets)
* 🎛️ Dynamic Speed Controls via UI sliders for each planet
* 🔄 Real-time orbital revolution simulation
* 🌌 Skybox environment for immersive space background
* 🪐 Orbit rings visualization for each planet
* 💡 Point light source (Sun-based lighting)
* 🎥 Interactive camera using OrbitControls
* 📱 Responsive canvas with resize handling

---

## 🎮 Interactive Controls

The application includes a dedicated control panel:

**Adjust speed for:**

* Mercury
* Venus
* Earth
* Mars
* Jupiter
* Saturn
* Uranus
* Neptune

Each slider dynamically updates orbital speed in real-time via DOM interaction logic.

---

## 🛠️ Tech Stack

* **Three.js (v0.129.0)** – 3D rendering engine
* **JavaScript (ES Modules)** – Core logic
* **HTML5** – Structure
* **CSS3** – UI styling
* **OrbitControls** – Camera interaction

---

## 🏗️ Project Structure

```bash id="l7k2fp"
threeJSAssignment/
│── index.html        # UI + controls
│── index.css         # Styling (canvas + control panel)
│── main.js           # Core Three.js logic
│── img/              # Planet textures + skybox assets
```

---

## ⚙️ Core Architecture

### 1. Scene Initialization

* Perspective camera setup
* WebGL renderer with alpha + antialiasing
* OrbitControls integration

### 2. Planet System

* Planets generated using `SphereGeometry`
* Textures applied via `TextureLoader`
* Material switching (`MeshBasicMaterial` / `MeshStandardMaterial`)

### 3. Orbital Mechanics

* Each planet revolves using a time-based trigonometric function

**Core function:**

```js id="z0ff3d"
planetRevolver(time, speed, planet, orbitRadius)
```

### 4. Dynamic Speed Control

* Speeds stored in `revolutionSpeeds` object
* Updated in real-time from slider inputs
* Enables interactive simulation tuning

### 5. Visual Enhancements

* Skybox using cube textures
* Orbit rings using `RingGeometry`
* Lighting via `PointLight` from the sun

---

## ▶️ Installation & Setup

```bash id="s7o0on"
# Clone the repository
git clone https://github.com/pavankumarvn1818/threeJSAssignment.git

# Navigate into project
cd threeJSAssignment

# Run locally
Open index.html in browser
```

### Recommended (for module support):

```bash id="cbln73"
npx serve
```

---

## 🎥 Usage

* 🖱️ Drag → Rotate camera
* 🔍 Scroll → Zoom in/out
* 🎛️ Use sliders → Adjust planet speeds dynamically
* 🌍 Observe real-time orbital motion

---

## 📈 Learning Outcomes

This project demonstrates:

* Three.js scene composition
* Camera and controls integration
* Real-time animation loops (`requestAnimationFrame`)
* Texture mapping and materials
* Interactive DOM + WebGL integration
* Mathematical simulation of orbital motion

---

## 🚀 Deployment

Deployed using **Vercel**, ensuring:

* Fast global delivery
* Seamless static hosting
* Zero-config deployment pipeline

---

## 🔮 Future Enhancements

* 🌗 Add realistic lighting + shadows
* 🛰️ Introduce moons and satellites
* 🎛️ Add global time scaling control
* 📊 Display planetary data overlays
* 🌠 Improve realism with HDR environment maps

---

## 🤝 Contribution

Contributions are welcome. Fork the repository and submit a pull request with improvements or enhancements.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Pavan Kumar**

---

## ⭐ Summary

This project showcases a **fully interactive 3D simulation system** combining rendering, animation, and user-driven controls.

Developed as part of a **frontend assignment for an internship opportunity (EmptyCup via Internshala)**, it highlights strong capabilities in:

* Three.js and WebGL
* Interactive UI engineering
* Real-time simulation systems

Making it a solid demonstration of **frontend and 3D web development proficiency**.

---
s
