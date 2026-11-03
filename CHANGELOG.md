# Changelog

All notable changes to Bills Tracker. Newest first. Each entry matches a GitHub Release.

## v1.1.0 - 2026-11-03
Pay schedule option: once or twice a month
- New Setup option "How often are you paid?": once a month, or twice a month (15th and month-end).
- Twice a month: set the month-end payout, the 15th payout and a split day (default 15).
- Bills due on or before the split day are paid from the month-end payout (received the month before); later bills from the 15th payout.
- Month view shows each payout's money in, bills and what is left, and groups bills under each payout.
- Per-payout overrides for any month in the Savings tab.
- Existing once-a-month data keeps working unchanged.
- Android APK now lives in the repo (`android/BillsTracker.apk`) and is attached to each release automatically.

## v1.0.3 - 2026-11-03
iPhone layout fix, round 3
- Header now clears the status bar (confirmed on device in v1.0.2).
- When opened from the Home Screen, the app is sized to the full screen height to remove the extra space under the tab bar.
- Setup now shows "Build v1.0.3 · view H/S" (visible height / screen height) to help diagnose sizing.

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
