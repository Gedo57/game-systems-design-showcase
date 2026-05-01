# DeadlyCuriosity — Objective, Interaction & Puzzle Flow Case Study

## Project Context

**DeadlyCuriosity** is a first-person puzzle / escape-room style game built in Unreal Engine.

The player is a journalist trapped by a secret organization and must escape by solving room-based puzzles, interacting with objects, and following notebook-driven objectives.

---

## Design Goal

The goal was to create a structured puzzle flow where the player always understands:

- What they can interact with
- What the current objective is
- What information has been discovered
- Which room or puzzle is currently relevant
- How progress is tracked

---

## Core Player Loop

```txt
Explore room
→ Inspect object
→ Discover clue
→ Update notebook objective
→ Solve puzzle
→ Unlock next area
→ Repeat with higher complexity
```

---

## Interaction System

The interaction system is based on:

- Line trace detection
- Interactable interface
- Highlight feedback
- Prompt widget
- Cooldown handling
- Object-specific interaction logic

The goal is to keep interactions consistent while allowing each puzzle object to have unique behavior.

---

## Notebook Objective System

The Notebook acts as the player’s objective tracker.

It supports:

- Current objective display
- Room-based progression
- Object discovery tracking
- Clue/state updates
- Puzzle dependency tracking

This prevents players from feeling lost in a multi-room puzzle structure.

---

## Puzzle Structure

Puzzle flow can include:

- Code panels
- Locked doors
- Inspectable clues
- Room flags
- Multi-step unlock conditions
- Power / basement systems
- Success and failure messaging

Example code puzzle structure:

```txt
Find clue
→ Read clue
→ Enter code
→ Validate code
→ Show success/failure feedback
→ Unlock door or next objective
```

---

## UI/UX Requirements

Important widgets include:

- Interaction Prompt
- Notebook
- Inspect View
- Code Entry Panel
- Pause Menu
- Settings Menu
- Objective Updates
- Success / Failure Feedback

The UI should be readable, minimal, and diegetic enough to support the mystery tone.

---

## Technical Implementation Notes

The system can be structured around:

- Interactable Interface
- Interaction Component
- Objective / Chapter Manager
- Puzzle Actors
- Door Actors
- Notebook Widget
- Prompt Widget
- Code Panel Widget

This keeps puzzle-specific logic separate from the core interaction layer.

---

## Progression Design

Puzzle progression should escalate through:

1. Simple object inspection
2. Basic locked door
3. Code-based puzzle
4. Multi-object dependency
5. Room-to-room objective chain
6. Larger environmental puzzle

This creates learning before complexity.

---

## Balancing Notes

Puzzle difficulty is not only about the answer.  
It is also about:

- Clue visibility
- Objective wording
- Room layout
- Interaction affordance
- Feedback clarity
- Penalty for wrong attempts
- Whether the player can recover from mistakes

---

## Portfolio Value

This case study demonstrates:

- Puzzle flow design
- Interaction system planning
- Objective system design
- UI/UX for first-person games
- Technical design for Unreal Engine
- Implementation-ready documentation
