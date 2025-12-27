# Animals Memory Blocks

A memory matching game with animal icons built with TypeScript. The game features dark and light modes, customizable time limits, and variable difficulty. The goal is to match all pairs before time runs out with the fewest wrong attempts.

## Features

- **Customizable Game Settings**:
  - Time Limits: 10 seconds to 4 minutes
  - Animal Variety: Choose 4-10 different animals (8-20 blocks)
- **Progress Tracking**:
  - Previous game time displayed before new rounds
  - Best time preserved in local storage
- **Theme Control**:
  - Light/dark mode toggle
  - Persistent theme preference
- **Responsive Design**:
  - Adapts to all screen sizes
  - Optimized grid layouts

## Installation

```bash
git clone https://github.com/a8k-legacy/animals-memory-blocks.git
cd animals-memory-blocks
npm install
npm run dev
```

## How to Play

1. **Game Setup**:
   - Select number of animals (4-10)
   - Set timer duration (10s-4m)
   - Click "New Game"

2. **Gameplay**:
   - Match animal pairs before time expires
   - Each selection reveals an animal
   - Mismatches auto-flip after 1 second
   - Previous game time shown at round start

3. **Winning**:
   - Success: Match all pairs in time
   - Failure: Time runs out
   - Restart with same/different settings

## Technical Implementation

- **Core Stack**:
  - TypeScript
  - CSS Grid/Flexbox
  - HTML5

## Enhanced Version

A restyled version of this game may be featured in a future collection.

---

*Part of the A8K Legacy archive—a collection of early projects and learning experiments by [Saif Abdelrazek](https://saifabdelrazek.com).*
