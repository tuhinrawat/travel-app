# Travel App

A cross-platform travel application built with Flutter, designed for iOS and Android. This app features a vibrant UI inspired by Instagram, with a modular project structure and Firebase integration for authentication and data storage.

## Features

- **Modular Project Structure**: Organized into `lib/features`, `lib/core`, `lib/models`, and `lib/services` for better maintainability.
- **Firebase Integration**: Authentication (Google, Facebook, Apple Sign-in) and Firestore for data storage.
- **Dependencies**: Uses `dio` for HTTP requests, `Riverpod` for state management, `flutter_secure_storage` for secure storage, and `fl_chart` for charts.
- **UI Scaffold**: Includes a bottom navigation bar with animated travel icons, an AppBar with dynamic search and profile avatar, and a splash screen with a looping travel video background.
- **Design**: Features a vibrant palette (#FF6F61, #1E88E5), glassmorphism cards, smooth animations, dark/light mode, and accessibility features.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/tuhinrawat/travel-app.git
   cd travel-app
   ```

2. **Install Dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the App**:
   ```bash
   flutter run
   ```

## GitHub Setup

- **Repository**: Private repository named `travel-app` under `tuhinrawat@gmail.com`.
- **Branches**: `main` (production), `dev` (development), and `feature/*` for new features.
- **GitHub Actions**: CI/CD pipeline for running tests and linting on push.
- **API Keys**: Stored in GitHub Secrets (e.g., `FIREBASE_API_KEY`, `AMADEUS_API_KEY`).

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
