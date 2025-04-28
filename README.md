WiFi Signal Logger is an Android application built using Kotlin and Jetpack Compose. The app allows users to scan and log WiFi signal strengths (RSSI) at different locations, visualize the data, and compare signal strengths between locations.

## Features

- **WiFi Signal Scanning**: Scan and log WiFi signal strengths for a specific location.
- **Signal Visualization**: View signal strength data in a graphical format.
- **Location Management**: Save and manage multiple locations for signal data.
- **Location Comparison**: Compare average signal strengths between different locations.
- **Permissions Handling**: Requests and manages location permissions required for WiFi scanning.

## Technologies Used

- **Kotlin**: Primary programming language.
- **Jetpack Compose**: For building the UI.
- **Coroutines**: For asynchronous operations.
- **Gradle**: Build system.

## Prerequisites

- Android device with **API level 24 (Android 7.0)** or higher.
- WiFi enabled on the device.

## Permissions

The app requires the following permissions:
- `ACCESS_FINE_LOCATION`: To scan WiFi networks.
- `ACCESS_WIFI_STATE`: To access WiFi state.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/wifi-signal-logger.git
   ```
2. Open the project in Android Studio.
3. Sync the Gradle files.
4. Build and run the app on an emulator or physical device.

## Usage

1. Launch the app.
2. Enter a location name in the input field.
3. Tap the **Scan WiFi Signals** button to start scanning.
4. View the signal data for the selected location.
5. Compare signal strengths between different locations.

## Project Structure

- `app/src/main/java/com/example/a3_task2/MainActivity.kt`: Contains the main activity and UI logic.
- `app/src/main/AndroidManifest.xml`: Defines app permissions and metadata.
- `app/build.gradle.kts`: Module-level Gradle configuration.
- `build.gradle.kts`: Project-level Gradle configuration.

## Dependencies

The project uses the following dependencies:
- Jetpack Compose libraries for UI.
- Material3 for modern UI components.
- AndroidX libraries for lifecycle and activity management.
- Kotlin Coroutines for asynchronous programming.
