# Seismic Data Detection Project

## Project Overview
The Seismic Data Detection project focuses on filtering seismic data from Apollo and Mars InSight missions. It identifies earthquake signals and reduces noise for efficient data transmission. The project leverages advanced techniques like Principal Component Analysis (PCA) and Huffman encoding to compress seismic data, making it possible to transmit only necessary information with high resolution and low power consumption.

## Problem Statement
The project aims to:
- Distinguish seismic signals from noise.
- Efficiently compress and transmit data.
- Minimize energy usage during data processing and transmission.

## Key Components
1. **Planetary Seismic Detector (PSD)**: 
   - A tool designed to process seismic data by separating raw data from seismic instruments (seismometers) into useful signals and noise.
   - Utilizes RMS (Root Mean Square) energy calculations to enhance data quality.

2. **Noise Removal**:
   - PCA (Principal Component Analysis) is used to reduce noise in the data by highlighting the most significant components.
   - It ensures a significant reduction in data size while retaining key features for analysis.

3. **Data Compression**:
   - Huffman encoding further compresses the data after PCA processing, ensuring lossless compression for optimized data transmission.

## Web Application
The project includes a web application that:
- Processes seismic data from Mars.
- Automates the algorithms for data filtering, noise reduction, and compression.
- Provides real-time or near-real-time data analysis through a user-friendly interface.

## Technologies Used
- **PCA (Principal Component Analysis)**: To highlight key features and reduce data size.
- **Huffman Encoding**: To perform lossless compression on the reduced data.
- **RMS Energy Calculation**: For distinguishing seismic signals from noise.

## Challenges
- Handling intermittent seismic signals.
- Optimizing algorithms to work efficiently with Mars data.
- Enhancing the web application to support Mars seismic data analysis.

## Future Work
- Focus on improving the web application for analyzing Mars seismic data.
- Automating the processing algorithms for continuous data filtering and analysis.
- Further optimizations in data transmission efficiency for long-duration missions.

## Contributors
- **Sunil Sachindar S A**
- **Leonal Robin D**
- **Karthie Krishna K**
- **Aadithya E R Menon**
- **Darneshwar S**
- **Sai Tarun Aditya K**

---

This project was developed by Phantom Developers to assist in planetary exploration and seismic data analysis, specifically focusing on the challenges faced with Apollo and Mars InSight seismic data.
