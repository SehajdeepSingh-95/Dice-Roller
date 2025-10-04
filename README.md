# 🎲 Dice Roller App

A fun **Dice Roller** built with **HTML, CSS, and Vanilla JavaScript**.  
Roll multiple dice at once and display both the rolled values and their corresponding dice images.

---

## 🚀 Features
- 🎲 **Multiple Dice Rolls** – Choose how many dice you want to roll.
- 🔄 **Random Results** – Each die roll generates a random value from 1 to 6.
- 🖼️ **Dice Images** – Displays images for each rolled dice side.
- ⚡ Instant roll results displayed dynamically.

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3** (for styling)
- **Vanilla JavaScript (ES6+)**
- **Dice PNG images** stored in an `/images` folder.

---


---

## 🖥️ Setup & Usage
### 1. Clone or Download the Project
```bash
git clone https://github.com/yourusername/dice-roller.git
cd dice-roller
<h1>Dice Roller 🎲</h1>

<input type="number" id="numOfRolls" placeholder="Enter number of dice">
<button onclick="rollDice()">Roll Dice</button>

<p id="diceResult"></p>
<div id="diceImages"></div>

<script src="script.js"></script>
