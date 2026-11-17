# Work Context Memory

Saves named work contexts and tracks the time you spend on each project between sessions, so you can recall what you were last working on.

- Kind: code mod
- Made by: flaqueeee

## Commands

- `context save [name]` - save your current work under an optional name
- `context recall` or `last context` - hear your most recent context and how long ago it was
- `context stats` - time per project
- `context list` - recent contexts
- `context help` - list the commands

If you save the same context again within 60 minutes, the elapsed time is added to that project's total. The mod does not look at your screen; it only stores what you tell it.

## Where it saves

Everything is stored in the mod's own folder (`contexts/sessions.txt` and `current-context.txt`).

Code mods are Windows only for now.
