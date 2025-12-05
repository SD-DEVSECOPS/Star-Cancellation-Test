# ⭐ Star Cancellation Test (SCT)

This repository contains the **Star Cancellation Test** — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control.  
It is commonly used in **neurological and neuropsychological research**, including studies on **spatial neglect** and related conditions.

## 📌 Overview

The test displays **small and large stars, letters, and words** on an interactive canvas.  

**Participant task:** Draw over small stars they see.  

The system automatically records:

- Stars cancelled correctly  
- Left/right distribution of cancelled stars  
- Laterality Index (proportion of left vs right cancellations)  
- Summary statistics across the test  
- **CSV export for full data and statistics**  
- **PNG export of the latest version of the canvas**  

Researchers can configure **object counts before starting the test**:

| Object Type    | Recommended Range |
|----------------|-----------------|
| Small stars    | 50–80           |
| Large stars    | 50–70           |
| Letters        | 10–30           |
| Words          | 10–20           |

> ⚠ Note: Input values are validated to prevent canvas overload and excessive overlapping.

## 🌐 Cross-Platform Use

The SCT runs entirely in a web browser — no installation required:

- Desktop: use mouse clicks  
- Mobile / iPad: use touchscreen taps  
- Fully responsive layout  
- Canvas area enlarged for better visibility on phones and tablets  
- Live strokes and statistics displayed below the test area

## 🧪 How to Use

Open the test at:  
[**Live SCT Application**](https://sd-devsecops.github.io/Star-Cancellation-Test/CancallationOfConstellation.html)

1. Configure object counts (optional) and set the timeout duration (minutes).  
2. Press **Start Test**.  
3. Cancel small stars by drawing over them on the canvas.  
4. When the time expires or the **Finish Test** button is pressed:  
   - A form will appear requesting participant information:  
     - Name  
     - Surname  
     - Age  
5. Press **Download CSV** or **Download PNG** to save results.  

The exported files include:

- All stroke data  
- Cancelled stars (left/right counts)  
- Laterality Index  
- Duration of the test  
- Participant demographics  
- PNG of the latest canvas state

## ✨ Features

- Configurable number of **small and large stars, letters, and words**  
- Countdown timer with automatic completion at timeout  
- Option to manually finish the test via **Finish Test** button  
- Large responsive canvas for mobile/iPad usability  
- Statistics displayed below the canvas (does not influence performance)  
- CSV export for **full data and statistics**  
- PNG export of **latest canvas state**  
- Fully offline capable  
- No external libraries required

## 📁 Repository Contents

- **CancallationOfConstellation.html** – Full test interface + JavaScript logic  
- **README.md** – Documentation

## ⚖ License

This project is **open-source** and free for **educational and research use**.

## ⚠ Ethical Disclaimer

For any **clinical or research use**:

- Ensure **appropriate ethical approval**  
- Obtain **informed consent**  
- Validate **all exported results independently**

**Project by:** Melisa Zengin  
**Powered by:** ChatGPT
