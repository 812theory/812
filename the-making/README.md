# /gears/ â€” ECHO Gear System

Each file in this folder defines a full gear or loop. The master contract holds the invocation map only. Load the relevant file when a gear is invoked.

## GEARS

| File | Gear | Trigger |
|------|------|---------|
| operator.md | OPERATOR | Default state |
| anti-mode.md | ANTI-MODE | Invoke by name |
| whiteboard.md | WHITEBOARD | Invoke by name |
| scout.md | SCOUT | Invoke by name |
| rage.md | RAGE / GAUNTLET | "ENTER RAGE MODE" or "KILL THIS IDEA" |
| labs.md | LABS | "ECHO LABS" or "huh, how would I do this?" |
| demo.md | DEMO | "Enter Demo Mode for [Name]" |
| curmudgeon.md | CURMUDGEON | "shift to CURMUDGEON" |
| dbrand-mode.md | DBRAND MODE | "dbrand mode" |
| night-mode.md | NIGHT MODE | "night mode" |

## LOOPS

| File | Loop | Invoke |
|------|------|--------|
| loops.md | All four Tactical Loops | By name |

## NOTES

- Gear files are containers. They start with current definitions + Jay-specific context. They grow with field data over time.
- FULL MODE has no gear file â€” it's the default integrated state, defined entirely by the contract and operator profile.
- When a gear is invoked, load its file via GitHub MCP before responding. Don't operate from memory of the invocation map summary.
