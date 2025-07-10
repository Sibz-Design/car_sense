# 📊 YouTube Comments Analytics Dashboard

A Python-based web application for analyzing YouTube comments with interactive charts, sentiment analysis, and video data visualization. Built with **Flask**, **Plotly.js**, and a responsive frontend using **HTML**, **CSS**, and **JavaScript**.

Inspired by the bold red-and-white aesthetic of [Cars.co.za](https://www.cars.co.za), the dashboard features a clean UI with theme switching, keyboard shortcuts, and mock or live YouTube data support.

---

## 🚀 Features

- **Dashboard Overview**: Total Comments, Videos Analyzed, Total Likes, Avg. Likes/Comment
- **Interactive Charts**: Comments by Video, Sentiment Distribution, Comments Over Time, Sentiment Trend (14 Days)
- **Sentiment Analysis**: Filter and search comments by sentiment (Positive, Negative, Neutral)
- **Video Browser**: View video thumbnails, stats, and sentiment breakdowns
- **Theme Selector**: Choose between plain white or Smart car backgrounds (Silver, Yellow, Black, Custom)
- **Responsive Design**: Optimized for desktop and mobile
- **Auto-Refresh**: Dashboard updates every 5 minutes
- **Keyboard Shortcuts**:
  - `Ctrl/Cmd + 1/2/3`: Switch tabs
  - `Ctrl/Cmd + R`: Refresh current tab
  - `Alt + D/S/V`: Load Dashboard, Sentiment, or Videos
- **Styling**: Arial font, red/white theme, fine red borders on inputs

---

## 🧰 Prerequisites

- Python 3.8+
- Modern browser (Chrome, Firefox, Safari, Edge)
- YouTube Data API key (optional; mock data included)

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd youtube-comments-analytics

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt
Flask==2.3.2
requests==2.31.0

youtube-comments-analytics/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── images/
├── requirements.txt
└── README.md

python app.py
