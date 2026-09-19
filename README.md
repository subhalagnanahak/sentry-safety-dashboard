# SENTRY — Factory Safety Monitoring Dashboard

AI-based real-time factory safety monitoring system — PPE compliance detection, fire/smoke/hazard alerts, and environmental pattern analysis, built for Hackathon Problem Statement PS6.

## 🚀 Live Demo
👉 **[Open the Dashboard](https://sentry-safety-dashboard-aujf8xtn6sn3bghazukser.streamlit.app/)**

## Features
- Multi-camera monitoring with zone-based tagging
- Customizable PPE compliance rules per zone/camera
- Continuous real-time detection with alert cooldown
- Voice announcements for PPE violations, siren for hazards
- 24-hour environmental pattern analysis (slippery zones, vibration, leaks)
- Signage-detection feedback loop
- Exportable compliance reports (CSV/PDF)

## Run locally
\`\`\`bash
pip install -r requirements.txt
streamlit run app.py
\`\`\`

## Tech Stack
Python · Streamlit · Pandas · (YOLOv8 for production detection pipeline)