# 🎮 Game Save Index

A visually stunning, interactive showcase for your game save files, powered by a dynamic 3D background and automatic updates from your Git repository.

---

### ✨ [Live Demo](https://ravisairockey.github.io/Game-save-index/)

---

## 🚀 Features

- **⚡ Dynamic Updates:** Automatically detects and displays `.zip` files from the `saves` directory.
- **🌌 Interactive 3D Background:** A mesmerizing, animated background built with Three.js.
- **💎 Glassmorphism UI:** A sleek, modern "frosted glass" interface for all UI elements.
- **📱 Responsive Design:** A fluid layout that works beautifully on all screen sizes.
- **✨ Minimalist Interface:** A clean, unobtrusive UI that prioritizes the content.

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

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js"/>
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=gsap&logoColor=white" alt="GSAP"/>
</p>

---


