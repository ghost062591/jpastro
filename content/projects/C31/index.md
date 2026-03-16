---
title: "C31"
date: 2026-03-16T14:04:34Z
draft: false

# The object you photographed
object: "C31-The Flaming Star Nebula"

# Cover image filename (place file alongside this index.md)
cover: "C31_Final.jpg"

# Additional in-page images (place files alongside this index.md)
gallery:
  - "Screenshot 2026-03-10 223842.png"
  - "Screenshot 2026-03-10 224321.png"
  - "Screenshot 2026-03-10 224629.png"
  - "Screenshot 2026-03-11 171411.png"
  - "Screenshot 2026-03-11 205429.png"
  - "Screenshot 2026-03-11 205705.png"
  - "Screenshot 2026-03-11 214618.png"
  - "Screenshot 2026-03-11 214841.png"
  - "Screenshot 2026-03-11 215244.png"
  - "Screenshot 2026-03-11 215250.png"
  - "Screenshot 2026-03-11 221037.png"
  - "Screenshot 2026-03-11 222634.png"
  - "Screenshot 2026-03-11 223205.png"
  - "Screenshot 2026-03-11 223727.png"
  - "Screenshot 2026-03-11 223904.png"
  - "Screenshot 2026-03-11 225428.png"

# Google Drive full-resolution download link
highres_url: "https://drive.google.com/file/d/12V-zsYtKkKeyPVBWL9k2i1U37SZcp5AA/view?usp=sharing"

capture:
  date: "March 08-10, 2026"
  location: "Bortle 5 Site"
  total_time: "2h 54m"
  frames: "1,015 × 10s"
  darks: "0"
  flats: "0"
  biases: "0"

equipment:
  telescope: "SeeStar S50"
  camera: "Built-in"
  mount: "Built-in"
  filters: "Built-in IRCUT, Built-in LP"
  accessories: "N/A"

processing:
  software: "PixInsight, Photoshop"
  steps:
    - "Gather images with LP Filter (785)"
    - "Gather images with IRCUT Filter (230)"
    - "Did the following steps for each the IRCUT and LP images"
    - "Weighted batch preprocessing in PixInsight"
    - "Color calibration with SpectrophotometricColorCalibration"
    - "Graxpert Background Extraction"
    - "BlurXTerminator (correct only)"
    - "Noise reduction with NoiseXTerminator"
    - "Star removal with StarXTerminator"
    - "SetiAstro Statistical Strech"
    - "SetiAstro Star Stretch"
    - "PixelMath to combine starless data of IRCUT and LP image sets"
    - "Curves adjustments to bring details to the forground"
    - "Registered starless with stars extracted from the IRCUT stack for natural star colors"
    - "PixelMath to recombine starless and stars images"
    - "Final tone mapping, added signature, and export TIFF and JPEG from Photoshop"
---


