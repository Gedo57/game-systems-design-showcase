# Game Systems Design Showcase

A curated portfolio repository focused on **game systems design**, **technical design**, **combat systems**, **progression**, **economy balancing**, **puzzle flow**, and **implementation-ready documentation**.

This repository supports my profile as a **Technical Game Designer / Systems Designer** with hands-on implementation experience across **Unreal Engine**, **C++**, **Roblox/Lua**, and production-style frontend tools.

---

## Overview

This is not a single game project.

It is a focused design portfolio that shows how I break down gameplay systems, structure rules, define progression, document balancing logic, and translate design intent into implementation-ready technical specifications.

The goal is to demonstrate how I think as a designer who can connect:

- Player experience
- Core loops
- System rules
- Balancing logic
- UI/UX feedback
- Technical implementation constraints

---

## Featured Case Studies

| Case Study | Focus Area | Project Type |
|---|---|---|
| [LostPulse — Combat & Progression](docs/lostpulse-combat-progression.md) | Combat design, roguelite progression, relics, skills, meta upgrades | Unreal Engine / C++ |
| [BeatTheBlock — Match-3 Systems](docs/beattheblock-match3-systems.md) | Puzzle logic, special pieces, combo rules, mobile UX feedback | Unreal Engine / C++ |
| [Roblox Zombie Tycoon — Economy & Raids](docs/roblox-zombie-tycoon-economy.md) | Tycoon economy, automation, raid rules, rebirth progression, retention | Roblox / Lua |
| [DeadlyCuriosity — Objective & Puzzle Flow](docs/deadlycuriosity-objective-system.md) | Interaction systems, notebook objectives, puzzle dependencies, room flow | Unreal Engine / C++ |

---

## Focus Areas

- Gameplay Systems Design
- Technical Game Design
- Combat and Progression Systems
- Economy and Reward Balancing
- Puzzle and Objective Flow
- UI/UX System Design
- Player Feedback Design
- Retention and Progression Loops
- Implementation-Oriented Documentation

---

## Design Methodology

My systems design process usually follows this structure:

### 1. Define the Player Fantasy

Before designing rules, I define what the player should feel.

Examples:

- Powerful but vulnerable
- Clever for solving a puzzle
- Rewarded for optimizing a build
- Pressured by enemy placement
- Motivated to return after a run or session

### 2. Define the Core Loop

Every system needs a repeatable loop.

Example:

```txt
Action
→ Feedback
→ Reward
→ Decision
→ Escalation
→ Repeat
```

### 3. Break the System into Rules

I document the system as clear rules:

- Inputs
- Outputs
- Constraints
- Success states
- Failure states
- Edge cases
- Scaling behavior

### 4. Balance for Progression

Balancing is not only numbers.  
It is the relationship between pressure, reward, player power, learning, and pacing.

Important questions:

- What does the player understand in the first 5 minutes?
- When does the system start creating depth?
- What prevents one strategy from dominating?
- How does the system scale into mid-game and late-game?
- What feedback tells the player they made progress?

### 5. Translate Design into Implementation

Each case study is written to be useful for actual development.

That means documenting:

- Component responsibilities
- Data-driven values
- UI states
- Player feedback requirements
- Debugging needs
- Expansion points

---

## Case Study Format

Each breakdown follows a consistent structure:

```txt
1. Project Context
2. Design Goal
3. Core Player Loop
4. System Rules
5. Player Feedback
6. Balancing Notes
7. Technical Implementation Notes
8. Portfolio Value
```

This format makes each system easier to evaluate from both a design and development perspective.

---

## Projects Covered

### LostPulse

A 2D roguelite platformer focused on movement, combat timing, relics, active skills, permanent upgrades, enemy pressure, and run-based progression.

Key systems:

- Light / heavy / charge / air attacks
- Startup / active / recovery timing
- Relic-driven build variety
- Meta progression
- Safehouse upgrades
- Currency and reward loops

### BeatTheBlock

A mobile puzzle project focused on board logic, match detection, special pieces, combo resolution, and readable touch-first UI feedback.

Key systems:

- Match-3 board logic
- Rocket / bomb / color bomb specials
- Combo rules
- Dead-board detection
- Reshuffle logic
- Floating score and combo feedback

### Roblox Zombie Tycoon

A Roblox tycoon concept focused on machine progression, automation, raids, rebirths, daily rewards, and long-term retention.

Key systems:

- Machine unlock pipeline
- Worker automation
- Raid risk/reward rules
- Rebirth progression
- Daily and playtime rewards
- Leaderboards and social status systems

### DeadlyCuriosity

A first-person puzzle / escape-room style project focused on interaction flow, objective tracking, notebook updates, and puzzle dependency chains.

Key systems:

- Interactable objects
- Line trace interaction
- Prompt UI
- Notebook objective tracking
- Code panels
- Room-based puzzle progression

---

## Portfolio Value

This repository demonstrates my ability to work beyond high-level design ideas.

It shows how I:

- Structure gameplay systems
- Document implementation-ready rules
- Think about balance and progression
- Connect UX feedback with gameplay rules
- Design systems that can scale
- Communicate clearly with developers and teams

This repository is relevant for roles such as:

- Game Designer
- Technical Game Designer
- Systems Designer
- Gameplay Designer
- Level Designer
- Economy Designer
- Technical Designer

---

## Related Portfolio Projects

| Project | Type | Status |
|---|---|---|
| ResumePilot | Resume Builder SaaS frontend | Live demo available |
| NexaDash | SaaS admin dashboard | Live demo available |
| SET Store | E-commerce marketplace frontend | Live demo available |
| StudioTrack | Game production tracker | Frontend demo live, backend-ready repo |

---

## Related Links

- Portfolio: https://www.ahmedmostafa.click/
- LinkedIn: https://www.linkedin.com/in/ahmed-mostafa-gedo/
- Itch.io: https://gedoo57.itch.io/

---

## Current Scope

This repository contains design documentation and system breakdowns.

It does not include full production source code for all referenced projects because some projects are private, in development, or contain production-specific files.

The purpose of this repository is to present:

- Design thinking
- System architecture
- Balancing logic
- Gameplay structure
- Technical design clarity
- Implementation-ready documentation

---

## Repository Structure

```txt
game-systems-design-showcase/
├── README.md
├── docs/
│   ├── lostpulse-combat-progression.md
│   ├── beattheblock-match3-systems.md
│   ├── roblox-zombie-tycoon-economy.md
│   └── deadlycuriosity-objective-system.md
└── LICENSE
```

---

## License

This repository is intended as a professional portfolio and design documentation showcase.
