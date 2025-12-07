# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control.  
It is widely used in **neurology**, **neuropsychology**, and **cognitive research**, including evaluations of **Unilateral Spatial Neglect (USN)**.

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
  - Left→Right  
  - Right→Left  
  - Top→Bottom  
  - Bottom→Top  
- Left/right cancellation distribution  
- **Laterality Index calculation**  
- **USN classification**  
- Full statistical summary  
- **CSV export** (UTF-8 BOM for multilingual support)  
- **PNG export** of the final canvas  
- **NEW: Pattern PNG export**  
  - Green = correct stroke  
  - Red = incorrect stroke  
  - Midpoint-to-midpoint **arrows** for scanning-path visualization  
  - Faint small-star reference markers  

Researchers can configure the number of displayed items:

| Object Type | Recommended Range |
|-------------|------------------|
| Small stars | 50–80            |
| Large stars | 50–70            |
| Letters     | 10–30            |
| Words       | 10–20            |

> ✔ Intelligent placement algorithm ensures balanced distribution and avoids overlaps.

---

## 🌐 Cross-Platform Compatibility

Runs fully in any modern web browser:

- ✔ Desktop (mouse)  
- ✔ Mobile phones (touch)  
- ✔ Tablets / iPad  
- ✔ Responsive scaling  
- ✔ Safe pointer handling  
- ✔ No installations or external libraries required  

---

## 🧪 How to Use

**Live Test Page:**  
https://sd-devsecops.github.io/Star-Cancellation-Test/CancellationOfConstellation.html

1. (Optional) Adjust object counts.  
2. Select test duration.  
3. Click **Start Test**.  
4. Participant performs cancellations by drawing strokes.  
5. When finished:
   - Results are displayed  
   - Cancellation order is shown  
   - Full stroke table appears  
   - User enters:
     - Name  
     - Surname  
     - Age  

### Export options

#### ✅ **CSV Export**
Contains:

- Participant demographics  
- Configuration data  
- Correct / missed counts  
- Left vs. right cancellations  
- Laterality Index  
- USN classification  
- Duration  
- Mean cancellation time  
- Stroke list (direction + correctness)  
- Cancellation order  

#### ✅ **PNG Export**
Saves the exact final test canvas.

#### ✅ **Pattern PNG Export (NEW)**
Creates a research-grade visualization:

- Green / red strokes  
- Stroke numbers  
- Scan-path arrows  
- Light small-star markers  

Useful for:

- Neuropsychological analysis  
- Clinical documentation  
- Behavioral mapping  
- Research data reporting  

---

## ✨ Features

- English, Türkçe, Deutsch interface  
- Non-overlapping randomized placement  
- Demo / training stars  
- Missed-star highlighting  
- Cancelled-star ID labeling  
- Stroke numbering & direction detection  
- High-resolution PNG exports  
- UTF-8 CSV support  
- Scanning-pattern visualization (NEW)  
- Works fully offline  
- No dependencies — pure HTML + JavaScript  

---

## ⚖ License

This project is open-source and free for **research**, **educational**, and **clinical development** use.

---

## 📚 Citation (Required for Research Use)

If you use this tool in **any academic publication, thesis, clinical study, research project, or presentation**,  
**you must cite this project** to acknowledge the development effort and ensure traceable scientific use.

**Recommended Citation Format:**

> **Zengin, M. (2025). Star Cancellation Test (SCT) — Web-based visuospatial assessment tool.  
> GitHub Repository: https://github.com/sd-devsecops/Star-Cancellation-Test**

For citation questions or collaboration requests:  
📧 **sdswat93@gmail.com**

---

## ⚠ Ethical Disclaimer

For clinical or research use:

- Ensure relevant **ethics approval**  
- Obtain **informed consent**  
- Validate exported data independently  
- Interpret results only with appropriate clinical or academic training  

---

**Project by:** *Zengin, M.*  
**Enhanced by:** *ChatGPT*
