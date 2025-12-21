---

# ⚡ The Enchanted Quizbook

**The Enchanted Quizbook** is a **cross-platform magical quiz application** that allows users to explore their wizarding identity through interactive challenges.  
Built with a modern **full-stack mobile architecture**, the application delivers a seamless experience across **Android and Web** platforms.

---

## 🌟 Key Features

### 1. 🪄 The Patronus Quiz
Discover your magical guardian.  
This **15-question diagnostic quiz** analyzes personality traits to assign a unique Patronus  
(e.g., the independent **Cat** or the courageous **Lion**).

### 2. 🌲 The Forbidden Forest Challenge
Test your wizarding knowledge with a high-stakes trivia game focused on the creatures and lore of the **Forbidden Forest**.

### 3. 🏆 Global Leaderboard
Compete with other users worldwide.  
The application tracks scores and displays a **real-time leaderboard**, fetching data directly from a centralized database.

### 4. 🌍 Cross-Platform Accessibility
Built with **React Native and Expo**, the app ensures a consistent user interface and smooth performance across mobile devices and web browsers.

---

## 🛠️ Technology Stack

| Component   | Technology Used |
|------------|-----------------|
| Frontend   | React Native (Expo) |
| Backend    | Python Flask API |
| Database   | MongoDB |
| Networking | Ngrok (local backend tunneling) |
| IDE        | Visual Studio Code |

---

## 🏗️ Project Structure

The application follows a **modular directory structure** for scalability and maintainability:

/app
├── Main application logic
/quiz
├── Patronus quiz module
├── Forbidden Forest quiz module
leaderboard.tsx
├── Global leaderboard UI
/assets
├── Images, fonts, icons
/backend
├── Flask API
├── MongoDB integration

---

## 🚦 Getting Started

### Prerequisites
- Node.js & npm  
- Expo Go  
- Python 3.x  
- MongoDB (optional: Compass)

### Setup
```bash
git clone [your-repo-link]
npm install
npx expo start
