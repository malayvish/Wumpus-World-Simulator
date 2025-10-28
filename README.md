
# Wumpus World Simulator 👹

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2F<YOUR_USERNAME>%2F<YOUR_REPO_NAME>)

A fully responsive, modern Wumpus World Simulator built with pure HTML, CSS, and JavaScript. This project is a single-file, dependency-free application perfect for deployment on platforms like Vercel.

The Wumpus World is a classic example of a knowledge-based agent in AI. This simulator allows a human player to act as the agent, navigating a 4x4 grid to find gold while avoiding deadly pits and the fearsome Wumpus.

---

## 🚀 Live Demo

**Play the game live:** [**https://<YOUR_APP_NAME>.vercel.app/**](https://<YOUR_APP_NAME>.vercel.app/)

*(Replace the link above after you deploy to Vercel!)*

---

## 📸 Screenshots

### Desktop View
![Desktop Screenshot of Wumpus World Simulator](<path-to-your-desktop-screenshot.png>)

### Mobile View
![Mobile Screenshot of Wumpus World Simulator](<path-to-your-mobile-screenshot.png>)

*(**Tip:** Take screenshots of your project and add them to your repository. Then, update the paths above.)*

---

## ✨ Features

* **Fully Responsive Design:** Adapts to desktops, tablets (Surface Pro), and mobile phones.
* **Sticky Mobile Controls:** A dedicated control bar sticks to the bottom on mobile/tablet for a great touch-screen experience.
* **Dynamic UI:** Percepts (Stench, Breeze, etc.) and agent status update in real-time.
* **Audio Feedback:** Sound effects for every action (move, shoot, scream, win/lose) with a mute button in the navbar.
* **Dual Controls:** Play using either your **keyboard** (WASD) or the **on-screen buttons**.
* **Informational Modals:** Clean "How to Play" and "About" popups.
* **Modern Theme:** A colorful, neon-style dark mode UI.
* **Zero Dependencies:** Built with 100% Vanilla HTML, CSS, and JavaScript.
* **Deployment Ready:** A single `index.html` file that can be deployed instantly.

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3:** (Flexbox, Grid, Media Queries, Custom Properties)
* **Vanilla JavaScript (ES6+):** (DOM Manipulation, Web Audio API)

---

## 🎮 How to Play

### Goal
Find the gold (💰) and return to the starting cell [1, 1] to escape.

### Percepts
* **🤢 Stench:** The Wumpus is in an adjacent (not diagonal) room.
* **💨 Breeze:** A Pit is in an adjacent room.
* **✨ Glitter:** The Gold is in your current room.
* **💥 Bump:** You walked into a wall.
* **😱 Scream:** You successfully shot the Wumpus.

### Dangers
* **👹 Wumpus:** Entering the Wumpus's room is death (unless you have already shot it).
* **🕳️ Pit:** Entering a Pit's room is death.

### Controls

| Action | Keyboard | On-Screen |
| :--- | :---: | :---: |
| Move Forward | `W` or `↑` | **⬆️** |
| Turn Left | `A` or `←` | **⬅️** |
| Turn Right | `D` or `→` | **➡️** |
| Shoot Arrow | `F` | **Shoot** |
| Grab Gold | `G` or `Space` | **Grab** |

---

## 💻 How to Run Locally

Since this is a simple, single-file project, there is no build step.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/](https://github.com/)<malayvish>/<Wumpus-World-Simulator>.git
    ```
2.  **Navigate to the directory:**
    ```sh
    cd <Wumpus-World-Simulator>
    ```
3.  **Open the file:**
    Simply double-click the `index.html` file to open it in your favorite web browser.

---

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
