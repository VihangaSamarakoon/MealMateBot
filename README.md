# MealMateBot
# 🤖 MealMateBot – AI-Powered Telegram Recipe Assistant

MealMateBot is a smart recipe assistant built on the Telegram platform, designed to help users discover recipes using natural language. The system integrates multiple interaction methods such as **text input**, **voice messages**, and soon, **image-based ingredient recognition**.

---

## 📌 Current Progress

### ✅ Core Features Completed

- **Telegram Bot Integration**
  - Command handlers set up using `python-telegram-bot`
  - Text input processed to return relevant recipe suggestions

- **Recipe Search Functionality**
  - Integrated with a public recipe API
  - Parses and formats results based on user queries

- **Basic Agent System**
  - Developed modular, functional agents for handling tasks
  - Currently shifting from independent to semi-dependent agents for better task coordination

---

### 🔄 Features In Progress

- **🎙️ Voice Message Handling (Ongoing)**
  - Working prototype converts `.ogg` files to `.wav` using `pydub`
  - Integrated `Google Speech Recognition` for transcription
  - Working on better command routing and contextual understanding after transcription

- **📷 Image-Based Ingredient Detection (Planned)**
  - Google Cloud Vision API service account is set up
  - Next steps involve integrating image upload handling and prediction parsing

---

## 🛠️ Technologies

- `python-telegram-bot`
- `pydub`
- `speechrecognition`
- `requests`
- `Google Cloud Vision API` (for upcoming image recognition)
