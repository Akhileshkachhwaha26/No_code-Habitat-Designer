# No_code Habitat Designer

An interactive, web-based 3D tool for prototyping and designing space habitats. Build planetary bases or orbital stations, plan interior layouts, and visualize your designs in a 3D environment.

## Features

- **3D Visualization:** Explore your habitat design in a fully interactive 3D viewport powered by Three.js. Switch between 3D perspective and precise 2D top-down views.
- **Mission Parameters:** Customize your destination (Mars, Moon, Low Earth Orbit), adjust crew size, and set mission duration to contextualize your design.
- **Parametric Habitats:** Choose your core habitat shell shape (Cylinder, Box, or Dome) and adjust dimensions (width and length) dynamically.
- **Object Placement:** Populate your habitat with various functional modules and objects:
  - **Private Quarters:** Sleep, Hygiene
  - **Common Areas:** Galley, Recreation
  - **Work & Science:** Lab, Workshop
  - **Health & Operations:** Medical, Gym, Airlock
  - **Props:** Stowage, Plant Growth, Astronaut scale references
- **Transform Controls:** Select placed items to intuitively move, rotate, and scale them to perfect your layout using on-screen gizmos or keyboard shortcuts (M, R, S).
- **Undo/Redo:** Built-in history management (Ctrl+Z / Ctrl+Y) to easily fix mistakes.
- **Save & Load:** Save your progress locally in the browser and load it back later to continue designing.
- **Auto-Layout:** Use the intelligent layout generator (`✨ Generate Layout`) to quickly block out initial module placements.

## How to Use

The application is entirely client-side. No installation, build process, or local server is required.

1. Clone or download this repository.
2. Open `Habitat_Designer.html` directly in your modern web browser (e.g., Chrome, Firefox, Edge).
3. Log in (or continue as a Guest).
4. Start designing by configuring your mission parameters and clicking **Create Habitat**!

## Controls & Hotkeys

- **Camera Navigation:**
  - `Left Click + Drag`: Rotate camera
  - `Right Click + Drag`: Pan camera
  - `Scroll Wheel`: Zoom in/out
- **Object Manipulation:**
  - `M`: Move mode
  - `R`: Rotate mode
  - `S`: Scale mode
  - `Del`: Delete selected object
  - `Ctrl + Z`: Undo
  - `Ctrl + Y`: Redo

## Technologies Used

- **HTML5 & CSS3**
- **JavaScript (ES6+)**
- [**Three.js**](https://threejs.org/) for 3D graphics and rendering
- [**Tailwind CSS**](https://tailwindcss.com/) for rapid UI styling
