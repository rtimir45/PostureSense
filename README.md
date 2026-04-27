

---

# 🚀 PostureSense – Real-Time Posture Monitoring System

PostureSense is a real-time posture detection and monitoring system designed to help users maintain healthy sitting habits. It uses computer vision and machine learning to detect posture and provide feedback through a web-based interface.

---

## 📌 Overview

Poor posture is a major cause of back pain, fatigue, and long-term musculoskeletal issues. PostureSense addresses this by continuously analyzing body posture using a webcam and alerting users when improper posture is detected.

Modern posture monitoring systems rely on **computer vision and behavioral analysis to detect posture deviations in real time** ([IJSR][1]), and this project implements a practical version of that concept using Python and Streamlit.

---

## ✨ Features

* 🎥 **Real-time posture detection** using webcam
* 🧠 **Pose estimation** powered by MediaPipe
* 📊 **Session tracking & analytics**
* 🖥️ **Interactive UI** built with Streamlit
* ⏱️ **Session timer with start/stop functionality**
* 🚨 **Visual feedback (red screen alert)**
* 📈 **Dashboard for posture insights**

---

## 🛠️ Tech Stack

| Category            | Technology Used                 |
| ------------------- | ------------------------------- |
| Language            | Python                          |
| Computer Vision     | OpenCV                          |
| Pose Detection      | MediaPipe                       |
| UI Framework        | Streamlit                       |
| Real-time Streaming | streamlit-webrtc                |
| Data Handling       | Python (collections, threading) |

---

## 🧠 How It Works

1. Webcam captures live video feed
2. MediaPipe detects key body landmarks
3. Angles between joints are calculated
4. Posture is classified as **Good** or **Bad**
5. Alerts are triggered if posture is incorrect
6. Data is tracked for session analytics

---

## 📂 Project Structure

```
PostureSense/
│── app.py                 # Main Streamlit application
│── requirements.txt      # Dependencies
│── utils/                # Helper functions (if any)
│── assets/               # Images / icons
│── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/rtimir45/PostureSense.git
cd PostureSense
```

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the application

```bash
streamlit run app.py
```

---



## 📊 Use Cases

* 👨‍💻 Students & Developers (long screen hours)
* 🏢 Office workers
* 🪑 Remote workers
* 🧘 Health-conscious users

---

## 🚧 Future Improvements

* 📱 Mobile app integration
* ☁️ Cloud-based analytics
* 🤖 AI-based posture correction suggestions
* 👥 Multi-user tracking

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request


---

## 👨‍💻 Author

**Timir Rana**
📌 GitHub: [https://github.com/rtimir45](https://github.com/rtimir45)

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

---


* Create **LinkedIn project description**
* Improve README with **diagrams & architecture**

Just tell me 👍

[1]: https://www.ijsr.net/getabstract.php?paperid=SR25416224103&utm_source=chatgpt.com "Posturesense - A Predictive Health Insight from Behavioural Analysis"
