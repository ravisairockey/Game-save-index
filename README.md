# 🎮 Game Save Index

<p align="center">
  <img src="https://raw.githubusercontent.com/ravisairockey/Game-save-index/main/game-save-index-banner.svg" alt="Game Save Index Banner">
</p>

A visually stunning, interactive showcase for your game save files, powered by a dynamic 3D background and automatic updates from your Git repository.

---

### ✨ [Live Demo](https://ravisairockey.github.io/Game-save-index/)

---

## 🚀 Features

- **Dynamic Updates:** Automatically detects and displays `.zip` files from the `saves` directory in your GitHub repository.
- **Interactive 3D Background:** A mesmerizing, animated neural network background built with Three.js.
- **Glassmorphism UI:** A sleek, modern "frosted glass" interface for the save file cards.
- **Responsive Design:** A fluid layout that works beautifully on all screen sizes, from mobile to desktop.
- **Minimalist Interface:** A clean, unobtrusive UI that prioritizes the content and the visual experience.

## ⚙️ How It Works

This project uses the GitHub API to fetch the contents of the `/saves` directory in this repository. The JavaScript then dynamically generates a "card" for each `.zip` file it finds, creating a direct download link. This means that whenever you push a new save file to the `saves` folder, the website updates automatically.

## 📂 How to Use

1.  **Add your save file:** Place your game save (in `.zip` format) into the `/saves` directory in your local repository.
2.  **Commit and push:**
    ```bash
    git add .
    git commit -m "Add new game save"
    git push
    ```
3.  **Done!** The new save file will now appear on the website.

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with advanced features like CSS Grid and custom properties)
- **JavaScript** (ES6 Modules)
- **Three.js** for the interactive 3D background
- **GSAP** for UI animations

---

<p align="center">
  This project was built with the assistance of an AI software engineer.
</p>
