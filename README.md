# Uni-Flow: AI-Based Detection of Cyber Threats in Unidirectional IP Traffic
**SIH 2026 | Problem ID: SIH26145 | Theme: Blockchain & Cybersecurity**

### 🚀 Problem
In isolated networks (defense/air-gapped), you only get one-way traffic. Traditional IDS fails because it can't interact back.

### 💡 Solution - Uni-Flow
An AI-powered passive monitoring system:
- **Silent Monitoring:** Zeek-style parsing, no interference with network
- **6 Threats Detected:** DDoS, C2 Beaconing, DGA, DNS Tunneling, Encrypted Malware, Port Scanning
- **Privacy Preserving:** No payload decryption - uses metadata, packet size, timing & JA3 fingerprinting
- **Evidence-Based Alerts:** Risk scores + confidence for SOC teams

### 🛠️ Tech Stack
Python | Redis Streams | Scikit-learn | Pandas | FastAPI | Streamlit | JA3 Fingerprinting

### 📊 Workflow
Zeek Logs → Streaming Pipeline → Detection Engine (Rule + ML) → API + Dashboard

Built for Smart India Hackathon 2026 - PDEA College of Engineering, Manjri, Pune
