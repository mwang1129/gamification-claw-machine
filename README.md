# Chore Club

A static arcade chore app built with HTML, CSS, and JavaScript, with no frameworks or build step.

## Features

- Playable claw machine with keyboard, pointer, and touch controls
- Saved chores with search, renaming, deletion undo, and pinned priorities
- Weighted capsules for priority chores
- First-completion rewards: 30 coins for priority chores and 10 for lower-priority chores
- A shop for themes and capsule colors
- Chore progress, daily streaks, personal bests, and weekly milestones

Data is saved in the current browser's local storage; it does not sync between devices.

## Run locally

Open `index.html`, or run `node server.cjs` and visit http://127.0.0.1:4173. The Node server is optional and uses only built-in modules.

## GitHub Pages

In repository Settings → Pages, choose Deploy from a branch, then select `main` and `/ (root)`. No build step is needed. Pages availability depends on repository visibility and the account plan.

The optional Google Fonts stylesheets have local font fallbacks. Gameplay requires no external libraries or services.
