<p align="center">
  <img src="https://raw.githubusercontent.com/bcheban/2048_js-game/master/src/images/reference.png" alt="2048 Game Preview" width="320" />
</p>

<h1 align="center">JS 2048 Game</h1>

<p align="center">
  <strong>A browser implementation of the classic 2048 puzzle game — built with vanilla JavaScript, SCSS, and Parcel.</strong>
</p>

<p align="center">
  <a href="https://bcheban.github.io/2048_js-game/">Live Demo</a> |
  <a href="https://github.com/bcheban/2048_js-game">GitHub Repo</a>
</p>

---

## 📌 Project Name & Description

**JS 2048 Game** is a faithful recreation of the classic **2048** sliding-tile puzzle, written in **vanilla JavaScript** with no external framework dependencies.

The primary purpose of this project is to showcase clean, object-oriented JavaScript logic. The entire game logic is encapsulated in a dedicated `Game` class (`src/modules/Game.class.js`), completely isolated from DOM rendering and event handling (`src/scripts/main.js`). The project features a fully responsive layout, robust code styling, and comprehensive test coverage.

---

## 🌐 Live Preview

You can play the fully functional game here:
🚀 **[Live Demo on GitHub Pages](https://bcheban.github.io/2048_js-game/)**

---

## ✨ Key Features

- **Smooth Tile Movement** — fluid animations for tile movements and merges.
- **Responsive Design** — playable across desktop, tablet, and mobile devices.
- **Score Tracking** — the current score is updated in real time as tiles merge.
- **Win & Lose Conditions** — the player is notified with the appropriate message when the 2048 tile is reached or no moves are left.
- **Restart Functionality** — the game can be reset at any time with a single click.

---

## 🧩 Challenges

Building **JS 2048 Game** involved solving several non-trivial problems that are typical of small-but-complete browser games:

1. **Tile Movement & Merging** — implementing the row/column shifting and merge rules so that tiles behave exactly as expected on every keypress.
2. **Responsive Design** — keeping the board playable and visually balanced from **1280px** down to **320px** required careful layout testing.
3. **Animation Performance** — keeping tile transitions smooth without dropping frames, even during rapid input.
4. **Game State Management** — tracking the board, score, best score, and win/lose state in a single source of truth (the `Game` class) without leaking state into the DOM layer.

---

## 🛠 Technologies Used

### Core Language & Build Tools
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Parcel-21374B?style=for-the-badge&logo=parcel&logoColor=E2C636" alt="Parcel" />
</p>

### Styling
<p>
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS" />
  <img src="https://img.shields.io/badge/Stylelint-263238?style=for-the-badge&logo=stylelint&logoColor=white" alt="Stylelint" />
</p>

### Testing
<p>
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />
  <img src="https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white" alt="Cypress" />
</p>

### Linting & Formatting
<p>
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" alt="Prettier" />
  <img src="https://img.shields.io/badge/LintHTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="LintHTML" />
</p>

### CI / CD & Deployment
<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages" />
</p>

---

## ⚙️ Technical Requirements

Before running the project, make sure your environment meets the following requirements:

- A modern web browser — the latest version of **Chrome**, **Firefox**, **Safari**, or **Edge**.
- **Node.js** version **14.x** or newer.
- **NPM** version **6.x** or newer.

---

## 🛫 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### 1. Clone the repository
```bash
git clone https://github.com/bcheban/2048_js-game.git
cd 2048_js-game
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the local development server
```bash
npm start
```

### 4. Run the tests (optional)
```bash
npm test
```

### 5. Build for production (optional)
```bash
npm run build
```

---

## 🎮 Usage

After starting the dev server, the game is available at **[http://localhost:8080](http://localhost:8080)**.

- Press **Start** to spawn the first two tiles.
- Use the **arrow keys** (← ↑ → ↓) to slide all tiles in the chosen direction.
- Tiles with the same value **merge** when they collide, doubling their value and adding it to the score.
- Reach the **2048** tile to win. The game ends when no moves are left.
- Press **Restart** at any time to start a new game.

---

## 📐 Design Specifications

The layout is designed and tested against the following reference sizes:

| Device  | Width    |
| ------- | -------- |
| Desktop | 1280px   |
| Tablet  | 640px    |
| Mobile  | > 320px  |

## 📊 Lighthouse

<p>
  <img src="https://bohdancheban-portfolio.vercel.app/api/lighthouse?url=https%3A%2F%2Fbcheban.github.io%2F2048_js-game%2F&strategy=mobile" alt="Lighthouse mobile scores" />
  <img src="https://bohdancheban-portfolio.vercel.app/api/lighthouse?url=https%3A%2F%2Fbcheban.github.io%2F2048_js-game%2F&strategy=desktop" alt="Lighthouse desktop scores" />
</p>


<p align="center">
  Made with ❤️ by <a href="https://github.com/bcheban">@bcheban</a>
</p>
