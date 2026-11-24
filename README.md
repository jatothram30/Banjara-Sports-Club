# Banjara Sports Club v2

Android Capacitor starter with an expanded cricket scoring prototype.

## Build
1. Upload the contents of this folder to the root of the GitHub repository.
2. Commit to `main`.
3. Open Actions and run `Build Android APK`.
4. Download artifact `Banjara-Sports-Club-APK`.

## Current scoring features
- Match setup, teams, overs, venue, opening batters and bowler
- Runs, wides, no-balls, byes, leg-byes, wickets and undo
- Batter replacement, retired hurt, strike and bowler changes
- Innings/chase target, scorecard, bowling figures and ball history
- Share current score through Android share sheet

## Important limitation
This version scores on the current device/session. Sending a score through the share sheet is not the same as a public live scoreboard. Real-time multi-device live scores, accounts, admin/scorer approvals and permanent cloud history require a Firebase or equivalent backend and deployment configuration.
