# 🌍 Animated 3D Globe 

An interactive, animated 3D globe built with **HTML, CSS and JavaScript**. The Earth is rendered as a sphere of colored dots that you can rotate, and you can click anywhere on the land to drop a pointer that shows the exact latitude and longitude of that spot.

##  Features

- 3D globe made of dots, with land colored by terrain (greens, browns, greys) and oceans left faint
- Smooth, continuous rotation animation
- Click anywhere on the globe to add a pointer
- Tooltip label showing the **latitude / longitude** of the clicked point (e.g. `40.1524° N, 69.3212° E`)
- Lightweight: no build step, runs directly in the browser

## 📁 Project Structure

```
Animated-3D-Globe/
├── .vscode/
│   └── settings.json   # Editor settings (e.g. Live Server config)
├── index.html          # Page markup and canvas/container for the globe
├── script.js           # Globe rendering, rotation and click-to-pointer logic
├── style.css           # Layout and styling
└── README.md           # You are here
```

##  Getting Started

### Prerequisites

- A modern web browser (Chrome, Edge, Firefox, Safari)
- (Optional) [VS Code](https://code.visualstudio.com/) with the **Live Server** extension

### Run Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/hridesh-thakur/Locate-your-coordinate.git
   cd Locate-your-coordinate
   ```
2. Open `index.html` in your browser, **or** right-click it in VS Code and choose **Open with Live Server**.

##  How to Use

| Action | Result |
| ------ | ------ |
| Open the page | The globe starts rotating automatically |
| Click on the globe | A pointer is placed and its coordinates are displayed |
| Click elsewhere | Move or add another pointer |

##  Built With

- **HTML5** – structure
- **CSS3** – styling
- **JavaScript** – rendering, animation and interaction

##  Customization

- **Dot size / density:** adjust the dot spacing and radius values in `script.js`
- **Colors:** change the land color palette in `script.js`
- **Rotation speed:** tweak the rotation increment in the animation loop
- **Pointer style:** edit the pointer and tooltip rules in `style.css`

##  Roadmap

- [ ] Drag to rotate manually
- [ ] Zoom in / out

## 🤝 Contributing

Contributions, issues and feature requests are welcome. Fork the repo, create a branch, and open a pull request.

##  Author

**Hridesh Thakur**
