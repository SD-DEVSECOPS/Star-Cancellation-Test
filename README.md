# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control.  
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
- **Stroke direction detection**  
  - Left→Right  
  - Right→Left  
  - Top→Bottom  
  - Bottom→Top  
- Left/right cancellation distribution  
- **Laterality Index calculation**  
- **USN classification**  
- Full statistical summary  
- **CSV export** (UTF-8 BOM for multilingual compatibility)  
- **PNG export** of the final test canvas  
- **NEW: Pattern PNG export**  
  - Shows each stroke in **clinical colors**:  
    - Green = correct (hit ≥ 1 small star)  
    - Red = incorrect  
  - Displays midpoint-to-midpoint **arrows** representing the participant’s visual scanning path  
  - Light context markers for all small stars  

Researchers may configure object counts:

| Object Type | Recommended Range |
|-------------|------------------|
| Small stars | 50–80            |
| Large stars | 50–70            |
| Letters     | 10–30            |
| Words       | 10–20            |

> ✔ Random placement algorithm prevents overlap and distributes items evenly across the canvas.

---

## 🌐 Cross-Platform Compatibility

The SCT runs inside any modern browser and supports:

- ✔ Desktop (mouse input)  
- ✔ Mobile (touch input)  
- ✔ iPad / tablets  
- ✔ Responsive canvas scaling  
- ✔ Multi-touch–safe pointer handling  
- ✔ No external libraries required  

---

## 🧪 How to Use

**Live Test Page:**  
https://sd-devsecops.github.io/Star-Cancellation-Test/CancellationOfConstellation.html

1. (Optional) Adjust the counts of stars, letters, and words.  
2. Select a test duration.  
3. Press **Start Test**.  
4. Participant draws strokes directly on the canvas.  
5. When time runs out or **Finish Test** is pressed:
   - Statistics appear  
   - Cancellation order is shown  
   - Full stroke direction table is displayed  
   - Participant enters:
     - Name  
     - Surname  
     - Age  

### Export options:

#### ✅ **Download CSV**
Includes:

- Demographic data  
- Object configuration  
- Correct cancellation totals  
- Left vs. right cancellations  
- Laterality Index  
- USN classification  
- Duration (seconds)  
- Average time per correct cancellation  
- All stroke data (coords, direction, correctness)  
- Full cancellation sequence  

#### ✅ **Download PNG**
Exports the final visual state exactly as drawn by the participant.

#### ✅ **NEW: Download Pattern PNG**
Generates an analytical visualization containing:

- **Green/red stroke coloring**  
- Midpoint-to-midpoint arrow path (scan sequence)  
- Stroke numbers  
- Faint small-star markers for spatial reference  

Ideal for:

- Neuropsychological pattern analysis  
- Clinical case documentation  
- Research datasets  
- Spatial behavior mapping  

---

## ✨ Features

- Multilingual UI: English, Türkçe, Deutsch  
- Randomized, non-overlapping placement  
- Demo stars for training  
- Missed stars highlighted  
- Cancelled stars labeled with IDs  
- Stroke numbering  
- Direction analysis  
- High-resolution PNG exports  
- UTF-8 CSV (supports Turkish & other languages)  
- Pattern visualization for scanning-path research (NEW)  
- Zero dependencies (pure HTML + JavaScript)

---

## ⚖ License

This project is open-source for **research**, **educational**, and **clinical development** purposes.

---

## ⚠ Ethical Disclaimer

For proper clinical or research use:

- Obtain relevant **ethical approvals**  
- Secure **informed consent**  
- Verify all exported data  
- Ensure interpretation by trained professionals  

---

## 🙏 Citation Request

If you use this tool in **research, clinical evaluation, a study, or a publication**,  
**please cite this project** to support continued development.
Email: sdswat93@gmail.com

This helps track academic use and encourages further improvements.

---

**Project by:** *Zengin, M.*  
**Enhanced by:** *ChatGPT*

