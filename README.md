# AI PPE Detection & Telegram Alert System

An AI-powered Personal Protective Equipment (PPE) Detection System built using YOLOv8, OpenCV, Gradio, and Telegram Bot API for real-time industrial safety monitoring.

This system detects PPE violations such as:
- No Helmet
- No Vest

and automatically:
- highlights violations,
- captures annotated screenshots,
- sends instant Telegram alerts,
- and acts as a detection layer for larger Agentic AI safety systems.

---

# Features

- Real-time PPE Detection
- YOLOv8-based Object Detection
- Helmet & Vest Compliance Monitoring
- Violation Highlighting
- Telegram Alert Integration
- Full Annotated Screenshot Alerts
- Image Detection Support
- Video Detection Support
- Gradio Web Interface
- Industrial Safety Monitoring Ready
- Agentic AI Compatible Architecture

---

# Tech Stack

- Python
- YOLOv8
- OpenCV
- Gradio
- Telegram Bot API
- Ultralytics

---

# PPE Classes

The model detects:
- helmet
- vest
- person
- no-helmet
- no-vest

Violation classes:
- no-helmet
- no-vest

---

# Project Architecture

```text
Video/Image Input
        ↓
YOLOv8 PPE Detection
        ↓
Violation Detection
        ↓
Annotated Screenshot Capture
        ↓
Telegram Alert System
        ↓
Agentic AI Safety Layer
```


Clone Repository:
git clone https://github.com/Vinay21rout/PPE-Detection-System.git

Install Dependencies
pip install ultralytics
pip install opencv-python
pip install gradio
pip install requests
Telegram Bot Setup
Create Telegram Bot

Open:
https://t.me/BotFather

Use:

/newbot

Copy generated BOT TOKEN.

Get Chat ID

Open:
https://t.me/userinfobot

Press START.

Copy your Chat ID.

Configure Credentials

Inside Python code:

BOT_TOKEN = "YOUR_BOT_TOKEN"

CHAT_ID = "YOUR_CHAT_ID"
Run Project
python app.py
