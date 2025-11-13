# MV52 3D Modeling Project (Blender)

> This repository archives a complete 3D scene built in Blender for the **MV52** (3D Modeling) course, part of the **"Monde Virtuel" (Virtual Worlds)** engineering specialization at UTBM.

---

## ⚠️ ATTENTION: Git LFS Required

This repository uses **[Git Large File Storage (LFS)](https://git-lfs.github.com/)** to manage the large `.blend` file (`Piana_Victor_MV52.blend`) which exceeds GitHub's 100MB file size limit.

**You must have Git LFS installed** to clone or download the 3D files correctly. If you clone without LFS, you will only download small text "pointer" files, not the actual 3D models.

### How to Clone This Repository

1.  **Install Git LFS** (if you haven't already):
    * [Download and install the Git LFS extension](https://git-lfs.com/).
    * Run this command **once per machine** to set it up:
        ```bash
        git lfs install
        ```

2.  **Clone the Repository:**
    * You can now clone the repository normally. Git LFS will automatically detect the `.gitattributes` file and download the large files during the checkout process.
        ```bash
        git clone [https://github.com/victorpiana/Blender.git](https://github.com/victorpiana/Blender.git)
        ```
    * If you have already cloned the repo *without* LFS, run `git lfs pull` from within the repository to download the large files.

---

## 🎯 Project Overview

The goal of this project was to create a complete, detailed, and coherent 3D scene from scratch. The final scene depicts a furnished house on a custom-designed volcanic island.

The project combines foundational objects required by the course assignment with numerous personal additions to create a unique and living world.

## ⚙️ Key Techniques & Features

This project served as a comprehensive application of a wide range of Blender's tools. Key techniques visible in the scene include:

* **Mesh Modeling:** Using fundamental operations like **Extrude**, **Bevel**, **Loop Cut**, and **Inset** for objects like the table, chairs, and kitchen.
* **Modifier-Based Workflow:** Heavy use of modifiers like **Mirror** (for cutlery), **Screw** (for glasses and plates), **Array** (for chair rungs), **Ocean** (for the sea), and **Solidify/Displace** (for complex objects).
* **Terrain Sculpting:** The entire volcanic island was sculpted by hand from a subdivided plane.
* **UV Mapping & Texture Painting:** Manual UV unwrapping (`Mark Seam`) and texture painting (using **Stencil**) were used for the apples and the island's terrain (to separate sand, grass, and rock).
* **Procedural Shading:** Creation of procedural materials for the lava, the metallic fruit bowl, and the **Nishita Sky Texture** used for the world's sunset lighting.
* **Particle Systems:** Used extensively for distributing vegetation, including:
    * **Hair** particles for grass, controlled by **Weight Painting**.
    * **Hair** particles (instancing objects) for the leaves on the maple trees.
    * **Particle** distribution for the pollen on the hibiscus flower.
* **Lighting & Rendering:** The scene is designed for both **Eevee** and **Cycles**, using **Glass BSDF** in Cycles for realistic glass refraction and an **Emission** shader for the lava.

## 📂 Scene Contents

The scene is composed of two main categories of objects, all detailed in the accompanying report:

### 1. Core Assignment Objects (TP)
* A complete dining set, including a **table**, **chairs**, **plates**, **cutlery** (forks, knives, spoons), and **wine glasses**.
* A **fruit bowl** containing texture-painted **apples**.

### 2. Personal Additions ("Hors Tps")
* **The Environment:** A **volcanic island** surrounded by an **animated ocean**.
* **The Interior:** A detailed **modern kitchen** with custom-modeled appliances, cabinets, and faucet.
* **Vegetation:** A **hibiscus flower** and **maple tree**, both modeled in detail and used in particle systems.
* **Bonus Objects:** A **Pokéball**, a **Katana**, a **lighthouse**, and a realistic mesh **trash can**.

---

## 👤 Author
**Victor Piana**

Engineering Student – Monde Virtuel (Virtual Worlds) Specialization
