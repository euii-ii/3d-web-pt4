# 3d-web-pt4

## Overview
This project demonstrates how to create an interactive 3D website using HTML, CSS, and Three.js. Three.js is a JavaScript library that makes it easy to render 3D graphics in the browser using WebGL.

## Features
- Interactive 3D models
- Smooth animations
- User-friendly UI/UX
- Lightweight and efficient

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Three.js

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/euii-ii/3d-web-pt4.git
   ```
2. Navigate to the project folder:
   ```sh
   cd 3d-website
   ```
3. Open `index.html` in your web browser.

## Usage
- Customize the 3D models by modifying the `scene.js` file.
- Adjust styles in `styles.css`.
- Add interactive elements using JavaScript.

## File Structure
```
3d-website/
│── index.html        # Main HTML file
│── styles.css        # Styling for the website
│── script.js         # Main JavaScript file
│── scene.js          # Three.js scene setup
│── assets/           # 3D models and textures
│── README.md         # Project documentation
```

## Getting Started with Three.js
1. Include Three.js in your project:
   ```html
   <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
   ```
2. Create a basic scene:
   ```js
   const scene = new THREE.Scene();
   const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
   const renderer = new THREE.WebGLRenderer();
   renderer.setSize(window.innerWidth, window.innerHeight);
   document.body.appendChild(renderer.domElement);
   ```
3. Add objects, lights, and animation.

## License
This project is licensed under the MIT License.

