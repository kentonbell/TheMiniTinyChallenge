# 💻 Introduction
This IntelliJ-based project is a collection of interactive console mini-games written in Java.  
It focuses on logic design, modular structure, algorithmic thinking, and scalable game expansion.

One or two player

The CPU opponent makes decisions using randomized guesses influenced by game difficulty, creating lightweight but replayable gameplay experiences.

---

## 📚 Index

- [About](#-about)
- [Usage](#-usage)
- [Development](#-development)
- [Acknowledgements](#-acknowledgements)

---

## 🧭 About

This project is a growing collection of Java mini-games playable through the console.  
Each game emphasizes problem solving, turn-based interaction, and clean program structure.

Currently implemented games:

- [x] Guess Number  
- [x] Tic Tac Toe  
- [x] Unscramble a Word  
- [x] Flip a Coin  
- [x] Name Countries and Capitals
  - All Capitals
  - All Countries
  - Asia
  - Europe
  - Africa
  - Oceania
  - North America
  - South America  
- [x] Increasing Word Length Spelling Challenge  
- [x] Anagrams (7-letter word competition)  
- [x] Higher or Lower  
  - 6 guesses → 1–100  
  - 9 guesses → 1–1,000  
  - 13 guesses → 1–10,000  
  - 16 guesses → 1–100,000  
  - 19 guesses → 1–1,000,000  
- [x] Wordle  
- [x] Number Patterns (turn-based sequence continuation)

There are currently **19 total playable game modes**, including variations within games.

---

## ▶️ Usage

### ☕ IntelliJ Setup

1. Install **IntelliJ IDEA** (Community or Ultimate)
2. Open IntelliJ
3. Select:
   ```
   File → Open
   ```
4. Choose the project root folder
5. Allow IntelliJ to index and build the project

### ▶ Running the Program

1. Navigate to the main class inside:
   ```
   src
   ```
2. Right-click the main file
3. Select:
   ```
   Run 'Main'
   ```
4. Follow console prompts to select and play games

---

## 🛠 Development

### 📋 Pre-Requisites

- IntelliJ IDEA
- Java JDK (17 or newer recommended)
- Basic Java knowledge

---

### 🖥 Development Environment

1. Clone or download the repository
2. Open using IntelliJ
3. Ensure Project SDK is set:
   ```
   File → Project Structure → SDK
   ```
4. Build project automatically when prompted

---

### 📂 File Structure

Important folders shown (expanded to core source organization).

```
.
├── src
│   ├── main
│   ├── games
│   ├── utilities
│   └── files
│       └── continents
├── .idea
├── README.md
└── pom.xml / build files
```

| No | File/Folder | Details |
|----|-------------|---------|
| 1  | src | Main Java source code |
| 2  | src/files | Game resources and data |
| 3  | src/files/continents | Country/capital datasets |
| 4  | .idea | IntelliJ configuration |
| 5  | README.md | Project documentation |

---

### ▶️ Build

1. Open project in IntelliJ
2. Select:
   ```
   Build → Build Project
   ```
3. Run the main class to start gameplay

---

### 🚧 Future Development

Planned or hypothetical additions:

- [ ] Word Chain  
  Players say words starting with the last letter of the previous word.

- [ ] Acronym Game  
  Players invent meanings for acronyms (e.g., NASA).

#### FOR AN iOS APP
- [ ] Only three randomly selected games available per session
- [ ] Dots and Boxes selectable
- [ ] Possibly remove Connect Four
- [ ] Palindromes limited to random selection pool

#### Experimental Ideas
- [ ] Hangman  
- [ ] Alphabet Category Game  
- [ ] Two Truths and a Lie  
- [ ] Word Search  
- [ ] Connect Four  
- [ ] Find Palindromes  
- [ ] Rock Paper Scissors  
- [ ] Dots  
- [ ] Mastermind / 20 Questions

---

## 🙏 Acknowledgements

Developed by **Kenton Bell**

© kentn 2026  
℗ kentn
