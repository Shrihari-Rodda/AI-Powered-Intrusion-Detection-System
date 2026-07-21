# AI Intrusion Detection System (AI-IDS)

🚧 **Status:** Under Development

An AI-powered Intrusion Detection System (IDS) for Industrial IoT (IIoT) environments that continuously monitors network traffic, analyzes PCAP files, correlates logs, and uses Large Language Models (Gemini) to detect cyber threats and recommend remediation actions.

## Features

- 📡 Continuous network traffic monitoring
- 📂 PCAP file analysis
- 🤖 AI-powered anomaly detection using Gemini
- 📜 Log correlation for better threat analysis
- 🚨 Detection of attacks like DDoS, SQL Injection, Port Scanning, etc.
- 📊 Grafana dashboard for alerts and remediation
- ☸️ Containerized deployment using Docker, Kubernetes, and Helm

## Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** React
- **AI Framework:** LangGraph + Gemini LLM
- **Infrastructure:** Docker, Kubernetes, Helm
- **Monitoring:** Grafana, Loki
- **Networking:** PCAP, TCP/IP

## Project Structure

```
AI-Intrusion-Detection-System/
│
├── backend/
├── frontend/
├── docker/
├── kubernetes/
├── helm/
├── sample_pcaps/
├── docs/
└── README.md
```

## Roadmap

- [x] Project setup
- [ ] Packet capture & parsing
- [ ] AI agent integration
- [ ] Threat detection
- [ ] Log correlation
- [ ] Grafana dashboard
- [ ] Docker deployment
- [ ] Kubernetes deployment
- [ ] Helm charts

## Disclaimer

This project is being developed for educational and defensive cybersecurity purposes only.
