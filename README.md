# Dumb Charades Game 🎭

A React-based interactive game that challenges users to guess movies with the help of hints. Designed for fun and engagement, this app includes personalized greetings, scoring, and a sleek user interface.

---

## Features 🌟
- **Dynamic Gameplay**: Guess movies with multiple hints.
- **Personalized Greetings**: Customized feedback and ratings based on performance.
- **Score Tracking**: Tracks user score and attempts.
- **Interactive Hints**: Provides sequential hints to guide users.
- **Routing Support**: Navigate between Home, Game, and Results pages.
- **Reusable Components**: Modular design with reusable components like buttons.

---

## How to Play 🎮
1. **Start**: Enter your username and begin the game.
2. **Guess**: Read the question and enter your answer.
3. **Hints**: Click *Show Next Hint* for additional clues.
4. **Submit**: Enter your answer and click *Submit Answer*.
5. **Finish**: Receive a score and personalized feedback on completion.

---
## Technologies Used 🛠️
- **React**: Frontend framework for building user interfaces.
- **React Router**: Handles navigation between components.
- **CSS Modules**: Component-scoped styling for better maintainability.
- **React Toastify**: Provides notifications and alerts for a better user experience.
- **LocalStorage**: Used to store user data and scores for continuity.

---

## Installation & Setup 🚀

### Clone the Repository
```bash
https://github.com/ChetanSingh14/Dums-Charads.git
```
## Install Dependencies
npm install
Run the Application
npm start


## File Structure 📁

```plaintext
src/
├── components/
│   ├── **Button.js**        - Reusable button component
│   ├── **Home.js**          - Home screen component
│   ├── **Game.js**          - Main game logic and UI
│   ├── **Greeting.js**      - Feedback and score display
├── styles/
│   ├── **Button.css**       - Styles for the Button component
│   ├── **Home.module.css**  - Scoped styles for the Home component
│   ├── **Game.module.css**  - Scoped styles for the Game component
│   ├── **Greeting.module.css** - Scoped styles for the Greeting component
├── **App.js**               - App entry point with routes
└── **index.js**             - Main entry file



