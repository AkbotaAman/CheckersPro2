# CheckersPro

CheckersPro is a modern web platform for playing checkers online.  
The goal is not just to create a basic checkers board, but to build a product that can grow into a real strategy gaming service.
## Product Vision

CheckersPro is designed as a strategy-thinking platform where users can play, learn, compete, and personalize their experience.

Instead of being only a simple board game, CheckersPro focuses on:

- strategic thinking
- player improvement
- social competition
- personalization
- long-term engagement

## Planned Creative Features

### 1. Smart Opening

The app will remember the player’s most common first three moves.

When a new game starts, the user will see:

> Continue with your usual opening?

This saves time and makes the game feel personalized.

### 2. AI Coach

After each game, users will be able to discuss the match with AI.

If the user loses:

> Discuss with AI how you could have won

If the user wins:

> Discuss with AI how to improve your skills

The AI Coach will explain:

- missed captures
- risky moves
- better move options
- why the player lost or won
- how to improve future strategy

### 3. Strategy Archetypes

The app will analyze playing style and assign a strategy profile.

Examples:

- Aggressive
- Defensive
- Tactical
- Chaotic
- Risk Taker
- Patient Strategist

This creates a psychological profile system that makes the game more personal and memorable.

### 4. City Identity and Leaderboards

CheckersPro will include city-based rankings.

Example:

> Top Strategic Thinkers in Almaty

This adds a local competitive identity and makes the leaderboard more engaging.

### 5. Certificates

Players will earn certificates after mastering specific skills.

Examples:

- Tactical Awareness
- Defensive Mastery
- Pattern Recognition
- Long-Term Planner
- Strategic Thinker

Certificates can be shared as proof of progress.

### 6. Custom Game Creator

Users will be able to create their own checkers-based games with AI.

The user can describe custom rules, and the platform will help generate a new game mode using the same board.

Example:

> I want pieces to move diagonally, but after a capture they can jump again.

### 7. Design Creator

Users will be able to customize the look of their game.

Planned options:

- piece colors
- board colors
- themes
- visual effects

This can later become part of a creator marketplace.

### 8. Monetization Without Ads

CheckersPro will not rely on ads.

Possible premium features:

- deeper AI analysis
- advanced puzzles
- personalized improvement statistics
- premium board themes
- special AI coach personalities
- creator tools

## Why This Is Valuable

CheckersPro turns a traditional board game into a modern strategy platform.

It helps users:

- improve decision-making
- recognize patterns
- evaluate risk
- think ahead
- learn from mistakes
- compete socially
- improve creativity by building own game rules and creating own designs with a possibily to sell

## Future Goal

The long-term goal is to make CheckersPro not only an online checkers game, but a full strategy learning and competition platform.

## Current Version

This is a multiplayer checkers game built using Node.js (Express.js) for the backend and HTML, CSS, Javascript for the frontend and Socket.IO for real-time communication. It allows players to play checkers with others in real-time.

## Current Features

- Real-time multiplayer checkers game.
- Clean and user-friendly interface.
- Ability for two users to join and play the game live.
- Login and play with active players.
- Chat globally with all the active players.

## Current Demo

To play the game, visit the [deployment link](https://checker-app-szap.onrender.com/).

## Installation

1. Clone this repository.
2. Run `npm install` to install the dependencies for both the frontend and backend.
3. Configure the necessary environment variables for the backend.
4. Install `env-cmd` using command `npm i -g env-cmd` as its being used to access env variables.
5. Start the project with `npm run dev`.


## Technologies Used currently

- Backend: Node.js, Express.js, SocketIO, MongoDB
- Frontend: HTML, CSS, Js, SocketIO
