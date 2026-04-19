# Temporal

A terminal-based focus session timer that helps you stay productive by timing your coding sessions. Inspired by a childhood timer bookmark that helped develop a lifelong love of reading.

## Motivation

As software engineers, we often struggle to balance productive work with gaming or other distractions. Temporal gives you a visual countdown and motivational reminders so you can earn your play time through focused work.

## Features

- **Configurable Session Timer** — Set goals for 1, 2, 3, 4 hours or custom duration
- **Interactive TUI** — Built with Bubbletea for a smooth terminal experience
- **Progress Tracking** — Tracks your daily productive time
- **Alarm System** — ASCII banner + system notification when sessions complete
- **Motivational Quotes** — Random encouragement from a local collection
- **Persistence** — Your progress and config persist between sessions

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/temporal.git
cd temporal
# Build
go build -o temporal .
# Run
./temporal
Usage
Key
s / t
p
c
q
Roadmap
v1 — MVP (Current)
- [x] Session timer with configurable goal
- [x] Keyboard controls
- [x] Progress bar display
- [x] Alarm system with quotes only
- [x] Local persistence
v2 — Activity Aware (Planned)
- [ ] Auto-detect active window
- [ ] Track productive vs gaming time
- [ ] Warning on context switch
v3 — Gamification (Planned)
- [ ] Pomodoro cycles
- [ ] Daily streak tracking
- [ ] Game token system
License
MIT
```
