# ATC AI: Real-Time Aircraft Emergency Awareness System

## 🌐 Overview
**ATC AI** is a real-time AI-based system designed to enhance situational awareness during in-flight emergencies. By linking the aircraft’s Flight Data Recorder (FDR) and Cockpit Voice Recorder (CVR) to ground control systems, it enables Air Traffic Control (ATC) to proactively monitor aircraft conditions—giving pilots the freedom to focus on flying safely.

---

## 🚀 Our Solution

- 🔗 **FDR + ADS-B Integration**  
  ATC AI bridges the Flight Data Recorder with existing ADS-B communication systems.

- 🤖 **Real-Time AI Analysis**  
  The Gemini API processes FDR data to detect anomalies and raise timely warnings.

- 🎙️ **CVR Transcription with AWS Transcribe**  
  Converts cockpit voice recordings into actionable text for deeper situational context.

- 🧠 **Parameter Prioritization**  
  We prioritize key flight parameters to quickly detect critical anomalies with minimal latency.

- 🛬 **Minimized Verbal Communication**  
  Enables ATC to receive full aircraft context without overburdening pilots during emergencies.

---

## 📋 Current Standard Emergency Procedure

1. 🆘 Pilot calls "Mayday" to ATC  
2. 🧭 ATC asks for the nature of the emergency  
3. ✈️ Pilot relays the situation and coordinates new flight plans  
4. 🔄 Constant communication is required to monitor and manage the crisis

---

## ⚠️ Problems with the Current System

- Pilots must relay vital information while managing the aircraft
- ATC has no insight into onboard issues without pilot input
- Only basic telemetry—**Heading | Speed | Altitude | Latitude | Longitude**—is visible

---

## 🛠️ How we built it

- Used **Python** for real-time data parsing and communication with Arduino
- Integrated the **Gemini API** for FDR anomaly detection and alerts
- Used **AWS Transcribe** for transcribing cockpit voice data
- Applied **parameter prioritization** to highlight critical flight conditions
- Simulated flight behavior using CSV-based FDR logs
- Controlled servos and LCDs via **Arduino**, mimicking cockpit instruments
- Deployed a web-based UI via **StackBlitz** for data visualization
- Built a flag-based communication protocol for handling LCD and servo updates separately

---

## 🧠 What we learned

- Real-time analysis is vital in aviation safety systems
- AI + CVR + FDR create a holistic picture of aircraft emergencies
- Prioritization and minimal latency are key to effective anomaly detection
- Seamless communication between hardware and software systems improves reliability

---

## 🏆 Accomplishments we’re proud of

- Created a working system simulating cockpit instruments and ATC alerts
- Used multiple tools (Gemini, AWS, Arduino) to build a functional pipeline
- Designed and implemented a real-time flag-based messaging protocol
- Showed that AI-driven awareness can assist ATC without increasing pilot workload

---

## 🚀 What’s next for ATC AI

- Integrate live ADS-B feeds for testing in real-world conditions
- Expand CVR analysis to detect urgency or stress using NLP
- Build a unified ATC dashboard for anomaly, audio, and telemetry insights
- Partner with aviation simulation environments for trial deployments
- Extend servo control to replicate more cockpit instruments

---
## Click here to view the app : https://bolt.new/~/sb1-dvkt2eg3
## 👨‍💻 Contributors
Len Johns Shaji
