# BeatTheBlock — Match-3 & Mobile Puzzle Systems Case Study

## Project Context

**BeatTheBlock** is a mobile puzzle game concept built around two modes:

- Classic block-placement mode
- Match-3 mode inspired by modern mobile puzzle games

The project focuses on responsive board interaction, satisfying chain reactions, combo feedback, and mobile-first UX.

---

## Design Goal

The goal was to create a puzzle system that feels:

- Easy to understand
- Satisfying to interact with
- Visually responsive
- Scalable through special pieces and combo rules
- Suitable for mobile play sessions

---

## Core Player Loop

```txt
Read board state
→ Choose a move
→ Place / swap / match pieces
→ Trigger clears
→ Generate score and feedback
→ Create specials or combos
→ Continue until objective or fail state
```

---

## Match-3 System

The Match-3 mode is built around:

- Grid-based board logic
- Swap validation
- Match detection
- Board clearing
- Gravity / refill behavior
- Special piece generation
- Combo resolution
- Dead-board detection
- Reshuffle logic

---

## Special Pieces

| Special | Function |
|---|---|
| Rocket | Clears a row |
| Column Rocket | Clears a column |
| Bomb | Clears an area |
| Color Bomb | Clears all pieces of one color |

---

## Combo Rules

Special combinations increase depth and player satisfaction.

| Combo | Result |
|---|---|
| Rocket + Rocket | Cross clear |
| Bomb + Bomb | Larger area explosion |
| Rocket + Bomb | Rocket burst area |
| Color Bomb + Normal | Clears all of that color |
| Color Bomb + Rocket | Converts matching color pieces into rockets |
| Color Bomb + Bomb | Converts matching color pieces into bombs |
| Color Bomb + Color Bomb | Full board clear |

---

## Feedback Design

Feedback is critical in mobile puzzle games.

Important feedback layers:

- Board highlight
- Drag preview
- Swap animation
- Clear animation
- Floating score text
- Combo popups
- Special piece effects
- Fail / success state messaging

Example combo feedback:

```txt
Cool
Amazing
Unbelievable
```

These popups reinforce player accomplishment and make chain reactions feel rewarding.

---

## Mobile UX Considerations

The design must support:

- Touch-first input
- Clear hit areas
- Minimal visual clutter
- Readable board state
- Smooth animations
- Fast retry flow
- Portrait or fixed mobile orientation depending on mode

---

## Balancing Notes

Important balancing questions:

- How often should specials appear?
- How much score should each clear give?
- How difficult should objectives become over time?
- When should the game reshuffle?
- How much randomness is acceptable?
- How many moves should players need per objective?

The goal is to create a fair challenge curve without making outcomes feel random.

---

## Technical Implementation Notes

The system can be divided into:

- Board Manager
- Tile Data
- Match Detection
- Special Piece Resolver
- Combo Resolver
- Score System
- HUD Widget
- Drag Visual Widget
- Game Over / Win State Widgets

This structure separates gameplay logic from presentation and improves iteration speed.

---

## Portfolio Value

This case study demonstrates:

- Puzzle system design
- Mobile UX thinking
- Combo logic design
- Board-state management
- Feedback and animation planning
- Technical design for scalable gameplay rules
