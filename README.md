# Drive to MSU 🚗

An Android application project that uses device location to help initiate navigation to Montclair State University.

## Features represented in the source

- Requests location permission from the user
- Uses Google Play Services' Fused Location Provider
- Configures high-accuracy location updates
- Receives latitude and longitude updates
- Uses the current location as the basis for navigation toward Montclair State University

## Tech Stack

- Java
- Android SDK (compile / target SDK 34; minimum SDK 24)
- Google Play Services Location 18.0.0
- AndroidX AppCompat
- Material Components
- ConstraintLayout

## Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/SRIKALYANBHAVANTHI/DrivetoMSU.git
   ```
2. Open the project in Android Studio.
3. Allow Gradle sync to complete.
4. Run the **app** configuration on an Android device or emulator.
5. Grant location permission when prompted. Location features require a device or emulator with location services enabled.

Build a debug APK:

```bash
./gradlew assembleDebug
```

Windows:

```bat
gradlew.bat assembleDebug
```

## Project Structure

Main activity: `app/src/main/java/com/example/drivetomsu/MainActivity.java`

Android layouts and resources: `app/src/main/res/`

## Privacy Note

The application accesses device location for its navigation workflow. Review the permission flow and location handling before using or distributing the app.

---

Created by [Srikalyan Bhavanthi](https://github.com/SRIKALYANBHAVANTHI).
