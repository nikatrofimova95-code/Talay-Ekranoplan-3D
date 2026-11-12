# 🚀 Propulsion System Modification: Talay Ekranoplan

This branch serves as an engineering addition to the base geometry of the Talay unmanned ekranoplan (`main`). It demonstrates detailed propulsion unit design, brushless motor integration, and a separable nacelle construction optimized for 3D printing.

---

## 📐 1. General Technical Parameters
- **Project Type:** Unmanned Ekranoplan (ground-effect vehicle).
- **Model Scale:** All components and STL files were designed and exported from Blender using a scale factor of **0.05**.
- **Design Environment:** Blender (configured with Ukrainian interface localization).

---

## 🖼️ 2. General View of the Updated Ekranoplan
Below is the general view of the assembled unmanned ekranoplan model in Blender featuring the integrated updated engine nacelles:

![General View of Ekranoplan 1](images/Знімок%20екрана%202026-11-12%20161735.png)

![General View of Ekranoplan 2](images/Знімок%20екрана%202026-11-12%20161756.png)

---

## 🛠️ 3. Nacelle Structural Modifications & Details
This version implements a complete design cycle for the rear nacelle to meet practical assembly requirements:

### Motor Mounting Face
A precise mounting plane with fastener holes and a central wiring channel for power cable routing has been formed on the rear wall of the nacelle.

![Motor Mounting Face (Rear Wall)](images/Знімок%20екрана%202026-11-12%20161829.png)

### Front Cowling & Joint Groove
The structure is split into two separate parts for convenient 3D printing and assembly. Due to the minimal wall thickness, using mechanical screws in this joint area is unfeasible. Therefore, a **3 mm deep cylindrical stepped lap joint groove** has been engineered at the interface for reliable adhesive bonding.

![Front Cowling](images/Знімок%20екрана%202026-11-12%20161838.png)
![3 mm Joint Groove](images/Знімок%20екрана%202026-11-12%20161916.png)

---
## ⚙️ 4. Detailed Propulsion Specifications

Since aerodynamic blades and heavy brushless motors are standardized high-precision industrial products, they do not require manual CAD modeling and are included in the project as strict technical specifications and documentation.

### Electric Motor: T-Motor U8 II KV100

![T-Motor U8 II Motor](images/Знімок%20екрана%202026-11-12%20163037.png)

- **Purpose:** High-power industrial brushless motor designed specifically for heavy-duty multirotors, long-endurance UAVs, and experimental ekranoplans.
- **Key Specifications:** 
  * Low KV rating (KV100) optimized for large propellers operating under high voltage (high-capacity LiPo batteries).
  * High torque at low and medium RPM, which is critical for overcoming water drag during ekranoplan takeoff.
  * Industrial-grade dustproof and waterproof housing construction reliably protects internal windings from water splashes and moisture during surface operations.
  * Mounting interface with standard hub hole patterns (15/16 mm, M3 fasteners), perfectly integrated into the engineered rear nacelle wall.

### Carbon Fiber Propellers: T-Motor Folding Carbon Fiber (28.2 × 9.2)

![T-Motor Carbon Fiber Propellers](images/Знімок%20екрана%202026-11-12%20163222.png)

- **Design Type:** Folding carbon fiber dual-blade propellers.
- **Key Specifications & Advantages:**
  * Dimensions: **28.2 × 9.2 inches**, engineered for direct synergy with T-Motor U8 series motors.
  * Material: High-modulus carbon fiber providing exceptional bending rigidity at minimal weight with zero deformation at maximum operating speeds.
  * Folding blade design reduces aerodynamic drag during gliding or when the propulsion system is inactive, while also simplifying transport and storage.
  * High aerodynamic efficiency of the profiled blade guarantees maximum static thrust for dynamic ekranoplan transition into ground-effect mode.

---

## 📂 5. Repository Structure
- `stl_files/` — folder containing updated STL files (scale factor **0.05**).
- `images/` — folder containing all visual assets and screenshots.
- `ekranoplan02` — Blender project file.
- `README.md` — technical documentation and branch overview.

---

## 🚀 How to Open & Requirements
1. **Blender Project (`ekranoplan02`):** 
   * Recommended to open using **Blender 5.0.1** (or compatible 5.x versions) to correctly inspect meshes, modifiers, and scene structure.
2. **STL Files (`.stl`):** 
   * Can be opened in any standard 3D viewer, CAD software, or slicer (such as Cura or PrusaSlicer) for prototyping or 3D printing individual parts and assemblies. Keep the **0.05 scale** and **0.5 mm wall thickness** parameters in mind during preparation.

