# Temporal

A Go terminal-based focus session timer using Bubble Tea TUI framework.

## Build & Run

```bash
go build -o temporal .
./temporal
```

## Project State

- **MVP in progress** — core timer, keyboard controls, progress bar, alarm with quotes, local persistence
- No test suite yet
- No generated code or migrations
- Entry point: `main.go` (not yet created)

## Key Files

- `README.md` — feature overview and roadmap
- `.gitignore` — Go-standard ignores

## Conventions

- Standard Go project layout
- Single binary output: `temporal`
- Local data persistence to filesystem

## Roadmap Priority

v1: Session timer with configurable goal (current)
v2: Auto-detect active window, track productive vs gaming time
v3: Pomodoro cycles, daily streak tracking, game token system