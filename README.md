# Tamagotchi-Digital-pet
Interactive react app with retro tamagotchi retro ASCII style that evolves based on coding activity logs
# CodeCreature 🎮

A retro tamagotchi-style digital pet that grows based on your coding habits.
Built with React + Vite.

## What it does

The pet evolves through 5 stages — Egg → Sprout → Junior → Senior → Legend —
based on the coding activities you log. Neglect it and it gets hungry and tired.
Keep training and it levels up.

## Activities

- ⚡ **Solve Problem** — Log a LeetCode or coding challenge (+12 XP)
- ◉ **Study Session** — Log any learning: courses, docs, tutorials (+7 XP)
- ♥ **Feed & Rest** — Restore health and energy

## Features

- 5 evolution stages with unique ASCII art per stage
- Mood system — pet reacts based on health, energy, and streak
- Streak bonus — 3+ activities in a row grants +40% XP
- Passive decay — pet gets weaker over time if neglected
- Persistent progress via localStorage — your pet survives page refreshes

## Tech Stack

- React (hooks: useState, useEffect, useCallback)
- Vite
- Pure inline CSS + CSS keyframe animations
- localStorage for persistence

## Running locally
```bash
npm install
npm run dev
```

## What I learned

- React state management across multiple interdependent values
- Using useEffect for timers, side effects, and data persistence
- Building a game loop with passive decay and streak mechanics
- CSS animations and retro aesthetic design

## Future ideas

- Connect to real LeetCode / GitHub API for automatic activity tracking
- Daily goals and weekly stats view
- Mobile app version
