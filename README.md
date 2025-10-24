# Card Game Mini Webapps

Minimal collection of single-file web apps for running small card-game utilities.

## Included files
- blind-timer.html — Blind‑First Poker Timer (editable structure, auto‑advance, beep + flash).
- blackjack-counter.html — Blackjack Card Counter (running/true count, history, basic strategy, bet spread).

## Quick start
1. Save the HTML files to your computer.
2. Open a file in any modern browser (Chrome, Edge, Firefox, Safari).
3. Interact with the UI directly; use the Start/Stop controls for the timer and the card buttons or keyboard for the counter.

## Basic usage
- Blind Timer: open Structure (overlay) to add/edit levels or breaks, select a level, then Start. Timer auto‑advances after the cue finishes.
- Blackjack Counter: click card buttons or press keys (1=A, 2–9 = ranks, 0 = 10/face cards). Use R to reset. Adjust decks to compute True Count.

## Keyboard shortcuts
- Blackjack Counter: 1 = A, 2–9 = 2–9, 0 = 10/face cards, R = Reset.

## Customization
- Edit levels, durations, and blinds directly inside the timer UI or modify the initial rows array in the HTML.
- Change beep/flash timing and WebAudio parameters in the timer script.
- Modify count system (countValues) or default bet spread in blackjack-counter.html.

## License
Use freely for personal, club, or internal use. Include attribution if redistributed.
