# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool designed to measure visuospatial attention, perceptual accuracy, and motor control.  
It is widely used in **neurology**, **neuropsychology**, and **cognitive research**, including studies on **Unilateral Spatial Neglect (USN)**.

---

## 📌 Overview

The test displays **small & large stars, letters, and words** randomly across an interactive canvas.

**Participant task:**  
Draw a stroke across each **small star** they detect.

The system automatically records:

- Correctly cancelled stars  
- **Cancellation order (first → last)**  
- **Stroke-by-stroke metrics**  
- **Stroke direction detection** (Left→Right, Right→Left, Top→Bottom, Bottom→Top)  
- Left/right spatial distribution  
- **Laterality Index**  
- **USN classification**  
- Full statistical summary  
- **CSV export** (UTF-8 BOM, multilingual safe)  
- **PNG export**  
- **NEW: Pattern PNG export**  
  - Green = correct (hit ≥1 star)  
  - Red = incorrect  
  - Arrows showing visual scanning path  
  - Light markers showing all small stars  

Researchers may configure object counts:

| Object Type | Recommended Range |
|-------------|------------------|
| Small stars | 50–80            |
| Large stars | 50–70            |
| Letters     | 10–30            |
| Words       | 10–20            |

> ✔ Smart placement algorithm prevents overlapping and ensures even spatial distribution.

---

## 🌐 Cross-Platform Compatibility

Compatible with all modern browsers:

- ✔ Desktop & laptop (mouse input)  
- ✔ Mobile phones  
- ✔ Tablets / iPad  
- ✔ Responsive canvas scaling  
- ✔ Touch-safe pointer control  
- ✔ No external libraries required  

---

## 🧪 How to Use

**Live Test Page:**  
https://sd-devsecops.github.io/Star-Cancellation-Test/CancellationOfConstellation.html

1. Optionally adjust counts of stars, letters, and words.  
2. Select test duration.  
3. Press **Start Test**.  
4. Participant draws strokes directly on the canvas.  
5. Upon timeout or pressing **Finish Test**, the system displays:
   - Summary statistics  
   - Cancellation order  
   - Stroke direction table  
   - Input fields for:
     - Name  
     - Surname  
     - Age  

### Export Options

#### 📄 **CSV Export**
Includes:
- Participant data  
- Object configuration  
- Cancellation totals  
- Left/right distribution  
- Laterality Index  
- USN classification  
- Test duration  
- Average cancellation time  
- Complete stroke dataset  
- Full cancellation order  

#### 🖼️ **PNG Export**
Saves the final visual state of the canvas.

#### 🧭 **Pattern PNG Export (NEW)**
Ideal for:
- Clinical assessment  
- Research visualizations  
- Behavioral pattern mapping  

Includes:
- Green/red stroke coloring  
- Arrow-based visual scanning path  
- Stroke numbering  
- Light background markers for all stars  

---

## ✨ Features

- English, Türkçe, Deutsch language support  
- Non-overlapping randomized placement  
- Demo stars  
- Missed stars highlighted  
- Cancelled stars labeled  
- Stroke numbering and direction analysis  
- High-resolution PNG export  
- UTF-8 CSV export  
- Pattern-analysis visualization  
- Pure HTML + JavaScript (zero dependencies)

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

## ⚠ Ethical Disclaimer

For clinical or research use:

- Obtain appropriate **ethics approval**  
- Secure **informed consent**  
- Independently verify exported data accuracy  
- Ensure interpretation by trained professionals  

---

**Project by:** *Zengin, M.*  
**Enhanced by:** *ChatGPT*
