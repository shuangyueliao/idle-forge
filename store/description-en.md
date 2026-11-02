# Idle Forge — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Strike the anvil to forge gold, then automate your smithy: auto-smiths, hammer
power, critical hits and an offline boiler. Hit milestones to craft legendary
gear from iron sword to dragon armor!

## Details

- Genre: Idle / Incremental / Casual
- Controls: Mouse / Touch (tap the anvil to forge). Keyboard: Space or Enter.
- Features: 4 upgrade tracks (Auto Smith x1.15 pricing, Hammer Grip click power,
  Crit Strike up to 50% for x5 gold, Forge Boiler for offline earnings up to 2h),
  milestone system (1K/10K/100K/1M total forged unlocks Iron Sword, Silver Bow,
  Gold Crown, Star Diamond, Dragon Armor), offline welcome-back panel, autosave
  every 5 seconds, number formatting (1.23K/M/B), mute toggle.
- Tech: Vanilla JavaScript, Canvas, WebAudio. Single-file HTML5, zero external
  assets, procedural graphics and sounds. No frameworks, no tracking.
- Works offline once loaded. Portrait-friendly responsive layout, mobile touch
  and desktop keyboard both supported.

## Tags
idle, incremental, clicker, forge, medieval, casual, offline, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop wired (first interaction + visibility), loadingStart / loadingStop, happytime on milestones
- [x] Responsive (canvas + panels scale, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover / screenshots (not produced in this pass)

## itch.io
- Upload idle-forge-itch.zip, mark "This file is playable in browser",
  entry file: index.html, kind: html, viewport: responsive (max width 520px)
- Pricing: $0 (donations optional)

## GameDistribution
- Upload idle-forge-gd.zip (contains index.html only) as an HTML5 game.
- SDK (gamedistribution v2) auto-loads on gamedistribution / gd.games domains only.
