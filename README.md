# ❄️ SnowGlobe

An interactive **web-based 3D snow globe** built with **HTML**, **JavaScript**, and **Three.js**.  
This project demonstrates the fundamentals of 3D rendering, particle systems, lighting, and camera control in a browser environment — no additional frameworks or build tools required.

---

## 🎯 What it is   
**SnowGlobe** is a lightweight, real-time 3D visualization that simulates a decorative snow globe scene.  
The application renders a transparent sphere containing a snowy landscape and dynamically falling snow particles. Users can freely rotate and zoom the camera to explore the environment from any angle.  

---

## 🧩 Features  
- 🌨️ **Real-time snow particle system** — hundreds of small white particles simulating snow inside the globe.  
- 🪞 **Physically accurate lighting** — point and ambient lights for realistic reflection and shading.  
- 🏔️ **Textured 3D environment** — customizable ground, trees, and interior objects (`textures/` folder).  
- 🕹️ **Interactive camera controls** — drag to orbit, scroll to zoom, smooth damping for natural motion.  

---

## 🧠 Technologies Used  
- **[Three.js](https://threejs.org/)** – main 3D rendering engine  
- **JavaScript (ES6)** – logic and scene control  
- **HTML5 Canvas** – rendering surface 
- **Node.js**
---

## 🚀 How to run  
1. Clone the repository:    
   ```bash  
   git clone https://github.com/Avuii/SnowGlobe.git
     
2. Open index.html in your browser, or use a simple HTTP server:  
   cd SnowGlobe   
   python3 -m http.server 8000
   
4. Navigate in your browser to http://localhost:8000/.  

---

## 📂 Repository structure
SnowGlobe/
├── index.html          
├── textures/           
├── .gitattributes  
├── LICENSE             
├── README.md          
└── node_modules/ 

---

## 🧑‍💻 Author
Created for educational purposes by Avui.


