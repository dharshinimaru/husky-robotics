# Husky Robotics - Spectroscopy System

**URC 2025 - Prometheus Rover - Science Subsystem**

Python-based spectroscopy processing pipeline for detecting biosignatures in Mars-analog soil samples using the ON Semiconductor NOIP2SE1300A-QTI (Python 1300) sensor.

## Features

-  2D → 1D spectrum extraction
-  Wavelength calibration
-  Peak detection
-  Biosignature analysis (chlorophyll, carotenoids, organics)
-  Real-time visualization (matplotlib)
-  Web dashboard (Flask)
-  Timestamped data logging

## Quick Start

### Installation
```bash
pip install numpy scipy matplotlib opencv-python pandas flask
```

### Running
```bash
# Generate test data
python3 testdata.py

# Run with dashboard
python3 run_with_dashboard.py

# Open browser to: http://localhost:5001
```

## Hardware

- **Sensor:** ON Semiconductor NOIP2SE1300A-QTI (Python 1300)
- **Resolution:** 1280 × 1024 pixels
- **Wavelength Range:** 400-700 nm (visible spectrum)

## Team

**Husky Robotics** - University of Washington  
**Competition:** University Rover Challenge 2025  
**Subsystem:** Science (Spectroscopy)


