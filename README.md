# 🌳 SmartStudy Planner

**Turn Productivity into a 3D Ecosystem.**

SmartStudy  Planner is a gamified study management platform that helps students stay consistent by turning their academic progress into a flourishing digital forest. Using immersive **Three.js** visualizations and advanced scheduling algorithms, the app makes productivity both visual and rewarding.

---

## ✨ Key Features

### 📅 Intelligent Weighted Scheduler
- **Dynamic Planning**: Automatically generates study schedules based on subject difficulty, current progress, and exam deadlines.
- **Priority Logic**: High-priority tasks are allocated more time while ensuring no subject is left behind.

### 🌲 Gamified 3D Forest
- **Immersive Visualization**: Watch your study efforts manifest as 3D trees in a persistent virtual forest built with **Three.js**.
- **Tiered Progression**: Grow anything from a simple "Healthy" Oak to a "Legendary" Rainbow Eucalyptus or even a "Mythic" World Tree.
- **Visual Feedback**: Trees reflect your consistency—thriving during productive weeks and slowing down during breaks.

### 🏆 Social & Competitive Features
- **Global Leaderboard**: Compare your study streaks and total points with students worldwide.
- **Integrity System**: Built-in verification logs to ensure study time is rewarded fairly.
- **Inventory System**: Collect and manage your rare tree species as you level up.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Django 5.2.13

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aryan12375/smartstudy-planner.git
   cd smartstudy-planner
   ```

2. **Set up a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Start the server**:
   ```bash
   python manage.py runserver
   ```

6. **Access the app**:
   Open `http://127.0.0.1:8000` in your browser.

---

## 🛠️ Tech Stack
- **Backend**: Python, Django
- **Frontend**: HTML5, CSS3, JavaScript (Three.js for 3D)
- **Database**: SQLite (Development) / PostgreSQL (Production)

---

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

*Made with ❤️ for students who want to build better habits.*
