🥛 Raman Spectroscopy–Based Milk Quality Analysis System
📌 Project Description

This project focuses on developing a Raman spectroscopy–based system for accurate, non-destructive milk quality assessment. The system is designed for use in dairy processing and milk distribution centers, where rapid and reliable quality checks are critical. By analyzing Raman spectral signatures of milk, the system aims to identify compositional parameters such as fat, protein, lactose, and possible adulterants. The acquired data is processed using embedded and Python-based analytics and transmitted via IoT connectivity for real-time monitoring and historical trend analysis.

🔧 Project Workflow

A 532 nm monochromatic laser illuminates the milk sample placed in a quartz holder.

Molecular interactions in the milk produce Raman-scattered light.

Optical components (beam splitter, converging lens, long-pass filter) isolate and guide the Raman signal.

A CCD detector captures the Raman spectrum.

Spectral data is processed for noise reduction, baseline correction, and feature extraction.

Processed data is transmitted via ESP32 (IoT) to a software layer for visualization, storage, and analysis.

Results are displayed to the user and logged for future reference and trend monitoring.

🧠 Technologies Used (Planned)

Optics & Hardware

532 nm DPSS Laser

Beam Splitter, Converging Lens, Long-Pass Filter

CCD Linear Image Sensor

ESP32 Microcontroller

Software & Data Processing

Python

NumPy, SciPy

Matplotlib

IoT & Communication

Wi-Fi / MQTT

Cloud-based data storage

## Workflow Diagram
![Workflow Diagram](Work-Flow%20Diag.jpg)

## Working Principle Diagram
![Working Principle Diagram](Working%20Principle%20Diag.jpg)


