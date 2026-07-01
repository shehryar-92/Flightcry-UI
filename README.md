# Flightscry

Android UI proof-of-concept for a flight itinerary screen, built with Skyscanner's Backpack design system.

## Features
- Flight info card (flight number)
- Departure card (airport code + time)
- Arrival card (airport code + time)
- Static dummy data — no backend integration (PoC only)

## Tech Stack
- Kotlin
- Android Views + XML layouts
- Backpack Android (`net.skyscanner.backpack:backpack-android:43.0.0`)
- Gradle

## How to Run

**Requirements:** Android Studio (recommended for visual preview) or Android SDK + Gradle (CLI only).

Clone the repo:
```bash
git clone <your-repo-url>
cd Flightscry-UI/flightscry
```

Build (verifies compilation):
```bash
./gradlew assembleDebug
```

For visual preview, open the `flightscry` folder in Android Studio and run on an emulator or device.

## Notes
Developed in GitHub Codespaces (CLI-only environment, no emulator access). Build verified via `./gradlew assembleDebug`; UI not visually tested in this environment — recommend opening in Android Studio to preview.
