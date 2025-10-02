# sysmonitor
This is a simple system monitoring tool written in Python.
It shows CPU usage, RAM usage, GPU stats, and internet traffic in real-time, directly in your terminal.

Features

✅ CPU usage and frequency

✅ RAM usage and total memory

✅ GPU name, memory, and temperature (requires NVIDIA GPU)

✅ Internet traffic (sent & received data)

✅ Cross-platform support (Windows/Linux/macOS)

Requirements

Before running, install the dependencies:
- pip install psutil GPUtil termcolor

-----------------------------------------
Example Output
==================== SYSTEM ====================
        System       - Windows
        Total Cores  - 8 Cores
        Cpu          - 12%
        Max Cpu Freq - 4200.0MHZ
        Total Ram    - 16GB
        Ram          - 4.20GB | 26%
        Gpu          - NVIDIA GeForce GTX 1660
        Gpu Memory   - 6144MB
==================== Internet ==================
        Data Sent    - 1.23MB
        Data Receive - 25.4MB

