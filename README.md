# TuneFinder

TuneFinder is a music recognition app built using Flutter and Dart. It allows users to identify songs by listening to audio, providing details like song title, artist, and album information. The app is powered by **ArcCloud** for music recognition and utilizes **Riverpod** for state management, ensuring efficient, scalable, and reactive state handling across the app.

## Features

- **Real-Time Song Recognition:** Instantly recognize any song playing around you.
- **Detailed Song Info:** Get the title, artist, album, and other song metadata.
- **History:** Keep track of all the songs you've identified in your search history.
- **Minimalist UI:** Clean and user-friendly interface for seamless interaction.

## Tech Stack

- **Flutter**: Cross-platform mobile app development framework.
- **Dart**: Programming language used for Flutter app development.
- **Riverpod**: State management solution for scalable and reactive state management.
- **ArcCloud**: Cloud-based music recognition service for identifying audio tracks.

## Getting Started

Follow the steps below to get the project up and running on your local machine.

### Prerequisites

- Flutter SDK: [Installation Guide](https://flutter.dev/docs/get-started/install)
- Dart SDK (included with Flutter installation)
- ArcCloud API Key: Obtain your API key from [ArcCloud](https://arccloud.com/) to enable music recognition.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AbdulRahmanMudasser/tunefinder.git
   cd tunefinder

2. **Install Dependencies:**

   Run the following command to install the necessary dependencies:

   `flutter pub get`

3. **Setup ArcCloud API Key:**

   In the lib/config/api_keys.dart file, add your ArcCloud API key:

    `const String arcCloudApiKey = 'YOUR_API_KEY_HERE';`

4. **Run the App:**

    Use the following command to run the app on your connected device or emulator:

   `flutter run`

## Project Structure

The project follows a clean and organized structure:

lib/
│
├── main.dart                 // Entry point of the app
├── config/                   // Configuration files (API keys, environment variables)
├── models/                   // Data models (song, artist, etc.)
├── providers/                // Riverpod providers for state management
├── services/                 // API services (ArcCloud integration)
├── screens/                  // UI screens (Home, Song Detail, History)
└── widgets/                  // Reusable UI components

## State Management

This project uses Riverpod for state management, ensuring a clean separation of concerns and making it easy to handle global app state in a scalable and reactive manner. All app states (such as search history, currently identified song, etc.) are managed efficiently with providers.

## Contributing

Contributions are welcome! If you’d like to contribute, please follow the contribution guidelines.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Contact
If you have any questions or feedback, feel free to reach out:

GitHub: AbdulRahmanMudasser

Email: abdulrahmanmuddasser@gmail.com
