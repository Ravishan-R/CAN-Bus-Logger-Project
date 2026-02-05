# CAN-Bus-Logger-Project
🎯 CAN Bus Data Logger & Vehicle Network Simulator – Project Goals
🚗 Project Overview
This project is a hands-on implementation of a CAN Bus Data Logger and Vehicle Network Simulator using ESP32 microcontrollers and Python. It simulates real vehicle ECU communication, logs CAN traffic, and provides a real-time diagnostic dashboard for analysis.

📌 Primary Goals
1. Hardware Integration
  Interface ESP32 with MCP2515 CAN module
  Build a multi-node CAN network (simulating ECUs)
  Transmit and receive standard/extended CAN frames

2. Data Capture & Logging
  Capture live CAN bus traffic using SavvyCAN
  Log time-stamped CAN data to CSV/SD card
  Implement real-time serial monitoring

3. Data Parsing & Decoding
  Parse raw CAN frames using Python (python-can)
  Decode CAN messages using DBC files (cantools)
  Convert hex data to human-readable values (RPM, speed, temperature, etc.)

4. Visualization & Dashboard
  Build a real-time dashboard using Plotly/Dash or Grafana
  Display live graphs for RPM, vehicle speed, battery voltage, and temperature
  Implement alerting for fault codes (e.g., over-temperature, low voltage)

5. Diagnostics & Analysis
  Simulate common OBD-II PID requests and responses
  Implement basic fault code detection and logging
  Provide export functionality for logged data (CSV, JSON)

6. Cloud Integration (Stretch Goal)
  Send CAN data to cloud platform (AWS IoT Core / InfluxDB)
  Enable remote monitoring via web dashboard
  Implement data persistence and historical analysis

🛠️ Technical Objectives

Layer	      Technology	            Goal
Hardware	  ESP32, MCP2515	        Stable CAN communication at 500kbps
Firmware	  Arduino/C, ESP-IDF	    Send/receive CAN frames, simulate ECUs
Software	  Python 3.x	            Parse, decode, visualize CAN data
Database	  InfluxDB / SQLite	      Store time-series CAN data
Dashboard	  Grafana / Plotly Dash	  Real-time monitoring & alerts
Cloud	      AWS IoT / MQTT	        Optional remote access

📈 Success Metrics
✅ CAN network with ≥ 2 nodes running without errors
✅ Dashboard updating in real-time (< 2 sec latency)
✅ DBC file correctly decoding ≥ 5 CAN signals
✅ GitHub repo with full documentation and demo video

🧠 Learning Outcomes
By completing this project, I will gain practical experience in:
  Automotive communication protocols (CAN, OBD-II)
  Embedded C programming for microcontrollers
  Python for data parsing and visualization
  Real-time dashboard development
  Hardware-software integration in IoT systems

🗓️ Project Timeline
Week	    Focus	                        Deliverable
Week 1	  CAN Basics & Hardware Setup	  Working 2-node CAN network
Week 2	  Python Parsing & Dashboard	  Live data visualization
Week 3	  DBC Decoding & Diagnostics	  Fault detection system
Week 4	  Cloud Integration & Polish	  Full-stack deployment
🤝 Contributing
This is a personal learning project, but feedback and suggestions are welcome! Feel free to open an issue or reach out via LinkedIn.

Started: February 5, 2026
Status: In Progress 🚧
Last Updated: February 5, 2026

🔗 Connect
GitHub: https://github.com/Ravishan-R
LinkedIn: www.linkedin.com/in/ravishan-rathnayakeprs
Portfolio: https://ravishan-r.github.io/Portfolio/ 

This README will evolve as the project grows. Each goal will be checked off upon completion, and new stretch goals may be added.


