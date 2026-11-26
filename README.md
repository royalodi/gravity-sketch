# Gravity Sketch

> Interactive N-Body Astrophysics & Physics Dynamics Canvas

![Physics](https://img.shields.io/badge/Mechanics-N--Body_Gravitation-3b82f6?style=flat-square) ![Math](https://img.shields.io/badge/Integrator-Verlet_Symplectic-8b5cf6?style=flat-square) ![Canvas](https://img.shields.io/badge/Rendering-HTML5_Canvas_2D-10b981?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

![Gravity Sketch Official Banner](assets/banner.svg)

## 📌 Executive Overview
A real-time astrophysics and classical mechanics simulation platform featuring N-body gravitational integration, Keplerian orbital tracing, elastic Hookean spring meshes, and collision physics.

---

## 🏛 System Architecture
The following diagram highlights the internal computation pipeline, data transformations, and rendering passes:

![Architecture Diagram](assets/diagram.svg)

---

## 📷 Live Application Interface
Below is an authentic 1080p high-resolution capture of the live running interface:

![Live Interface](assets/screenshot.png)

---

## 🔬 Technical Deep-Dive
### Core Technical Specifications
- **N-Body Gravitational Computation:** Evaluates pair-wise gravitational attractions with distance softening factor $epsilon = 12.0$ to eliminate infinite force singularities at close proximities.
- **Symplectic Verlet Integration:** Utilizes Velocity Verlet numerical integration to maintain Hamiltonian energy conservation over extended simulation durations.
- **Orbital Path Forecaster:** Precomputes analytical two-body Keplerian trajectories and orbital velocities for drawn astronomical bodies.
- **Cloth and Spring Meshing:** Supports Hookean elastic spring-mass constraints for soft-body physics, ropes, and structural grids.

---

## 🚀 Quick Start Guide

### Zero-Dependency Launch
This project is built as a self-contained, high-performance HTML5 application with zero runtime dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/royalodi/gravity-sketch.git
   cd gravity-sketch
   ```

2. **Launch directly in any modern browser:**
   ```bash
   # Windows (PowerShell)
   Start-Process index.html

   # macOS / Linux
   open index.html || xdg-open index.html
   ```

---

## 📄 License
This project is distributed under the **MIT License**.


---

## 👨‍💻 Author & Lead Maintainer

<table>
  <tr>
    <td align="center" width="150" valign="middle">
      <a href="https://github.com/royalodi">
        <img src="https://github.com/royalodi.png" width="105" height="105" style="border-radius: 50%;" alt="royalodi" />
      </a>
      <br /><br />
      <b>Royal Odi</b><br />
      <sub><i>Full-Stack Engineer</i></sub>
    </td>
    <td valign="top">
      <p>
        Designed, engineered, and maintained by <b>Royal Odi</b>. Full-Stack Engineer focused on building scalable web architectures, robust backend systems, and responsive, high-performance digital experiences.
      </p>
      <p>
        <a href="https://github.com/royalodi"><img src="https://img.shields.io/badge/GitHub-royalodi-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub Profile" /></a>
        <a href="mailto:royalodi.dev@gmail.com"><img src="https://img.shields.io/badge/Email-royalodi.dev%40gmail.com-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Contact Email" /></a>
        <a href="https://github.com/royalodi?tab=repositories"><img src="https://img.shields.io/badge/Portfolio-Featured_Repositories-10b981?style=flat-square&amp;logo=codeforces&amp;logoColor=white" alt="Portfolio" /></a>
      </p>
    </td>
  </tr>
</table>

