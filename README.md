# Star Cancellation Test

This repository contains the **Star Cancellation Test** — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control.  
It is commonly used in neurological and neuropsychological research, including studies on spatial neglect and related conditions.

---

## 📌 Overview

The test displays **small and large stars**, letters, and words on an interactive canvas.  
For each trial, the participant cancels (draws over) the **small stars** they see.

The system automatically records:

- Stars cancelled correctly  
- Left/right distribution of cancelled stars  
- Laterality Index (proportion of left vs right cancellations)  
- Summary statistics across the test  
- CSV export including full data and participant demographics

A researcher **cannot currently adjust the number of demo or target stars**, as these are preset in the test.  

---

## 🌐 Cross-Platform Use

The Star Cancellation Test runs entirely in a web browser — no installation required.

- **Desktop:** use mouse clicks  
- **Mobile / iPad:** use touchscreen taps  
- Fully responsive layout  
- Canvas area enlarged for better visibility on phones and tablets  
- Live strokes and statistics displayed below the test area  

---

## 🧪 How to Use

1. Open the test at:

   **https://sd-devsecops.github.io/Star-Cancellation-Test/CancallationOfConstellation.html**

2. Set the **timeout duration** at the top (minutes) and press **Start Test**.

3. Cancel small stars by drawing over them on the canvas.

4. When the **time expires** or the **Finish Test** button is pressed:
   - A form will appear requesting:
     - Name  
     - Surname  
     - Age

5. Press **Download CSV** or **Download PNG** to save results.  
   The files include:
   - All stroke data  
   - Cancelled stars (left/right counts)  
   - Laterality Index  
   - Duration of the test  
   - Demographic metadata

---

## ✨ Features

- Preset number of small and large stars, letters, and words  
- Countdown timer with automatic completion at timeout  
- Option to manually finish the test anytime via **Finish Test** button  
- Large responsive canvas for mobile/iPad usability  
- Statistics displayed below the canvas to avoid influencing performance  
- CSV export with all metrics and participant info  
- PNG export of the canvas for visual record  
- Fully offline capable (works without internet once loaded)  
- No external libraries required  

---

## 📁 Repository Contents

- **`CancallationOfConstellation.html`** – Full test interface + JavaScript logic  
- **`README.md`** – Documentation

---

## ⚖ License

This project is open-source and free for educational and research use.

---

## ⚠ Ethical Disclaimer

For any clinical or research use:

- Ensure appropriate ethical approval  
- Obtain informed consent  
- Validate all exported results independently  

---

**Project by Melisa Zengin**  
**Powered by ChatGPT**
