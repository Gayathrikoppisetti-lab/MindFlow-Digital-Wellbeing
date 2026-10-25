# Manual Testing Checklist

Open `index.html` in a browser and complete these checks. Mark a test as passed **only after you run it**.

- [ ] Dashboard loads and navigation changes the visible page.
- [ ] On App Usage, change simulated screen time and pickups; save and check dashboard values.
- [ ] On Goals, change daily limit and verify progress changes.
- [ ] On Focus Mode, select 1 minute, start, pause, resume, and reset.
- [ ] Allow a 1-minute focus session to finish and check Achievements.
- [ ] On Mindful Breaks, start, pause, resume, and reset the 2-minute timer.
- [ ] Allow a mindful break to finish and check its achievement.
- [ ] Change the display name in Settings and check Dashboard greeting.
- [ ] Refresh the page and verify saved settings and completed counts persist.
- [ ] Reset demo data and verify defaults return.
- [ ] Check layout on phone and desktop widths.

## Real-world testing note

These tests evaluate **user interaction and UI behavior**. Actual Android/iOS app screen-time collection is **not** supported by this website and requires a separately developed native application and platform permissions.
