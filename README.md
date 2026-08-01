# Time-to-Rupee Stopwatch

A simple stopwatch that converts every minute of time into money — by default, **1 minute = ₹1**. It's a way to put a real, visible price tag on the time you spend (or lose) on something.

## Why this exists

Time feels abstract — it just slips by. Money doesn't; we notice it. This app bridges the two: it turns ticking seconds into a rupee amount that keeps climbing on screen, so you can *see* what your time is costing you (or worth to you) in real terms.

Use it to:
- See how much time you're **wasting** on distractions, procrastination, or waiting around — watch the rupee count grow as a reminder to stop.
- Track how much your time is **worth** while working, studying, or freelancing.
- Build awareness around idle time, meetings, commutes, or any activity you want to measure the "cost" of.

## How it works

1. **Set your rate** — the box at the top lets you set how many rupees one minute is worth (defaults to ₹1/min). Adjust it before starting if 1 minute should equal something other than ₹1.
2. **Start** — begins the stopwatch. The timer (HH:MM:SS) and the rupee amount update live, every fraction of a second — not just once a minute. So 30 seconds already shows ₹0.50 at the default rate.
3. **Pause** — freezes both the timer and the amount exactly where they are. You can resume later with Start.
4. **Reset** — stops everything and brings the timer and amount back to zero.
5. The status label at the bottom (RUNNING / PAUSED / STOPPED) always tells you the current state at a glance.

## Files

- `stopwatch-billing.html` — the app itself. Open it in any browser, no installation needed.

## Notes

- All calculation happens in your browser; nothing is saved or sent anywhere. Closing or refreshing the page resets it.
- The rate field is locked while the stopwatch is running — pause or reset first if you want to change it.
