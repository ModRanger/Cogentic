# Cogentic- Train your CoFOunder. 🥚

## Project Overview
Dont find your cofounder, train them. 

## Design Theme
Mysterious on the websit  starting with an oversized, mysterious egg interface.
- Dark background with neon accents
- Retro-futuristic Tamagotchi inspiration
- Minimalist yet engaging interface

## Core Features

### 1. The Egg (Landing Page)
- Oversized egg centerpiece with:
  - Subtle pulsing glow animation
  - Neon color palette (suggest: purple, cyan, hot pink)
  - Floating/hovering effect
- Single input field for Twitter handle(make it super user unfriendly to input, i want to make it hard)
- Hidden changelog that appears **after** handle submission
- Easter egg interactions

#### Technical Specifications
- Background: Pure black (#000000)
- Egg dimensions: 60% of viewport height
- Glow effect: CSS box-shadow with multiple layers
- Animation: Subtle breathing effect (3s cycle)

### 2. User Interface Elements
- Twitter handle input field:
  - Neon border glow on focus
  - Cyberpunk-style input validation
  - Success animation triggers changelog reveal
- Changelog:
  - Random position on screen
  - Retro terminal aesthetic
  - Typewriter text effect

## Implementation Guidelines

### CSS Variables
```css
:root {
  --neon-primary: #ff00ff;
  --neon-secondary: #00ffff;
  --neon-tertiary: #ff00aa;
  --glow-strength: 0 0 10px;
}# Cogentic
Don't find your next cofounder, train them.


