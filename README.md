# Today's Draw

One habit or hobby a day, drawn for you, so you don't have to decide. Open it, see today's thing, ask Siri for a timer, and start.

## What it does

- **Daily three** at the top: Move (#1), Tidy, Connect. Check them off every day; they're not part of the random pick
- Moving is what keeps your streak alive, so a rough day where you only moved still counts
- Picks one habit each day. The longer since you last did something, the likelier it comes up, so nothing gets forgotten
- ★ Focus habits come up about twice as often (star the 1–2 you most want to get better at)
- One re-roll a day
- After you finish, an optional **bonus spin** picks another one (as many as you want)
- ✓ any habit in your list to log it, even if it wasn't the pick, so tomorrow's pick stays smart
- **Graduate** a habit once it's automatic: it leaves the roulette and goes in your Graduated list (bring it back anytime)
- Each habit has its own default minutes; nudge today's time up or down
- Rough day? "Did 2 min" still counts and keeps your streak
- "I kept going" adds 10 more minutes to today's log
- After you finish, jot what to work on next time; it shows up the next time that habit comes up
- **Calendar** tab: a month view with a dot for days you moved and a ✦ for each habit; tap a day to see what you did (no "missed" marks, ever)
- **Habit tip** of the day: 30 research-backed tips that rotate daily (tap Another for more)
- Streak, days this month, and how often you've done each habit
- Everything saves on the device; **Backup & restore** at the bottom lets you copy it out and paste it back (for re-adding the app or a new phone)

## Files

```
index.html             # The whole app (no build step)
manifest.webmanifest   # Lets phones install it with an app icon
sw.js                  # Service worker so it opens offline
icons/                 # App icons (192, 512, Apple touch icon)
```

## Running it

Hosted free on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

- **iPhone:** open the Pages link in Safari → Share → Add to Home Screen
- **Android:** open it in Chrome → ⋮ menu → Add to Home screen / Install app

When you change a file, bump `VERSION` in `sw.js` so phones pick up the update.

Built by Anna via Claude.
