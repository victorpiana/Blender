# MV52 3D Modeling Project (Blender) - 2024

> This repository archives a complete 3D scene built in Blender for the **MV52** (3D Modeling) course, part of the **"Monde Virtuel" (Virtual Worlds)** engineering specialization at UTBM.

[![Software](https://img.shields.io/badge/Software-Blender-orange.svg)](https://www.blender.org/)
[![Version](https://img.shields.io/badge/Blender-3.x-blue.svg)](https://www.blender.org/download/)
[![Storage](https://img.shields.io/badge/Storage-Git_LFS-red.svg)](https://git-lfs.github.com/)
[![Render](https://img.shields.io/badge/Render-Cycles_|_Eevee-green.svg)](https://docs.blender.org/manual/en/latest/render/index.html)

---

## ⚠️ ATTENTION: Git LFS Required

This repository uses **[Git Large File Storage (LFS)](https://git-lfs.github.com/)** to manage the large `.blend` file (`Piana_Victor_MV52.blend`) which exceeds GitHub's 100MB file size limit.

**You must have Git LFS installed** to clone or download the 3D files correctly. If you clone without LFS, you will only download small text "pointer" files, not the actual 3D models.

### How to Clone This Repository

1.  **Install Git LFS** (if you haven't already):
    * [Download and install the Git LFS extension](https://git-lfs.com/)
    * Run this command **once per machine** to set it up:
        ```bash
        git lfs install
        ```

2.  **Clone the Repository:**
    * You can now clone the repository normally. Git LFS will automatically detect the `.gitattributes` file and download the large files during the checkout process:
        ```bash
        git clone https://github.com/victorpiana/Blender.git
        cd Blender
        ```
    * If you have already cloned the repo *without* LFS, run `git lfs pull` from within the repository to download the large files.

---

## 🎯 Project Overview

The goal of this project was to create a complete, detailed, and coherent 3D scene from scratch. The final scene depicts a **furnished house on a custom-designed volcanic island**, combining foundational objects required by the course assignment with numerous personal additions to create a unique and living world.

**Key Achievement**: A fully realized 3D environment showcasing advanced Blender techniques including mesh modeling, procedural shading, particle systems, and realistic rendering.

---

## 📁 Repository Contents

* **`Piana_Victor_MV52.blend`**: Complete Blender project file (requires Git LFS)
* **Project Report (PDF)**: Comprehensive documentation with screenshots and technical explanations (if included)

---

## ⚙️ Key Techniques & Features

This project served as a comprehensive application of a wide range of Blender's tools:

### Mesh Modeling
* **Fundamental Operations**: Extrude, Bevel, Loop Cut, and Inset for objects like tables, chairs, and kitchen elements
* **Precision Modeling**: Complex geometries for cutlery, glassware, and architectural elements

### Modifier-Based Workflow
* **Mirror**: Symmetrical modeling for cutlery
* **Screw**: Circular objects like glasses and plates
* **Array**: Repetitive elements like chair rungs
* **Ocean**: Animated water simulation
* **Solidify/Displace**: Complex surface details

### Terrain & Environment
* **Terrain Sculpting**: Hand-sculpted volcanic island from a subdivided plane
* **UV Mapping & Texture Painting**: 
  - Manual UV unwrapping using `Mark Seam`
  - Texture painting with **Stencil** for apples and terrain
  - Separation of sand, grass, and rock textures on island

### Advanced Shading
* **Procedural Materials**: 
  - Realistic lava material with emission
  - Metallic fruit bowl shader
  - **Nishita Sky Texture** for authentic sunset lighting
* **Glass BSDF**: Realistic glass refraction in Cycles renderer

### Particle Systems
* **Hair Particles**: 
  - Grass distribution controlled by **Weight Painting**
  - Maple tree leaves instancing
* **Particle Distribution**: Pollen on hibiscus flower

### Rendering
* **Dual Renderer Support**: Optimized for both **Eevee** (realtime) and **Cycles** (raytracing)
* **Advanced Lighting**: Natural sunset atmosphere with procedural sky

---

## 🏝️ Scene Contents

### 1. Core Assignment Objects (TP Requirements)

**Dining Set:**
* Complete table with detailed legs and surface
* Four matching chairs with proper geometry
* Ceramic plates modeled with Screw modifier
* Full cutlery set (forks, knives, spoons) using Mirror modifier
* Wine glasses with realistic glass material
* Metallic fruit bowl with procedural shader
* Hand-painted apples with custom UV maps

### 2. Personal Additions ("Hors TP")

**Environment:**
* **Volcanic Island**: Hand-sculpted terrain with lava flow
* **Animated Ocean**: Dynamic water simulation with foam
* **Nishita Sky**: Procedural sunset atmosphere

**Interior Architecture:**
* **Modern Kitchen**: 
  - Custom-modeled appliances
  - Detailed cabinets and drawers
  - Realistic faucet with metal shader

**Vegetation:**
* **Hibiscus Flower**: Detailed petals and stamens with particle pollen
* **Maple Trees**: Complete with particle-based leaf system

**Bonus Objects:**
* **Pokéball**: Accurate geometry and materials
* **Katana**: Detailed sword with proper edge flow
* **Lighthouse**: Architectural structure with emission light
* **Trash Can**: Realistic mesh with proper topology

---

## 🚀 Getting Started

### Prerequisites

* **Blender 3.x or higher** installed ([Download here](https://www.blender.org/download/))
* **Git LFS** installed and configured
* Minimum 4GB RAM recommended
* GPU with OpenGL 4.3+ for optimal Eevee performance

### Opening the Project

1. Clone the repository with Git LFS (see instructions above)
2. Open Blender
3. Go to `File > Open` and select `Piana_Victor_MV52.blend`
4. Choose your preferred renderer:
   - **Eevee**: Fast realtime preview (recommended for editing)
   - **Cycles**: High-quality raytraced renders (recommended for final output)

### Rendering Tips

* **Eevee**: Enable Ambient Occlusion, Bloom, and Screen Space Reflections in render settings
* **Cycles**: Use GPU compute for faster rendering if available
* The scene is optimized for 1920x1080 resolution

---

## 📸 Scene Highlights

The project showcases several technically challenging elements:

* **Procedural Lava**: Custom shader network with animated emission
* **Grass System**: Over 10,000 grass blades distributed via weight painting
* **Ocean Simulation**: Realistic wave motion and foam
* **Sunset Lighting**: Volumetric atmosphere using Nishita sky model
* **Glass Physics**: Accurate refraction and caustics in Cycles

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

* **Polygon Modeling**: Creating clean, efficient mesh topology
* **UV Unwrapping**: Manual seam placement and texture coordination
* **Procedural Texturing**: Building complex shader networks
* **Particle Systems**: Managing large-scale instancing and distribution
* **Lighting & Composition**: Creating atmospheric and believable scenes
* **Render Optimization**: Balancing quality and performance

---

## 👤 Author

**Victor Piana**  
Engineering Student – Monde Virtuel (Virtual Worlds) Specialization, UTBM

---

## 📄 License

This project is part of an academic curriculum at UTBM and is provided for educational purposes.

---
