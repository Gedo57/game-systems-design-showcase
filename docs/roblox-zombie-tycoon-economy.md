# Roblox Zombie Tycoon — Economy, Automation & Raid Systems Case Study

## Project Context

**Roblox Zombie Tycoon** is a systems-heavy tycoon concept built around zombie production, staged automation, raids, rebirth progression, and retention-focused rewards.

The game uses a factory-like structure where players unlock and upgrade machines that produce zombie-related resources.

---

## Design Goal

The main goal was to create a tycoon loop that feels:

- Progressively rewarding
- Visually understandable
- Expandable across many machines
- Competitive through raids
- Retention-friendly through daily and playtime rewards

---

## Core Player Loop

```txt
Claim plot
→ Unlock machines
→ Produce zombies / cash
→ Upgrade automation
→ Defend or raid other players
→ Earn more resources
→ Rebirth for long-term progression
→ Repeat with stronger multipliers
```

---

## Machine Pipeline

The production pipeline is built around visible staged progression.

Example machine stages:

| Stage | Machine |
|---|---|
| 1 | Hand |
| 2 | Leg |
| 3 | Skeleton |
| 4 | Nerves |
| 5 | Assembly |

This creates a clear sense of factory growth instead of abstract income generation.

---

## Automation Design

Automation is designed to feel visible and understandable.

Key principles:

- Workers should appear near machines.
- Workers should animate while crafting.
- The manager NPC should appear near claim/output areas.
- Machine unlocks should be readable.
- Future machines can appear as locked previews.

The player should understand what changed after every upgrade.

---

## Economy Design

The base economy follows a simple readable rule:

```txt
Each zombie = cash generation over time
```

However, price scaling, rebirth requirements, worker upgrades, raid rewards, and production multipliers must be tuned carefully to avoid:

- Too-fast progression
- Empty mid-game
- Rebirth becoming meaningless
- Late-game inflation
- No reason to raid or defend

---

## Raid System

Raids add social competition and resource risk.

Important raid rules:

- Periodic raid opportunities
- Cannot raid the same target repeatedly
- Protection window after being raided
- Defender can benefit if they win
- Attacker can steal partial resources if successful

This creates risk/reward without making the game feel punishing.

---

## Rebirth System

The rebirth system is designed as long-term progression.

Design goals:

- Encourage replay
- Unlock deeper machine tiers
- Increase production potential
- Create long-term goals
- Avoid making early progression too slow after each reset

A strong rebirth system needs meaningful unlock pacing and visible reward growth.

---

## Retention Systems

Retention features include:

- Daily rewards
- Daily playtime rewards
- Community group reward
- VIP presentation
- Leaderboards
- Top player statues
- Donation / monetization visibility

These systems support repeat sessions and social status.

---

## UI/UX Considerations

The UI should support:

- Machine panel
- Automation panel
- Raid panel
- Daily rewards panel
- Store panel
- Leaderboard display
- VIP / nameplate feedback

Mobile readability is important because Roblox players often use smaller screens.

---

## Technical Implementation Notes

Likely system modules include:

- Machine Service
- Worker NPC Service
- Rebirth Service
- Raid Service
- Leaderboard Service
- Client UI Bridge
- Monetization / Gamepass handling
- DataStore persistence

The goal is to keep economy, UI, persistence, and raid logic separated.

---

## Portfolio Value

This case study demonstrates:

- Tycoon economy design
- Multiplayer retention systems
- Raid rule design
- Rebirth progression planning
- Roblox systems thinking
- Monetization-aware design
- Technical design documentation
