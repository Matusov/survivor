# Survivor 51 Fantasy League

A mobile-first, dark-themed fantasy league tracker for **Survivor 51 (The Open Era)** —
Matusov vs O'Brien.

Open on your phone → **Share → Add to Home Screen** to run it full-screen.

## Tabs
- **Home** — Teams scores, family showdown, rules, scoring
- **Cast** — all 21 castaways with bios and photos
- **Picks** — 3 picks per player; locks automatically Wed Sep 30, 7:59 PM ET
- **Scores** — leaderboard + commissioner tools (PIN-protected)

## Commissioner
Episode results are entered manually: **S**urvived / **I**mmunity / **R**eward, plus **OUT**
for the episode a castaway is voted out. Final 3 and Winner bonuses at season's end.
Commissioner tools sit behind a 4-digit PIN (a convenience lock, not real security).

## Icons and caching
Icons are flat **RGB (no alpha channel)** on pure black, at every iOS size. They are served under
**content-hashed filenames** (`icons/apple-touch-icon-<version>-<size>.png`) so iOS can never reuse a
stale home-screen icon after an update. `favicon.ico` is a real multi-resolution ICO.

If an old icon still appears on an existing home-screen shortcut, delete that shortcut and re-add it —
iOS caches home-screen artwork per shortcut and does not refresh it.

## Disclaimer

Personal fan project. **Not affiliated with, endorsed by, or sponsored by CBS or Paramount.**
"Survivor" and the Survivor logo are trademarks of CBS Broadcasting Inc. Cast photos are
official CBS press images (© Robert Voets/CBS) and the logo is used for identification only.
All trademarks and copyrights are the property of their respective owners.
