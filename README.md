# 🥊 BattleFit

**BattleFit** is a browser-based fitness app developed for the **TerraHacks 2025** hackathon. It gamifies health and exercise through interactive voice-driven menus, AI-powered form feedback, and exercise tracking — all built with pure **HTML**, **CSS**, and **JavaScript**.

> No frameworks. No dependencies. Just raw code and creative design.

---

## 🚀 Project Overview

- 🗣️ **Voice-Controlled Navigation with Gemini AI** – Interact hands-free using basic voice commands like “start,” “menu,” or “next,” with Gemini used to double-check and validate commands for accuracy.
- 💪 **Gamified Fitness Flow** – Transforms workout steps into structured, battle-like challenges.
- 🤖 **AI-Powered Feedback** – Uses Gemini to analyze images of users performing exercises, providing real-time feedback on form through Text-To-Speech (TTS).
- 🧠 **Accessible Design** – Built for simplicity, speed, and cross-device support (desktop & mobile).

---

## 🎯 Core Features

### ✅ 1. Voice Command Menu (`menuVoiceControllerFree.js`)
- Listens for voice inputs like:
  - `menu`, `start`, `next`, `repeat`, `exit`
- Validates commands via Gemini AI to ensure high accuracy
- Guides users through app sections with audio and visual cues
- Modular and extendable command-based architecture

### ✅ 2. Feedback Collection & Form Analysis (`feedback.js`)
- Captures images of users performing exercises
- Sends images to Gemini AI for form evaluation
- Provides encouraging and corrective feedback via TTS
- Modular architecture facilitating easy updates

### ✅ 3. App Orchestration (`main.js`)
- Handles core app flow:
  - Navigating from intro → menu → feedback
  - Plays audio assets
  - Manages UI visibility and resets between states

---

## 🧪 Technologies Used

| Technology     | Purpose                          |
| -------------- | -------------------------------- |
| HTML5          | UI structure                     |
| CSS3           | Retro-styled theme (not included in JS files) |
| JavaScript     | App logic, interactivity         |
| Web Speech API | Voice recognition (in-browser)  |
| Audio API      | Feedback and navigation sounds   |
| Gemini AI      | Voice command validation and exercise form analysis with TTS feedback |

---

## 🛠️ Getting Started

1. Clone the repo:

    ```bash
    git clone https://github.com/your-username/battlefit.git
    cd battlefit
    ```

2. Open `index.html` in any modern browser (Chrome recommended for voice and camera features).

3. Grant microphone and camera access when prompted.

---

## 🧑‍⚕️ Why It Matters

Sedentary lifestyles are increasingly common, especially in work-from-home or tech-heavy environments. BattleFit reduces friction in staying active — no wearables, no app installs — just open your browser, use voice commands, and move.

---

## 🧠 What We Learned

- Integrating Gemini AI to improve voice command recognition and user form feedback
- Using the Web Speech API for basic voice command support
- Structuring multi-file vanilla JS projects with modular design
- Designing gamified feedback loops to improve user engagement

---

## 📈 Future Improvements

- 📱 Fully responsive mobile layout  
- 🏆 Leaderboards or PvP-style competitive challenges  
- 🗣️ More advanced natural language commands  

---

## 🙌 Built At

**TerraHacks 2025**  
Category: Healthcare  
Time: 36 hours  
Team Size: 4 developers

---
