Star Cancellation Test

This repository contains the Star Cancellation Test — a browser-based assessment tool used to measure visuospatial attention, perceptual accuracy, and motor control. It is commonly used in neurological and neuropsychological research, including studies on spatial neglect and related conditions.

📌 Overview

The test displays small and large stars, letters, and words on an interactive canvas.
For each trial, the participant cancels (draws over) the small stars they see.

The system automatically records:

Stars cancelled correctly

Left/right distribution of cancelled stars

Laterality Index (proportion of left vs right cancellations)

Summary statistics across the test

CSV export including full data and participant demographics

🔧 New Feature: Configurable Object Counts

Researchers can now set the number of objects before starting the test:

Object Type	Recommended Range
Small stars	50–80
Large stars	50–70
Letters	10–30
Words	10–20

The system validates inputs to prevent overloading the canvas and ensures objects do not overlap excessively.

🌐 Cross-Platform Use

The Star Cancellation Test runs entirely in a web browser — no installation required:

Desktop: Use mouse clicks

Mobile / iPad: Use touchscreen taps

Fully responsive layout

Canvas area enlarged for better visibility on phones and tablets

Live strokes and statistics displayed below the test area

🧪 How to Use

Open the test at:
https://sd-devsecops.github.io/Star-Cancellation-Test/CancallationOfConstellation.html

Configure object counts (optional) and set the timeout duration at the top (minutes).

Press Start Test.

Cancel small stars by drawing over them on the canvas.

When the time expires or the Finish Test button is pressed:

A form will appear requesting participant information:

Name

Surname

Age

Press Download CSV or Download PNG to save results.

The exported files include:

All stroke data

Cancelled stars (left/right counts)

Laterality Index

Duration of the test

Demographic metadata

✨ Features

Configurable number of small and large stars, letters, and words

Countdown timer with automatic completion at timeout

Option to manually finish the test anytime via Finish Test button

Large responsive canvas for mobile/iPad usability

Statistics displayed below the canvas to avoid influencing performance

CSV export with all metrics and participant info

PNG export of the canvas for visual record

Fully offline capable (works without internet once loaded)

No external libraries required

📁 Repository Contents

CancallationOfConstellation.html – Full test interface + JavaScript logic

README.md – Documentation

⚖ License

This project is open-source and free for educational and research use.

⚠ Ethical Disclaimer

For any clinical or research use:

Ensure appropriate ethical approval

Obtain informed consent

Validate all exported results independently

Project by Melisa Zengin
Powered by ChatGPT
