# Tic-Tac-Toe Game

A modern, interactive Tic-Tac-Toe (XO) game built with Next.js, React, and TypeScript. This project features a clean, responsive design and smooth gameplay experience.

## 🎮 Features

- **Interactive Gameplay**: Click on any cell to make your move
- **Turn-based System**: Alternates between Circle (O) and Cross (X) players
- **Win Detection**: Automatically detects winning combinations and declares the winner
- **Draw Detection**: Recognizes when the game ends in a draw
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Real-time Updates**: Game state updates instantly with each move

## 🚀 Getting Started

### Prerequisites

Make sure you have Node.js installed on your machine (version 18 or higher recommended).

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd xo-nextjs-game
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to play the game.

## 🛠️ Built With

- **Next.js 15.3.5** - React framework for production
- **React 19.0.0** - JavaScript library for building user interfaces
- **TypeScript 5** - Typed superset of JavaScript
- **CSS Modules** - Scoped CSS styling

## 📁 Project Structure

```
xo-nextjs-game/
├── app/
│   ├── components/
│   │   └── cell.tsx          # Individual game cell component
│   ├── globals.css           # Global styles
│   ├── layout.tsx           # Root layout component
│   ├── page.tsx             # Main game page
│   └── page.module.css      # Page-specific styles
├── public/                  # Static assets
├── package.json            # Project dependencies and scripts
└── README.md              # Project documentation
```

## 🎯 How to Play

1. The game starts with Circle (O) player's turn
2. Click on any empty cell to place your mark
3. Players alternate turns between Circle (O) and Cross (X)
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
5. If all cells are filled without a winner, the game ends in a draw

## 🔧 Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the app for production
- `npm start` - Runs the built app in production mode
- `npm run lint` - Runs ESLint to check for code issues

## 🎨 Game Logic

The game implements the following winning combinations:
- Horizontal: [0,1,2], [3,4,5], [6,7,8]
- Vertical: [0,3,6], [1,4,7], [2,5,8]
- Diagonal: [0,4,8], [2,4,6]


**Enjoy playing Tic-Tac-Toe! 🎉**
