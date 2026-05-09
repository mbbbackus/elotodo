# ELOTodo

ELOTodo is a todo list that ranks itself. Instead of forcing you to set priorities up front, it shows you two tasks at a time and asks which one matters more right now. Each comparison updates an ELO score for the tasks involved, and over a handful of rounds your list sorts itself from "do this next" to "probably never."

The whole app is a single static `index.html` — no build step, no backend, no account. State lives in your browser.

## Why pairwise?

Looking at a long flat list and trying to assign priorities is hard. Comparing two things at a time is easy. ELO turns a series of easy choices into a stable ranking.

## Contributing

We're open to contributors. Bug fixes, UX tweaks, new ranking heuristics, accessibility improvements — all welcome. Open an issue or send a PR.
