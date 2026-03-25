# LoL Real-time Match Tracking System (Prototype)

This repository contains the prototype implementation and pre-trained weights for the **Dual-Scale Tactical Extraction Pipeline**, built for real-time esports analytics in League of Legends.

##  Repository Structure
* `*.ipynb` - The main Colab notebook containing the end-to-end YOLOv8 + ByteTrack inference pipeline.
* `best.pt` - Fine-tuned YOLOv8n weights optimized for minimap champion detection.
* `training_metrics_nano.png` - Validation performance and loss curves.
* `final_gameplay_demo.mp4` - Qualitative demonstration of the tracking output.

##  Performance Highlights
* **Speed:** Sub-10ms latency per frame (>100 FPS on NVIDIA T4).
* **Architecture:** Ultralytics YOLOv8n backbone integrated with ByteTrack for high-continuity ID persistence.

*Note: This repository currently serves as the supplementary material for our presentation. Full modularized source code and synthetic datasets will be released in subsequent updates.*
