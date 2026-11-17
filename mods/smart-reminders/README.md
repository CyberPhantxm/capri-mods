# Smart Reminders Plus

Context reminders: say "remind me when I'm back on X to do Y" and Capri nudges you the next time you mention X. For timed reminders, just ask Capri.

- Kind: code mod
- Made by: flaqueeee

## Commands

- `remind me when I'm back on X to do Y` (also "when I get back to X", "when I open X", "when I go back to X", "when I switch to X")
- `context reminders` - list waiting context reminders
- `clear context reminders` - delete the waiting ones
- `context reminders help` - show these commands

For timed reminders ("remind me in 20 minutes"), just ask Capri. This mod leaves those to her.

## How it works

The mod does not watch your screen or apps. A reminder fires the next time a line you say to Capri contains the X you named (for example "Visual Studio"), as long as at least 30 seconds have passed since you set it. Capri still answers that line as usual.

Reminders are saved in `reminders.txt` in this mod's own folder and survive restarts.

Code mods are Windows only for now.
