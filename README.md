# 🎵 EmoGroove

**EmoGroove** is an emotion‑aware, multilingual music recommender.  
Give it a short text snippet—anything from *“Feeling on top of the world!”* to *“Why is everything so hard today?”*—and it instantly detects the underlying emotion and serves up songs that match or gently shift your mood.

---

## 🌟 Core Features

| Feature | What it Does |
|---------|--------------|
| **Text‑Based Emotion Detection** | Uses a lightweight NLP model to classify the user’s input as *happy, sad, angry, relaxed,* or *neutral*. |
| **Multilingual Recommendations** | Maps each emotion to curated song lists across multiple languages (currently English, Hindi, Tamil, Telugu, Malayalam). |
| **API‑Driven Playback** | Streams tracks via public Spotify API. |
| **Minimalist UI** | Built with plain HTML + CSS + JavaScript for maximum portability and fast load times. |

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML5, CSS3 (Flexbox & Grid), Vanilla JavaScript (ES6) |
| **Backend** | Flask |
| **Database** | PostgreSQL 15 |
| **NLP / ML** | A simple bidirectional RNN |
| **External API** | Spotify API |

---

## 🚀 Quick Start

### 1. Clone & Configure

```bash
git clone https://github.com/VarshaKumaraguru/emogroove.git
cd emogroove
