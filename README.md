<div align="center">

# 👑 ROYALE INSIGHT

### ⚔️ Analyze Smarter. Battle Better. Climb Higher.

**A Clash Royale analytics dashboard built by a player, for players.**

Track your battles, analyze your decks, discover your strengths, and take your gameplay to the next level.

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

</div>

---

## 👋 Meet the Developer

Hey! I'm **Ojas Kaushik**, a Computer Science student, software developer, and highly competitive Clash Royale player! ⚔️

With **14,000+ trophies 🏆**, **multiple Ultimate Champion finishes 👑**, and a **Top 10,000 Global Finish 🌍**, I've spent countless hours mastering strategies, refining decks, and competing at a high level.

For me, **Clash Royale isn't just a game, it's a passion built around strategy, competition, and constant improvement.** From pushing the ladder to competing against some of the strongest players, I've always been driven to reach the next level.

That's exactly what inspired **Royale Insight**, combining my experience as a competitive player with my passion for computer science and software engineering to create something meaningful for the Clash Royale community.

---

## 🚀 What is Royale Insight?

**Royale Insight** is a web-based Clash Royale analytics platform designed to help players make smarter decisions both inside and outside the arena.

Whether you're grinding trophies, experimenting with new decks, or reviewing your recent battles, Royale Insight brings your gameplay information together in one clean, interactive dashboard.

> ⚡ Every battle tells a story. Royale Insight helps you understand it.

---

## ✨ Features

### 📊 Player Dashboard
- View player profiles and trophy statistics.
- Track personal best trophies.
- Monitor recent win rates and battle activity.
- Explore player performance in a modern dashboard.

### ⚔️ Battle History
- Review recent victories and defeats.
- See opponents, battle modes, and crown results.
- Track trophy gains and losses when available.
- Identify patterns across recent matches.

### 🃏 Deck Analyzer
- View your current eight-card deck.
- Calculate average elixir cost.
- Identify potential deck strengths and weaknesses.
- Receive rule-based suggestions for elixir balance, spell coverage, and air defense.

### 📈 Performance Analytics
- Explore win-rate visualizations.
- Compare recent wins and losses.
- Monitor important gameplay metrics.
- Understand your performance at a glance.

### 🔎 Player Search
- Search for players using their Clash Royale player tags.
- Retrieve player information through the official Clash Royale API when configured.
- Explore recent battle logs and equipped decks.

### 🎮 Demo Mode
- Explore Royale Insight without an API token.
- Experience the dashboard with clearly labeled sample data.
- Test the interface before enabling live player lookup.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| ⚛️ React | Frontend interface |
| ⚡ Vite | Development and build tooling |
| 🎨 CSS | Responsive dashboard styling |
| 🟢 Node.js | Backend runtime |
| 🚀 Express.js | Backend API |
| 📊 Recharts | Data visualizations |
| 🎯 Lucide React | Icons and UI elements |
| 👑 Clash Royale API | Player and battle information |

---

## 💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ojaskaushik/clash.royale-insight.git
cd clash.royale-insight
```

### 2. Install Dependencies

Make sure you have Node.js installed.

```bash
npm install
npm install --prefix frontend
npm install --prefix backend
```

### 3. Start the Application

```bash
npm run dev
```

Open the local frontend URL displayed in your terminal, typically:

**http://localhost:5173**

The application starts in demo mode, so you can explore the dashboard without configuring an API token.

---

## 🔑 Enable Live Player Lookup

Royale Insight supports optional integration with the official Clash Royale API.

**Step 1:** Visit the [Clash Royale Developer Portal](https://developer.clashroyale.com/).

**Step 2:** Create a developer API token. IP allowlisting may be required.

**Step 3:** Inside the `backend` folder, copy `.env.example` to `.env`.

**Step 4:** Set your API token:

```env
CLASH_ROYALE_API_TOKEN=your_api_token_here
```

**Step 5:** Restart the development server:

```bash
npm run dev
```

**Step 6:** Enter a Clash Royale player tag in the dashboard to retrieve available live player information.

> 🔒 Never expose your API token in frontend code or commit your `.env` file to GitHub.

---

## 🧠 How Deck Analysis Works

Royale Insight currently uses transparent, rule-based analysis to evaluate selected aspects of a deck.

It considers:

- ⚡ Average elixir cost
- 🔥 Spell coverage
- 🛡️ Air-defense options
- 🃏 Overall card composition

These suggestions are intended to provide helpful starting points for deck evaluation.

**Note:** The analyzer is not currently an AI coach, live meta predictor, or full battle replay analysis system.

---

## 🗺️ Future Vision

Royale Insight is an evolving project, with opportunities to introduce more advanced analytics and competitive tools.

Potential future improvements include:

- 🤖 Advanced deck recommendations
- 📊 Historical performance tracking
- ⚔️ Matchup and opponent analysis
- 🏆 Trophy progression visualizations
- 🃏 Expanded card and deck statistics
- 📱 Improved mobile experience
- 🧠 More intelligent gameplay insights

The long-term vision is to build a platform that helps Clash Royale players make more informed decisions and improve consistently.

---

## ⚠️ Disclaimer

Royale Insight is an **unofficial, fan-made project** and is not affiliated with, endorsed by, or sponsored by Supercell.

Clash Royale and its associated assets are trademarks of Supercell.

The official Clash Royale API has limitations, including restricted historical data and no access to full replay actions. Some visualizations use clearly labeled illustrative data.

---

<div align="center">

### 👑 Built with passion for Clash Royale.

**14K+ Trophies 🏆 | Multiple-Time Ultimate Champion 👑 | Top 10K Global Finisher | Developer 💻**

*Keep pushing. Keep improving. See you in the arena.* ⚔️

**Made by [Ojas Kaushik](https://github.com/ojaskaushik)**

</div>
