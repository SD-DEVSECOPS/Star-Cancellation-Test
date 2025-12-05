# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control.  
It is commonly used in **neurological and neuropsychological research**, including studies on **spatial neglect** and related visuospatial disorders.

---

## 📌 Overview

The test displays **small & large stars, letters, and words** generated randomly across an interactive canvas.

**Participant task:**  
Draw a stroke over each **small star** they see.

The system automatically records:

- Correctly cancelled stars  
- **Cancellation order (first → last)**  
- **Stroke-by-stroke data**  
- **Stroke direction detection**  
  - Left→Right  
  - Right→Left  
  - Top→Bottom  
  - Bottom→Top  
- Left/right cancellation distribution  
- **Laterality Index**  
- **USN classification**  
- **Full statistical summary**  
- **CSV export** (UTF-8 BOM for Turkish characters)  
- **PNG export** of the final canvas state  

Researchers can configure object counts before starting the test:

| Object Type | Recommended Range |
|-------------|------------------|
| Small stars | 50–80            |
| Large stars | 50–70            |
| Letters     | 10–30            |
| Words       | 10–20            |

> ⚠ These values are validated to prevent excessive overlap or overload.

---

## 🌐 Cross-Platform Compatibility

The SCT runs fully inside any modern browser:

- ✔ Desktop (mouse input)  
- ✔ Mobile phones (touch input)  
- ✔ iPad & tablets  
- ✔ Touch-friendly stroke handling  
- ✔ Fully responsive layout  
- ✔ No installation required  
- ✔ Offline-capable  
- ✔ Uses **no external libraries**

---

## 🧪 How to Use

**Live Test Page:**  
https://sd-devsecops.github.io/Star-Cancellation-Test/CancallationOfConstellation.html

1. Adjust object counts (optional).  
2. Select test duration (minutes).  
3. Press **Start Test**.  
4. Participant draws strokes directly on the canvas to cancel stars.  
5. When the timer ends or **Finish Test** is pressed:
   - Statistics panel appears  
   - Cancellation order displayed  
   - Directional stroke table displayed  
   - Required participant info:
     - Name  
     - Surname  
     - Age  

6. Export results via:
   - **Download CSV**  
   - **Download PNG**  

### CSV includes:

- Participant demographics  
- Object configuration  
- Total correct cancellations  
- Left vs right cancellation counts  
- Laterality Index  
- USN classification  
- Duration (seconds)  
- Average time per correct cancellation  
- Every stroke — with direction & correctness  
- Full cancellation order list  

---

## ✨ Features

- **Multi-language interface:** English, Türkçe, Deutsch  
- Automatic browser-language detection  
- Translated words list for each language  
- Randomized placement of:
  - Small stars  
  - Large stars  
  - Letters  
  - Words  
- Demo stars included  
- **Red highlight** for missed stars at test end  
- **Blue labels** for cancelled stars  
- **Numbered strokes** on final canvas (visual order tracking)  
- Direction detection for each stroke  
- Large, responsive canvas for tablet use  
- PNG export  
- UTF-8 encoded CSV export  
- Works 100% offline  
- Zero dependencies  

---

## 📁 Repository Structure
📦 Star-Cancellation-Test
 ├── CancallationOfConstellation.html   # Full UI + test logic
 └── README.md                          # Documentation

---

## ⚖ License

This project is **open-source** and free for **educational and research use**.

---

## ⚠ Ethical Disclaimer

For any **clinical or academic** research use, ensure:

- Proper **ethics committee approval**  
- **Informed consent** from all participants  
- Independent verification of exported data  

---

**Project by:** *Melisa Zengin*  
**Enhanced by:** *ChatGPT*

