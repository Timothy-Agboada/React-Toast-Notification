## 🚀 30-Day Coding Challenge: Day 26

This project is the twenty-sixth entry in my 30-day coding challenge. Today's goal was to build a professional, non-intrusive toast notification system, a common component in modern web applications. This project focuses on managing self-dismissing UI elements, advanced animations, and a more complex React concept: Portals.

### 📖 Project Overview

This is a sleek and modern toast notification system built with React. The application features a control panel that can trigger different types of notifications (success, error, info). When triggered, a "toast" message appears on screen with a unique color and icon corresponding to its type. Each toast includes a progress bar indicating its remaining time and automatically dismisses itself after a few seconds with a smooth exit animation.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jul-04-2025 17-34-02](https://github.com/user-attachments/assets/f513f0cf-79c5-4b1b-8677-0dfc1e3a4d87)


### 🌟 Key Features

* **Multiple Notification Types:** Supports different notification contexts (success, error, info), each with a distinct color and icon.
* **Auto-Dismissing Toasts:** Notifications automatically disappear after a set duration.
* **Animated Progress Bar:** Each toast has a visual timer that shows how long it will remain on screen.
* **React Portals:** Uses `ReactDOM.createPortal` to render the toast notifications into a separate DOM node, allowing them to appear on top of all other content without being constrained by parent CSS.
* **Smooth Animations:** Toasts have fluid enter and exit animations for a polished user experience.
* **Manual Dismissal:** Users can also close a notification at any time by clicking the close button.
* **Modern "Glassmorphism" UI:** The main control panel features a popular semi-transparent, blurred background effect for a modern aesthetic.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface and managing state.
* **ReactDOM:** Used for rendering and specifically for `createPortal`.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling, layout, and animations.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-toast-notification.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-toast-notification
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several advanced React concepts:

* **React Portals:** Understanding when and how to use `ReactDOM.createPortal` to render components outside of their parent's DOM hierarchy, which is essential for modals, tooltips, and notifications.
* **`useEffect` for Timers & Cleanup:** Mastering the use of `setTimeout` within a `useEffect` hook to trigger actions after a delay, and implementing the cleanup function to prevent memory leaks.
* **Managing a Dynamic List:** Building logic to add items to a state array and have them automatically remove themselves after a set time.
* **Advanced CSS in JS:** Creating dynamic animations and applying conditional classes to create a polished and interactive UI.
