# FitCheck

## Description
Our app makes fashion fun by gamifying everyday style and inspiring creativity. Each night, users receive a theme for the next day’s outfit—think “red” or “denim.” The following day, they share photos of their outfits, and friends vote on who nailed the theme best. It’s like BeReal, but for outfits!

## Living Document
[View the detailed plan and progress](https://docs.google.com/document/d/1CZu642kOHpgtLdXkNPS8U6OsxPTkgixnqs-X6VRMPes/edit?tab=t.0)

---

## Completed Features
- **User Authentication**: Sign up, log in/out, user profiles with picture and username.
- **Daily Outfit Challenges (P0)**: Receive a daily theme, submit photos within the time window.
- **Database**: Stores user info (followers, following, posts count, username) and all outfits.
- **Awarding System**: Heart-based awards with daily limits; tracked in the leaderboard.
- **Leaderboard & Badges (P1)**: Shows top three users; badges based on earned hearts.
- **Friend Search (P2)**: Search by username to view a friend’s latest post and profile stats.
- **OTP & Account Creation**: Fully functional one-time-passcode flow.
- **Backend**: Complete data storage and retrieval.

---

## Current Use Case
- **Goal**: Post your daily outfit photo!
- **Primary Actor**: Signed-in user.
- **Trigger**: User opens the app and taps the camera/upload button on the daily theme screen.
- **Preconditions**: User is authenticated; daily challenge is active.
- **Postconditions**: Photo uploads, processes, and appears on feed for likes/comments.

---

## Getting Started
Follow these steps to install Flutter, Dart, and run FitCheck locally.

### 1. Install Prerequisites
1. **Flutter & Dart SDK**
   - Visit [Flutter Install](https://flutter.dev/docs/get-started/install) and follow the guide for your OS.
   - Ensure Flutter’s `bin` directory is added to your PATH.
   - Verify setup:
     ```bash
     flutter doctor
     ```
2. **IDE**
   - **Visual Studio Code**: Install the Flutter and Dart extensions.
   - **Android Studio**: Install the Flutter plugin and Android SDK components.
3. **iOS (macOS only)**
   - Install Xcode from the App Store.
   - After Xcode install:
     ```bash
     sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
     ```

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/fitcheck.git
cd fitcheck
```

### 3. Fetch Dependencies
```bash
flutter pub get
```

### 4. Build the App
- **Android (APK)**
  ```bash
  flutter build apk
  ```  
- **iOS**
  ```bash
  flutter build ios
  ```

### 5. Run the App
- **Android Emulator / Physical Device**
  ```bash
  flutter run
  ```
- **iOS Simulator**
  ```bash
  flutter run -d ios
  ```
- **List Available Devices**
  ```bash
  flutter devices
  ```

---

## Testing
Run unit and widget tests:
```bash
flutter test
```

---

## Project Structure
```
fitcheck/
├── android/        # Android platform configuration
├── ios/            # iOS platform configuration
├── lib/            # Dart code
│   ├── main.dart   # App entry point
│   ├── screens/    # UI screens
│   ├── widgets/    # Reusable widgets
│   └── services/   # Business logic & API calls
├── assets/         # Images, fonts, etc.
├── test/           # Unit & widget tests
└── pubspec.yaml    # Dependencies & project metadata
```

---

## 📌 Beta++ Release
- **Tag:** [v2.0-beta++](https://github.com/chaafenr/fitcheck/releases/tag/v1.0-beta++)
- **Last Commit:** March 11, 2025

