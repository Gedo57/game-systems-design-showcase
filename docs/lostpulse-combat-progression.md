# LostPulse — Combat & Progression Systems Case Study

## Project Context

**LostPulse** is a 2D roguelite platformer built around responsive movement, combat readability, relic-driven builds, and run-based progression.

The player engages with enemies through fast movement, melee combat, active skills, relic effects, and permanent meta upgrades.

---

## Design Goal

The goal was to create a combat and progression structure that supports:

- Fast side-scroller movement
- Clear attack windows
- Build variety through relics and skills
- Roguelite replayability
- Permanent progression without removing challenge

---

## Core Player Loop

```txt
Explore level
→ Fight enemies
→ Earn currency / rewards
→ Pick upgrades or relics
→ Improve build
→ Survive harder encounters
→ Die or complete run
→ Spend meta currency
→ Start stronger next run
```

---

## Combat System

The combat model is based on different attack types:

| Attack Type | Purpose |
|---|---|
| Light Attack | Fast, low-risk, basic damage |
| Heavy Attack | Slower, higher damage, commitment-based |
| Charge Attack | Requires timing and positioning |
| Air Attack | Supports mobility and aerial combat |

The goal is to make each attack type useful in a different situation instead of making one option strictly dominant.

---

## Combat Timing Structure

Each attack can be understood as three major phases:

```txt
Startup
→ Active
→ Recovery
```

### Startup
The anticipation window before the hit becomes active.

### Active
The hit detection window where the attack can damage enemies.

### Recovery
The vulnerability window after the attack.

This structure helps create readable combat where timing, spacing, and commitment matter.

---

## Progression Systems

LostPulse uses multiple progression layers:

### Run-Based Progression

- Relics
- Temporary upgrades
- Skill choices
- Currency pickups
- Combat rewards

### Meta Progression

- Permanent health upgrades
- Permanent damage upgrades
- Critical chance upgrades
- Meta currency
- Safehouse upgrade flow

---

## Relic Design

Relics are divided into broad categories:

### Offensive Relics
Improve damage, attack frequency, critical potential, or elemental effects.

### Defensive Relics
Improve survivability, mitigation, healing opportunities, or damage reflection.

### Active Skills
Examples:

- Fireball — applies burn pressure
- Ice Ball — slows enemies
- Lightning Ball — burst damage / chain potential
- Reflect Shield — reflects incoming projectiles

---

## Balancing Notes

Key balancing goals:

- Early upgrades should feel immediately useful.
- Late upgrades should create build identity.
- Meta progression should reduce friction, not erase difficulty.
- Relics should create meaningful choices rather than flat stat stacking.
- Enemy pressure should scale with player power.

---

## Technical Implementation Notes

The project structure uses a component-oriented approach:

- Health Component
- Combat Component
- Hitbox Component
- Hurtbox Component
- Currency Component
- Meta Currency Subsystem
- Save Game structure
- Shop / relic / weapon data assets

This allows combat, damage, rewards, and progression to remain modular.

---

## UI/UX Considerations

The player needs clear feedback for:

- Damage taken
- Damage dealt
- Currency gained
- Upgrade selection
- Relic effects
- Death flow
- Safehouse interactions
- Meta upgrade spending

Clear feedback is critical because roguelite systems depend heavily on repeated learning.

---

## Portfolio Value

This case study demonstrates:

- Combat system design
- Roguelite progression design
- Modular technical design
- Reward loop structuring
- Meta progression balancing
- C++ implementation-oriented thinking
