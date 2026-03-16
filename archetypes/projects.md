---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true

# The object you photographed
object: "M31 - Andromeda Galaxy"

# Cover image filename (place file alongside this index.md)
cover: "cover.jpg"

# Additional in-page images (place files alongside this index.md)
gallery:
  - "image1.jpg"
  - "image2.jpg"

# Google Drive full-resolution download link
highres_url: "https://drive.google.com/file/d/YOUR_FILE_ID/view?usp=sharing"

capture:
  date: "January 10–12, 2024"
  location: "Bortle 4 Site"
  total_time: "8h 30m"
  frames: "102 × 5min @ gain 100"
  darks: "30"
  flats: "50"
  biases: "100"

equipment:
  telescope: "William Optics GT81"
  camera: "ZWO ASI2600MC Pro"
  mount: "Sky-Watcher EQ6-R Pro"
  filters: "Optolong L-eNhance"
  accessories: "ZWO EAF, ASIAir Plus"

processing:
  software: "PixInsight, Photoshop"
  steps:
    - "Weighted batch preprocessing in PixInsight"
    - "Dynamic background extraction"
    - "Noise reduction with NoiseXTerminator"
    - "Star removal with StarXTerminator"
    - "Color calibration with SpectrophotometricColorCalibration"
    - "Final tone mapping and export in Photoshop"
---

Write any additional notes about this project here. Markdown is supported.
