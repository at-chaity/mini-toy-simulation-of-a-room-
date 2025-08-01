
# 🧪 Mini Toy Simulation of a Room

A simple yet insightful 2D simulation modeling pollutant dispersion inside a **1m × 1m** box—imagined as a tiny room. Pollutants enter through a small hole (imagined as a window) in the boundary, while the rest of the walls maintain no-flux (**Neumann**) boundary conditions. The simulation explores how different injection profiles affect pollutant spread using numerical methods.

---

## 🧠 Concept

- 📦 **Room setup**: 1m × 1m box with Neumann BCs
- 🕳️ **Opening**: A tiny hole on the boundary to inject pollutants
- 💨 **Injection types**:
  - Step function
  - Gaussian pulse
- 🔁 **Scenario change**: Hole size is increased to observe changes in dispersion

---

## 🧮 Numerical Methods

| Component    | Method Used             |
|-------------|--------------------------|
| Time Stepping | ⏱️ Forward Euler (Explicit) |
| Diffusion    | ♻️ Crank–Nicolson (Semi-Implicit) |
| Advection    | ➡️ Upwind Scheme (Explicit)   |

These choices balance stability and accuracy for advection-diffusion dynamics.

---
## 🛠️ Tech Stack

- 🐍 Python 3
- 🔢 NumPy
- 📊 Matplotlib
- ⚙️ SciPy (for sparse solvers)
- 📓 Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/at-chaity/mini-toy-simulation-of-a-room-.git
2. Open 2D_box_simulation.ipynb in Jupyter Notebook.

- Run the cells step-by-step to:

- Initialize grid and parameters

- Inject pollutants

3. Visualize
---

##🖼️ Output
Sample visualizations:

✅ Step Function Injection

🌊 Gaussian Pulse Injection

---

🤝 Acknowledgments
This is a toy problem crafted for learning and visualization purposes. Feel free to fork, star ⭐, or contribute if you find it helpful!
