# Shadow Clone

A small debug notebook. Save notes and bugs by typing them, compare notes, and get a generic tip. It does not see your screen.

- Kind: code mod
- Made by: flaqueeee

## Commands

Every command starts with "clone":

- `clone capture <text>` - save a note about what you're working on
- `clone compare` - compare your last two notes
- `clone track bug <text>` - log a bug
- `clone bugs` - list open bugs
- `clone ideas` - get a generic tip based on your last note's type
- `clone analyze` - keyword check of your last note
- `clone clear` - drop the current note
- `clone help` - list the commands

Capture only stores the text you give it. It never looks at your screen, and the tips and analysis are simple canned ones, not real inspection.

## Where it saves

Notes and bugs are saved as `contexts.txt` and `bugs.txt` in a `shadow-clone` folder inside its own mod folder.

Code mods are Windows only for now.
