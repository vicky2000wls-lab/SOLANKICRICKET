# SOLANKICRICKET Android

Ready-to-build Android Studio/Gradle project for SOLANKICRICKET.

Features:
- Live cricket scoring
- 6 legal balls = completed over
- Wide/No-ball do not consume a legal ball
- Bye/Leg-bye consume a legal ball
- Wickets, runs, ball-by-ball log, scorecard
- Team/player management
- Local backup/restore
- Portrait Android interface
- GitHub Actions debug APK build

## Build on GitHub
Push this project to the `main` branch. Open **Actions → Build SOLANKICRICKET APK**.
The workflow also has `workflow_dispatch`, so the **Run workflow** button is available.

## Important
The included `solanki_cricket_bg.jpg` is a branded placeholder because the original image bytes were not available in this build environment. Replace that file with your preferred background image while keeping the same filename.
