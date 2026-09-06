# ⏱️ The Final Countdown - React Project

This project is a timer-based challenge game developed as part of the *"React - The Complete Guide"* course by Maximilian Schwarzmüller. 

Players are challenged to start a timer and stop it exactly when the target time expires, without going over. The main goal of this repository is to demonstrate how to manage values that shouldn't trigger component re-renders and how to manipulate the DOM directly when necessary.

## ✨ Features
*   **Timer Challenges:** Multiple difficulty levels with different target times (e.g., 1 second, 5 seconds, etc.).
*   **Start & Stop Mechanisms:** Users can trigger and halt intervals dynamically.
*   **Score Calculation:** Calculates and displays a score based on how close the user was to the target time when they stopped the timer.
*   **Interactive Modals:** Displays a results dialog when the timer expires or is stopped manually.

## 🚀 Advanced React Concepts Practiced
This project moves beyond basic state management and dives into advanced component communication and DOM manipulation:
*   **`useRef` Hook:** Used for two distinct purposes: connecting directly to HTML elements (like dialogs) and managing variables (like timer IDs) that persist across renders without triggering a new render cycle.
*   **`forwardRef`:** Passing refs through multiple layers of components to access child DOM elements from a parent component.
*   **`useImperativeHandle`:** Exposing custom callable functions (methods) from a child component to a parent component, allowing the parent to trigger specific actions (like `dialog.showModal()`).
*   **React Portals (`createPortal`):** Rendering components (like the result modal) outside of the main root DOM hierarchy to avoid CSS styling conflicts and improve accessibility.

## 🛠️ Built With
*   **React.js** (initialized via Vite)
*   **JavaScript (ES6+)**
*   **HTML5 & CSS3**

## ⚙️ Getting Started (Local Setup)

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone [https://github.com/BardoczDaniel/FinalCountdown.git](https://github.com/BardoczDaniel/FinalCountdown.git)
