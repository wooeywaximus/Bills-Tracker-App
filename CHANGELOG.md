# Changelog

All notable changes to Bills Tracker. Newest first. Each entry matches a GitHub Release.

## v1.0.2 - 2026-11-03
iPhone layout fix, round 2
- Bottom tab bar is now part of the page layout instead of floating, so no gap under it on iOS 26.
- Page background matches the tab bar, so any leftover edge is invisible.
- App always fetches the newest files (no stale cached copy).
- "Build v1.0.2" label added at the bottom of Setup so you can tell which version is running.

## v1.0.1 - 2026-11-03
iPhone layout fix (web app)
- Header no longer draws under the status bar/notch.
- App frame pinned to the full screen so the bottom tab bar sits at the screen edge.
- "+ One-off" button and pop-up messages lifted to clear the home-bar area.
- Service worker cache bumped to `bills-v2` so installed copies update.

## v1.0.0 - 2026-11-03
First release
- Starts with blank data and a 3-step welcome card.
- Month view with payout, bills, paid, left after bills, free to spend and running balance.
- Bills (fixed, variable, installment, one-off), savings goal, payoff chart, settings.
- Backup and restore (share sheet on iPhone/Android).
- iPhone/web: installable PWA (Add to Home Screen), works offline.
- Android: sideloadable APK (attached to the release).
