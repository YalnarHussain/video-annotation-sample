## 🧰 Tools & Annotation Schema

* **Annotation Tool:** [VGG Image Annotator (VIA)](https://www.robots.ox.ac.uk/~vgg/software/via/)
* **Methodology:** Manual frame-by-frame tagging, temporal segmentation, and class-specific timestamping across multiple videos.
* **Output Format:** Structured JSON annotations exportable for ML model training pipelines.

---

### 🧠 Class Taxonomy (40 Classes per Video)

The annotation schema was structured into **three main categories** to support multi-label classification and temporal activity detection:

---

**🔧 Tool Interaction Classes**
*(Capturing tool usage and operational engagement)*

* 3'' Nail gun
* Clinch nail gun
* Hammer
* Saw
* Board spreader

---

**⚙️ Process & Task States**
*(Identifying repair stages, movement patterns, and manual handling of components)*

* Component replacement
* Component removal
* Maintenance only
* No repair
* Pull from conveyor
* Push to conveyor
* Pull from floor
* Push to floor

---

**🧱 Structural Components**
*(Tracking presence, usage, and assembly of physical parts and materials)*

* Long base boards (1–3)
* Short base boards (1–2)
* Top boards (1–9)
* Connector boards (1–3)
* Corner blocks (1–4)
* Support blocks

  * Small (1–2)
  * Large (1–2)
* Center block

---

**📂 Miscellaneous Class**

* Misc *(Used for outliers or non-critical visual segments not falling under above categories)*

