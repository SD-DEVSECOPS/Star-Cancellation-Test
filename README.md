# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool designed to measure visuospatial attention, perceptual accuracy, and motor control.  
It is widely used in **neurology**, **neuropsychology**, and **cognitive research**, including studies on **Unilateral Spatial Neglect (USN)**.

<div align="center">

## 🚀 [CLICK HERE TO START TEST](https://sd-devsecops.github.io/Star-Cancellation-Test/CancellationOfConstellation.html)
**https://sd-devsecops.github.io/Star-Cancellation-Test/CancellationOfConstellation.html**

*(Alternative: [Object Cancellation Test](https://sd-devsecops.github.io/Star-Cancellation-Test/ObjectCancellation.html))*

</div>

---

## 📌 Overview

The test displays **small & large stars, letters, and words** randomly across an interactive canvas.

**Participant task:**  
Draw a stroke across each **small star** they detect.

The system automatically records:

- Correctly cancelled stars  
- **Cancellation order (first → last)**  
- **Stroke-by-stroke metrics**  
- **Stroke direction detection**  
- Left/right spatial distribution  
- **Laterality Index** & **USN classification**  
- Full statistical global summary  
- **CSV export** (UTF-8 BOM, multilingual safe)  
- **Pattern PNG export** (visualizing search strategy)

Researchers may configure object counts:

| Object Type | Recommended Range |
|-------------|------------------|
| Small stars | 50–80            |
| Large stars | 50–70            |
| Letters     | 10–30            |
| Words       | 10–20            |

---

## ⚙ Technical Specifications

### Precision Engine
The tool uses a **Geometric Line-Rectangle Intersection** algorithm rather than simple point sampling.
- **Accuracy**: Fast swipes or partial detections are registered with 100% mathematical precision.
- **Robustness**: Even if a stroke moves quickly across the screen, it will not "skip" over stars.

### Mobile Data Safety
Digital tests often suffer from data loss if the device is rotated. This tool features **Smart Resize Protection**:
- If the screen rotates or the address bar toggles, the test **preserves the current state**.
- The canvas does not reset, ensuring the patient's progress is never lost due to device handling.

---

## 🌐 Cross-Platform Compatibility

Compatible with all modern browsers:
- ✔ Desktop & laptop (mouse input)  
- ✔ Mobile phones  
- ✔ Tablets / iPad  
- ✔ Touch-safe pointer control (blocks native scrolling)  
- ✔ No external libraries required  

---

## 🧪 How to Use

1. **Setup**: Adjust object counts (stars/words) and set a timeout duration. 
2. **Start**: Press **Start Test**.
3. **Execution**: Patient draws lines through the small stars.
4. **Finish**: Press **Finish Test** or wait for timeout.
5. **Analyze**:
   - View on-screen Heatmap and Stats.
   - Enter Patient Info (Name/Age).
   - Download **CSV** for statistical analysis.
   - Download **Pattern PNG** for visual search path reconstruction.

### Export Options

#### 📄 **CSV Export**
Detailed dataset including: Laterality Index, USN Classification, Time-per-star, and precise coordinates of every single stroke.

#### 🧭 **Pattern PNG Export**
A visual map of the patient's performance:
- **Green Lines**: Correct hits.
- **Red Lines**: Misses/False positives.
- **Arrows**: Show the exact sequence and direction of movement (e.g., did they scan Left-to-Right or chaotic?).
- **Markers**: Show positions of all target stars to easily spot omissions (neglect).

---

## ⚖ License
This project is open-source for **research**, **educational**, and **clinical development** purposes.

---

## 📚 **Required Citation**

If you use this tool in **research**, **clinical evaluation**, **academic studies**, or **publications**,  
you are **required to cite** the project to acknowledge its use and support continued development.

Please use the following provisional citation:
> For citation inquiries or academic use, contact: **sdswat93@gmail.com**

---

## ⚠ Ethical & Usage Disclaimer

To ensure responsible and ethical use, the following conditions apply:

### 🏥 Clinical Use
- This tool **does not replace** standardized or professionally validated diagnostic instruments.  
- Interpretation must only be performed by a **licensed clinician**, **neuropsychologist**, or a **qualified specialist**.  
- All assessment outcomes must be **independently verified** before being used in any clinical or medical decision-making.  
- Users must obtain **informed consent** from participants and appropriate **ethical approval** for all human-subject testing.

### 🔬 Research Use
Researchers using this tool must:
- Obtain **IRB / Ethics Committee approval** where required  
- Follow local and international data protection regulations (e.g., **GDPR**, **HIPAA**)  
- Properly **cite this project** in publications  

### 💼 Commercial Use
Commercial use of this software is **not permitted** without **explicit written authorization** from the project author.

For licensing discussions, institutional deployment, or collaboration requests, contact:
📧 **sdswat93@gmail.com**

---

### ✅ User Agreement
By using this tool, you agree to:
- Follow all ethical guidelines listed above  
- Obtain all required permissions  
- Use the results responsibly within the limits of the tool  

Failure to follow these terms may result in misuse and invalidation of collected data.

---

**Project by:** *Zengin, M.*
