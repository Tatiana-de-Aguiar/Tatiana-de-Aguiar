# Hi, I'm Tatiana de Aguiar 👋

**Senior Fullstack Engineer | 3D Graphics Specialist | Product Engineer**

I don’t just write code; I build products that solve real-world problems. My expertise lies in uniting computational mathematics, high-performance 3D rendering, and scalable web architecture to create complex interactive ecosystems.

I operate at the intersection of **Software Engineering and Product Vision**, making architectural decisions that prioritize application efficiency, user experience, and business value.

---

## 🔬 Project Spotlight: 3D Interactive Clinical Ecosystem

Currently, I am the lead engineer behind the development of a proprietary **3D Clinical Ecosystem**, focused on elevating the standard of diagnosis and care for Massage Therapy, Acupuncture, and Chiropractic professionals.

> 🔒 *Note: This project's repository is private as it contains proprietary clinical and architectural intellectual property.*

> 🎥 **[Click here to watch the technical and clinical demonstration on my LinkedIn]: https://www.linkedin.com/posts/tatianadeaguiar_fullstackengineer-spatialintelligence-clinicalsoftware-ugcPost-7441929233200844800-kNBD?utm_source=share&utm_medium=member_desktop&rcm=ACoAACwuJYwBrVjufOlAS3nH3ty2sGchCAKk3Hk)**

### The Business and Clinical Challenge
Healthcare professionals visualize the human body in 3D but traditionally record data in 2D. The challenge was to build a clinical precision tool, not just a visual model, that serves as an "interactive map" for therapeutic point mapping, postural analysis, and clinical dossier organization, all rendered natively in the browser without performance loss.

### Engineering Solutions & Decision Making (CTO View)

* **Computational Mathematics & Spatial Raycasting:** I developed a precision system based on spatial calculation (via worldToLocal) and vector intersection. This allows for the surgical clicking and recording of acupuncture points and trigger points directly on the 3D mesh, maintaining coordinate accuracy regardless of camera rotation or zoom level.
* **Targeted Rendering & Smart Shading:** To ensure near-instant browser loading, I eliminated the use of traditional massive textures. I designed a code-based "Smart Shading" engine (React Three Fiber + PBR) that focuses processing power on the structural sharpness of bones and nerves. This architectural decision creates high visual contrast between the skeletal/nervous systems (rendered with high-quality light physics) and soft tissues (kept schematic). The result is a clinical interface where critical areas for chiropractic adjustments and nerve mapping stand out, delivering diagnostic clarity at a fraction of the memory cost.
* **Strongly Typed Data Architecture:** I structured the ecosystem using rigorous TypeScript. Every bone, muscle, or nerve is not just a mesh, but a trackable data entity. This allows for associating laterality, pathologies, and clinical history directly with 3D geometry in a scalable manner.

---

## 🛠️ Tech Stack & Expertise

### Core 3D & WebGL
* **Three.js & React Three Fiber (R3F):** Scene Graph manipulation, PBR Materials, Lighting, Tone Mapping.
* **3D Mathematics:** Applied linear algebra, transformation matrices, quaternions, raycasting.
* **Asset Optimization:** GLB/GLTF pipeline management, geometry compression, vertex colors.

### Fullstack & Architecture
* **Frontend:** React, TypeScript, complex state management coupled with the 3D canvas.
* **Backend:** Node.js, API construction for spatial and clinical data persistence.
* **Practices:** Clean Architecture, Code as Design, Performance Profiling.

---

## 💡 Engineering Philosophy

1. **Tools should be invisible:** The user (clinician/therapist) should focus on the patient, not the interface. I reduce friction through fluid UX and native interactions.
2. **Code works for the Product:** A complex architecture only makes sense if it generates real utility. I trade "overengineering" for efficient solutions that deliver the expected ROI.
3. **Precision is non-negotiable:** In healthcare contexts, the accuracy of visual information and data storage dictates the tool's authority.

---

### 📬 Let's Connect

Always open to discussing software architecture, WebGL innovations, and how 3D technology can transform products.
* [LinkedIn]: https://www.linkedin.com/in/tatianadeaguiar/?locale=en-US
